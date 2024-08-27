<script setup lang="ts">
import { ref } from 'vue';
import Comp from 'Comp.vue';

const msg = ref('Hello World!');
</script>

<template>
  <h1 v-foo>{{ msg }}</h1>
  <input v-model="msg" />
  <Comp></Comp>
</template>
