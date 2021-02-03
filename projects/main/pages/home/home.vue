<template>
  <div class="home">
    <img alt="Vue logo" src="../../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloWorld from '@main/components/hello-world/hello-world.vue' // @main is an alias to /project/main

@Component({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>
