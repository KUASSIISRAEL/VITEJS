<script setup lang="ts">
import HeaderPart from './components/HeaderPart.vue';
import MissionCard from './components/MissionCard.vue';
import PartenerPart from './components/PartenerPart.vue';
</script>
<template>
  <div>
    <!-- Header Block -->
    <HeaderPart />
    <!-- Block of Cards -->
    <div class="container mx-auto lg:px-12 py-12">
      <div class="grid gap-4 lg:grid-cols-3 md:grid-cols-1">
        <MissionCard />
        <MissionCard />
        <MissionCard />
        <MissionCard />
        <MissionCard />
        <MissionCard />
      </div>
    </div>
    <!-- Parteners Block -->
    <PartenerPart />
  </div>
</template>
<style scoped>
</style>