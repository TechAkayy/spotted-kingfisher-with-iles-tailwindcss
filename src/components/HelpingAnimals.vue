<script setup lang="ts">
	// const props = defineProps({
	// 	name: {
	// 		type: String,
	// 		default: 'HelpingAnimals',
	// 	},
	// })
</script>
<template>
    <section class="bg-black bg-opacity-90 lg:text-left py-20 text-center">
        <div class="container mx-auto px-4">
            <div class="flex flex-wrap -mx-4 items-center">
                <div class="p-4 w-full lg:ml-auto lg:order-2 lg:w-6/12">
                    <div class="-mx-4 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1507476023592-4768ab885969?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDIyNnx8d2lsZGxpZmUlMjBuYXR1cmV8ZW58MHx8fHwxNjI0ODMxOTA1&amp;ixlib=rb-1.2.1q=85&amp;fm=jpg&amp;crop=faces&amp;cs=srgb&amp;w=200&amp;h=300&amp;fit=crop" class="px-3 w-5/12" width="170"/>
                        <img src="https://images.unsplash.com/photo-1516934024742-b461fba47600?ixid=MnwyMDkyMnwwfDF8c2VhcmNofDE2fHx3aWxkbGlmZSUyMG5hdHVyZXxlbnwwfHx8fDE2MjQ4Mjg0NjM&amp;ixlib=rb-1.2.1q=85&amp;fm=jpg&amp;crop=faces&amp;cs=srgb&amp;w=200&amp;h=300&amp;fit=crop" class="px-3 w-6/12" width="200"/>
                    </div>
                </div>
                <div class="p-4 w-full lg:order-1 lg:w-5/12">
                    <h2 class="font-bold mb-2 text-5xl text-primary-600 lg:text-6xl">
                Helping Animals </h2>
                    <h3 class="font-light mb-6 text-3xl text-white">
                Bringing forest restoration to life </h3>
                    <p class="mb-6 text-neutral-100">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam
                vitae congue tortor. Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Curabitur ac sagittis neque, vel egestas est. </p>
                    <BaseButton size="xl" class="!rounded-full" to="/explore">
                        <span class="font-serif px-6 py-1 text-neutral-400 tracking-wide">Become a Volunteer</span>
                    </BaseButton>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped></style>
