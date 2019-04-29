<template>
  <div class="max-w-sm rounded overflow-hidden shadow-lg mt-8">
    <img class="w-full" :src="charImg" alt="Sunset in the mountains" />
    <div class="px-6 py-4">
      <div class="font-bold text-xl mb-2">{{ charName }}</div>
      <p class="text-grey-darker text-base">
        <slot name="description"> </slot>
      </p>
    </div>
    <div class="px-6 py-4">
      <slot name="badges"></slot>
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
    charImg: {
      required: true,
      type: String
    }
  }
}
</script>
