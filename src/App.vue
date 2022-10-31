<script setup lang="ts">
import HeaderPart from './components/HeaderPart.vue'
import MissionCard from './components/MissionCard.vue'
import PartenerPart from './components/PartenerPart.vue'
</script>
<template>
  <div>
    <!-- Header Block -->
    <HeaderPart />
    <!-- Block of Cards -->
    <div class="container mx-auto lg:px-12 py-12">
      <div class="grid gap-4 lg:grid-cols-3 md:grid-cols-1">
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
        <MissionCard
          title="Linux & Windows"
          content="Lorem, ipsum, dolor sit amet consectetur adipisicing elit. Fugiat eaque ratione odio recusandae quaerat numquam."
        />
      </div>
    </div>
    <!-- Parteners Block -->
    <PartenerPart />
  </div>
</template>
<style scoped></style>
