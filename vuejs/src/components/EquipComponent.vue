<template>
  <div id="equip-component" class="m-2 p-2 text-center">
    <b-row class="pt-4">
      <b-col><ItemComponent name="EARPIECE" /></b-col>
      <b-col><ItemComponent name="HEADWEAR" /></b-col>
      <b-col><ItemComponent name="FACE COVER" /></b-col>
    </b-row>

    <b-row class="pt-2">
      <b-col offset="4"><ItemComponent name="BODY ARMOR" /></b-col>
      <b-col><ItemComponent name="EYEWEAR" /></b-col>
    </b-row>

    <b-row class="pt-2">
      <b-col cols="8"><ItemComponent name="ON SLING" isDouble /></b-col>
      <b-col><ItemComponent name="HOLSTER" /></b-col>
    </b-row>

    <b-row class="pt-2">
      <b-col cols="8"><ItemComponent name="ON BACK" isDouble /></b-col>
      <b-col><ItemComponent name="MELEE" /></b-col>
    </b-row>

  </div>
</template>

<script>
import ItemComponent from "./itemComponent.vue";
export default {
    name: "EquipComponent",
    props: {},
    components: { ItemComponent }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  #equip-component {
    width: 500px;
    height: 80vh;
    background-color: rgba(66, 66, 66, 0.519);
  }
</style>
