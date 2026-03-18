<template>
	<AtomsCard class="flex w-full rounded-[4vw] md:rounded-[20px] relative h-full">
		<div class="w-full flex flex-col px-[4.8vw] md:px-[24px] py-[2.8vw] md:py-[14px]">
			<span
				class="font-apple text-[#ddd] font-light w-full text-[4.8vw] md:text-[24px] absolute top-[3.4vw] md:top-[17px] left-[8vw] md:left-[40px]">Kazuho
				Ishida</span>
			<p class="text-[4.2vw] md:text-[21px] mb-[2vw] md:mb-[10px] relative z-50 tracking-[0.6vw] md:tracking-[3px]">石田 一帆</p>
			<span class="text-smmini md:text-mini">ショップ店員 / 24歳 / </span>
		</div>
		<NuxtImg :src="img" loading="lazy" class="h-[24vw] md:h-[120px] w-[46.7vw] md:w-[276px]" alt="player" />
	</AtomsCard>
</template>

<script>
export default {
	props: [
		'img',
	]
}
</script>

<style scoped></style>