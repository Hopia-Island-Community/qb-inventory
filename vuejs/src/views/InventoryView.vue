<template>
  <div>
    <section>
      <AppNavbar />
    </section>
    
    <section>
      <EquipComponent />
      <b-row>
        <b-col cols="4">
          
        </b-col>
        <b-col cols="4">
          <img alt="Vue logo" src="../assets/logo.png">
          <HelloWorld msg="Welcome to Your Vue.js App"/>
        </b-col>
      </b-row>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import AppNavbar from '@/components/AppNavbar.vue'
import EquipComponent from '@/components/EquipComponent.vue'

export default {
  name: 'InventoryView',
  components: {
    HelloWorld,
    AppNavbar,
    EquipComponent
  }
}
</script>
