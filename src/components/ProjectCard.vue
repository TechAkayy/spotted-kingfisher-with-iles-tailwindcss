<script setup lang="ts">
  defineProps({
    projectName: {
      type: String,
      default: 'Project',
    },
    projectImage: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1473731308450-b3a5fc9f16d2?crop=entropy&cs=srgb&fm=jpg&ixid=M3wyMDkyMnwwfDF8c2VhcmNofDEwfHxzcG90dGVkJTIwa2luZ2Zpc2hlcnxlbnwwfHx8fDE2OTA0MjYwNDd8MA&ixlib=rb-4.0.3&q=85',
    },
  })
</script>
<template>
    <div class="p-1 text-primary-500 w-6/12 lg:w-4/12"><a href="#" class="block group hover:text-primary-600 relative text-primary-500"><img class="group-hover:opacity-90 w-full" width="300" height="300" :src="projectImage"/> <div class="absolute bg-black bg-opacity-90 bottom-0 inset-x-0 px-6 py-4 z-10">
                <p class="font-bold text-center">{{ projectName }}</p>
            </div> </a>
    </div>
</template>
<style scoped></style>
