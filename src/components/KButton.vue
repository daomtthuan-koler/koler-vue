<template>
  <button>
    Hello world
  </button>
</template>

<script lang="ts">
  import { Component, Vue } from 'vue-property-decorator';

  @Component({
    name: 'k-button',
  })
  class KButton extends Vue {}

  export default KButton;
</script>

<style lang="scss" scope></style>
