<template>
  <section id="about" class="section-about">
    <div class="text-center mb-20">
      <h2 class="heading-secondary">About Ordinal Camels</h2>
    </div>
    <div class="container-about text-center">
      <img
        class="camel-photo mx-auto mb-32"
        src="../assets/camel-nft.png"
        alt="camel"
      />
      <div class="faq mb-[10rem]" v-for="item in faq" :key="item.question">
        <h3 class="heading-tertiary mb-5">
          {{ item.question }}
        </h3>
        <p class="paragraph mx-[4%]">
          {{ item.answer }}
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "my-about",
  data() {
    return {
      faq: [
        {
          question: "Who are we?",
          answer:
            "We are a brand new NFT collection of 125 pixelated Camels inscribed as ordinals on the BTC blockchain forever! Not a basic copy pasta or deriv NFT project from an existing ETH collection either. 🐪🐪🐪",
        },
        {
          question: "How many Camels are in the total collection?",
          answer: "125 Camels",
        },
        {
          question: "Why a collection on Bitcoin?",
          answer:
            "Ordinals are stored fully on-chain. Your Camel is permanently stored on the most secure blockchain.",
        },
      ],
    };
  },
};
</script>
