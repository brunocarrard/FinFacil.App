<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ButtonComponent title="testando" @clicked="this.showMsg = true"/>
  <TextFormComponent title="Nome" />
  <p v-if="showMsg">Botão foi clicado</p>
</template>

<script>
import ButtonComponent from '@/components/ButtonComponent.vue'
import TextFormComponent from '@/components/TextFormComponent.vue'

export default {
  name: 'App',
  components: {
    ButtonComponent,
    TextFormComponent
  },
  data() {
    return {
      showMsg: false
    }
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
