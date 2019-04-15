<template>
  <div id="main-wrap">
    <section class="pb-10 mt-5" style="text-align:center;">
      <h1>Game of Thrones - Death Log</h1>
      <p>A list of everyone noteable who's died in season 8</p>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Beric Dondarrion"
        :char-img="require('~/assets/img/beric-dondarrion-ign.jpg')"
        char-desc="Beric appeared in a blink-and-you-missed-him moment back in Season 1 (played by a different actor initially) but then later rebounded in a big way in Season 3 as the oft-resurrected leader of a group of neutral Riverlands resistance fighters called the Brotherhood Without Banners. Beric’s band of warriors gave Arya a place to hide for a bit while also introducing us to the Lord of Light’s ability to breathe life back into the dead. Basically, Melisandre gave the whole “bring someone back from beyond” spell a whirl on Jon because of Beric’s success rate when it came to cheating death."
      ></death>
    </section>
  </div>
</template>

<script>
import Death from '../components/Death.vue'
export default {
  components: {
    Death
  }
}
</script>


<style lang="scss">
#main-wrap {
  max-width: 800px;
  margin: 0 auto;
  padding: 45px 45px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
</style>
