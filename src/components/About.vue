<template>
  <div>
    <article>
      <p>
        App desenvolvido por <a href="http://www.joaorigotti.com">joaorigotti</a>, mais para praticar Vue.js do que pela funcionalidade em si.
      </p>

      <p>Se for útil é um plus...</p>

      <p>
        O app não sincroniza com nenhum servidor. Todas as informações ficam armazenadas no prórpio navegador.
      </p>
    </article>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '../assets/styles/vars.scss';

article {
  width: 80%;
  margin: 0 auto;

  p {
    color: $text-color;
    font-size: 1.25rem;
    text-align: left;
    margin-bottom: 1.4rem;
  }
}
</style>
