<template>
  <div id="app">
    <HeaderComponent />
    <main>
      <CartComponet />
    </main>
    <FooterComponet />
  </div>
</template>

<script>
import FooterComponet from "@/components/Footer/Footer.vue";
import HeaderComponent from "@/components/Header/Header.vue";
import CartComponet from "@/components/Cart/Cart.vue"

export default {
  name: 'App',
  components: {
    FooterComponet,
    HeaderComponent,
    CartComponet
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
