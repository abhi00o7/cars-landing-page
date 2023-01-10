<template>
  <div class="Nav container mx-auto my-8">
    <div class="flex">
      <div class="mx-4">
        <img :src="Logo" alt="vue logo" class="w-16" />
      </div>
      <div class="mx-4">
        <a href="#">Home</a>
      </div>
      <div class="mx-4">
        <a href="#">About</a>
      </div>
      <div class="mx-4">
        <a href="#">Contact</a>
      </div>
    </div>
  </div>
</template>

<script setup>
import Logo from "../assets/logo/favicon.ico";
</script>
