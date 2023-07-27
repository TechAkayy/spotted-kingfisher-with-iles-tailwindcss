<script setup lang="ts">
	// const props = defineProps({
	// 	name: {
	// 		type: String,
	// 		default: 'HeroSection',
	// 	},
	// })
</script>
<template>
    <section class="-mt-24 bg-primary-900 poster relative text-white">
        <div class="container mx-auto px-4 py-36">
            <div class="-mx-4 flex flex-wrap">
                <div class="px-4 w-full lg:w-7/12 2xl:w-6/12">
                    <h1 class="font-light mb-4 text-6xl sm:text-7xl xl:text-8xl">
                Help the World&rsquo;s Most <span class="font-bold">Iconic Species</span> </h1>
                    <p class="mb-6 text-xl sm:pr-12">
                Conserve the world&apos;s most important forests to sustain
                nature&apos;s diversity, benefit our climate, and support human
                well-being. </p>
                    <BaseButton size="xl" class="!rounded-full" to="/explore">
                        <span class="font-serif px-6 py-1 text-neutral-400 tracking-wide">Explore</span>
                    </BaseButton>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>
