<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta
      exercitationem dolores officia! Blanditiis quia iusto suscipit similique
      officia distinctio aperiam, qui tempore, quas possimus aliquid totam
      impedit alias quaerat molestiae! Lorem ipsum dolor, sit amet consectetur
      adipisicing elit. Dolores labore accusamus quo nam cumque. Adipisci
      suscipit omnis alias animi laudantium fugiat provident, accusamus sunt
      iure aliquid fuga illo, illum consequatur.
    </p>
    <img src="@/assets/img/presentation.svg" alt="Apresentação do ibook">
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
