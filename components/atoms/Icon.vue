<template>
  <div class="flex items-center">
    <NuxtImg :src="img" loading="lazy" class="w-[3vw] md:w-[15px] h-[3vw] md:h-[15px]" alt="icon" />
    <span class="text-[2.4vw] md:text-[12px] ml-[1vw] md:ml-[5px] tracking-[-0.25vw] md:tracking-[-1.25px]">{{ text }}</span>
  </div>
</template>

<script>
export default {
  props: [
    'img',
    'text',
  ]
}
</script>

<style scoped></style>