<template>
  <div id="main-wrap">
    <section class="pb-10 mt-5" style="text-align:center;">
      <h1>Game of Thrones - Death Log</h1>
      <p>A list of everyone noteable who's died in season 8</p>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Ned Umber (Umber Boy)"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1555895946/ned-umber.jpg"
      >
        <template v-slot:description>
          <p class="pb-2">
            Ned Umber was the 10-year-old Lord of the Last Hearth. Ned was
            likely named for Lord Eddard Stark by his father, Jon Umber, known
            as “Littlejon,” in contrast to his own father, “Greatjon” Umber.
          </p>
          <p>
            In the aftermath of the Battle of the Bastards, many Northern lords
            and Knights of the Vale wanted to see Ned Umber stripped of his land
            and titles, but in the Season 7 premiere, Jon Snow refuses. Ned
            Umber and another child of traitors, Alys Karstark, declare their
            undying allegiance to House Stark.
          </p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >1st Minor Death</span
          >
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 1</span
          >
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Not in Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Eddison Tollett (Ed)"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556508470/eddison-tollett.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Not in Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Lyanna Mormont"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556508095/lyanna-mormont.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Not in Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Baric Dondarrion"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1555895946/beric-dondarrion-ign.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >1st Death Pool Death</span
          >
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >In Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Theon Greyjoy"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556508722/theon-greyjoy.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >In Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Jorah Mormont"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556508309/jorah-mormont.png"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >In Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="The Night King"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556535664/night-king.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >In Death Pool</span
          >
        </template>
      </death>
    </section>
    <section id="deaths" class="">
      <death
        char-name="Melisandre"
        char-img="https://res.cloudinary.com/bradkriss/image/upload/f_auto,q_auto/v1556557157/melisandre.jpg"
      >
        <template v-slot:description>
          <p class="pb-2"></p>
        </template>
        <template v-slot:badges>
          <span
            class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >Episode 3</span
          >
          <span
            class="inline-block bg-red-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2"
            >In Death Pool</span
          >
        </template>
      </death>
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
