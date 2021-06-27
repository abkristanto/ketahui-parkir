<template>
    <div class="w-full h-96 bg-yellow-300">
        <div class="text-white text-left ml-8 mt-5">
            <div class="font-bold text-2xl">
            {{ title }}
            </div>
            <div class="text-md font-light mr-32">
            {{ description }}
            </div>
            <button class="absolute text-sm px-7 py-3 mt-5 rounded-md font-semibold tracking-wide bg-white text-blue-700">
                Mulai Belajar
            </button>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HomeCard',
  props: {
    title: {
      type: String,
    },
    description: {
      type: String,
    }
  }
}
</script>