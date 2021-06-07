<template>
  <div>
    <div>
      <Intro/>
    </div>
    <SectionTwo/>
    <SectionThree/>
    <SectionFour/>
    <ScrollToTop/>
    <PopUp/>
  </div>
</template>

<script>
import IntroSection from "~/components/Organisms/IntroSection.vue"
import SectionTwo from "~/components/Organisms/SectionTwo.vue"
import SectionThree from "~/components/Organisms/SectionThree.vue"
import SectionFour from "~/components/Organisms/SectionFour.vue"
import ButtonScrollToTop from "~/components/Atoms/ButtonScrollToTop.vue"
import PopUp from "~/components/Atoms/PopUp.vue"
export default {
  components: {
    Intro: IntroSection,
    SectionTwo: SectionTwo,
    SectionThree: SectionThree,
    SectionFour: SectionFour,
    ScrollToTop: ButtonScrollToTop,
    PopUp: PopUp,
  },
}
</script>

<style>

</style>