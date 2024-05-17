<script setup lang="ts">
import { SpeedInsights } from "@vercel/speed-insights/vue";
</script>

<template>
  <SpeedInsights />
  <div class="layouts-default">
    <p>レイアウト：default</p>
    <slot />
  </div>
</template>
