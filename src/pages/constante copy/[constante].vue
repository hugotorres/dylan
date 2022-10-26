<script setup lang="ts">
const props = defineProps<{ section: string }>()
</script>

<template>
  <div>
    <Header />
    <div i-carbon-chemistry text-4xl inline-block />
    <p>
      {{ props.section }}
    </p>
    <p text-sm op50>
      <em>Constante</em>
    </p>

    <div />
  </div>
</template>
