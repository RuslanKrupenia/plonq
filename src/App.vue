<template>
<HeaderComponent/>
<HomeComponent/>
<PlonqxComponent/>
<ProductComponent/>
<MapComponent/>
<InfoComponent/>
<FooterComponent/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import HomeComponent from './components/HomeComponent.vue'
import PlonqxComponent from './components/PlonqxComponent.vue'
import ProductComponent from './components/ProductComponent.vue'
import MapComponent from './components/MapComponent.vue'
import InfoComponent from './components/InfoComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,HomeComponent,PlonqxComponent,ProductComponent,MapComponent,InfoComponent,FooterComponent,
  }
}

</script>


<style lang="scss">
@import "~normalize.css/normalize.css";
html,body{
  font-family: 'Gotham Pro';
  font-size: 14px;
}
</style>

