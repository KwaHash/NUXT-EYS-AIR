<template>
  <div class="flex items-center">
    <NuxtImg :src="img" loading="lazy" class="w-[3.5vw] md:w-[17.5px] h-[3vw] md:h-[15px]" alt="icon" />
    <span class="text-[2.4vw] md:text-[12px] ml-[1vw] md:ml-[5px] tracking-tighter">{{ text }}</span>
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