<script setup>
// Compositon API
import { useProductStore } from "@/stores/product";
import { useCounterStore } from "@/stores/counter";

const counter = useCounterStore();
const product = useProductStore();


</script>

<template>
  <main>
    <div class="about"></div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
