<template>
  <div class="item-component mx-auto" :class="{large: isDouble}">
    <div class="item-name">{{ name }}</div>
    <div class="item-box" :class="{large: isDouble}">

    </div>
  </div>
</template>

<script>
export default {
  name: 'ItemComponent',
  props: {
    name: String,
    isDouble: Boolean,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .large {
    width: 100%!important;
  }

  .item-component {
    width: 130px;
    height: 150px;

    .item-name {
      width: 130px;
      height: 20px;
      padding:0;
      background-color: rgb(22, 22, 22);
      border-radius: 5px 5px 0 0;
      color: rgb(208, 208, 208);
    }


    .item-box {
      width: 100%;
      height: 130px;
      border: 1px solid rgb(22, 22, 22);
    }

  }
  
  

</style>
