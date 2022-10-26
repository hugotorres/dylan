<script setup lang="ts">
const name = $ref('')

const router = useRouter()
const go = () => {
  if (name)
    router.push(`/hi/${encodeURIComponent(name)}`)
}
</script>

<template>
  <div>
    <div i-carbon-campsite text-4xl inline-block />
    <div class="header">
      <h1>Factores que afectan la velocidad de Reaccion</h1>
    </div>
    <nav>
      <div>Equilibrio quimico</div>
      <div>Constante de equilibrio</div>
      <div>Calses de equilibrio</div>
    </nav>

    <div py-4 />

    <div>
      <button class="m-3 text-sm btn" :disabled="!name" @click="go">
        Go
      </button>
    </div>
  </div>
</template>
