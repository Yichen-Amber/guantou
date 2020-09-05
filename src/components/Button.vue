<template>
  <button class="button"
          @click="$emit('click',$emit)">
    <slot/>
  </button>
</template>

<script lang="ts">
  import Vue from 'vue';
  import {Component} from 'vue-property-decorator';

  @Component
  export default class Money extends Vue {
  }
</script>

<style scoped lang="scss">
  .button {
    background: #767676;
    color: white;
    border-right: 4px;
    border: none;
    height: 40px;
    padding: 0 16px;

    &-wrapper {
      text-align: center;
      padding: 16px;
      margin-top: 44-16px;
    }
  }

</style>