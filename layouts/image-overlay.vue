<script setup lang="ts">
// Full-bleed image slide with a bottom-left title/text overlay.
// Usage in frontmatter:
//   layout: image-overlay
//   image: /dragon-fruit.jpg
//   image2: /dragon-flower.jpg   # optional second image (side-by-side)
const props = defineProps<{
  image: string
  image2?: string
}>()
</script>

<template>
  <div class="slidev-layout image-overlay">
    <div class="image-overlay__media" :class="{ 'is-split': props.image2 }">
      <div
        class="image-overlay__img"
        :style="{ backgroundImage: `url('${props.image}')` }"
      />
      <div
        v-if="props.image2"
        class="image-overlay__img"
        :style="{ backgroundImage: `url('${props.image2}')` }"
      />
    </div>
    <div class="image-overlay__scrim" />
    <div class="image-overlay__content">
      <slot />
    </div>
  </div>
</template>
