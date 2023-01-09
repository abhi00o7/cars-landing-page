<template>
  <div>
    <Navbar />
  </div>
  <div>
    <MainHeader />
  </div>
  <div>
    <Tabs />
  </div>
  <div>
    <Stats />
  </div>
  <div>
    <Presentation orientation="left" />
  </div>
  <div>
    <Presentation orientation="right" />
  </div>
  <div>
    <Footer />
  </div>
</template>

<script setup>
import {
  Tabs,
  Stats,
  Presentation,
  Footer,
  MainHeader,
  Navbar,
} from "../components";
</script>
