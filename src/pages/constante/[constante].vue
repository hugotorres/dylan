<script setup lang="ts">
const props = defineProps<{ section: string }>()
const router = useRouter()
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

    <div>
      <button class="btn m-3 text-sm mt-8" @click="router.back()">
        Back
      </button>
    </div>
  </div>
</template>
