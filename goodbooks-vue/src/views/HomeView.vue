<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/gblogo.png">
    <HelloWorld msg="Welcome to GoodBooks"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
})
export default class HomeView extends Vue {}
</script>
