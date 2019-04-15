<template>
  <div class="max-w-sm rounded overflow-hidden shadow-lg">
    <img class="w-full" :src="charImg" alt="Sunset in the mountains" />
    <div class="px-6 py-4">
      <div class="font-bold text-xl mb-2">{{ charName }}</div>
      <p class="text-grey-darker text-base">
        {{ charDesc }}
      </p>
    </div>
    <div class="px-6 py-4">
      <span class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2">#1 - Episode 2</span>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    charName: {
      required: true,
      type: String
    },
    charDesc: {
      required: true,
      type: String
    },
    charImg: {
      required: true,
      type: String
    }
  }
}
</script>

