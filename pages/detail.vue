<template>
  <div>
      <SectionOneDetail/>
      <SectionTwoDetail/>
      <SectionThreeDetail/>
      <SectionFourDetail/>
      <SectionFiveDetail/>
  </div>
</template>

<script>
import SectionOneDetail from '~/components/Organisms/SectionOneDetail.vue'
import SectionTwoDetail from '~/components/Organisms/SectionTwoDetail.vue'
import SectionThreeDetail from '~/components/Organisms/SectionThreeDetail.vue'
import SectionFourDetail from '~/components/Organisms/SectionFourDetail.vue'
import SectionFiveDetail from '~/components/Organisms/SectionFiveDetail.vue'
export default {
    components: {
        SectionOneDetail: SectionOneDetail,
        SectionTwoDetail: SectionTwoDetail,
        SectionThreeDetail: SectionThreeDetail,
        SectionFourDetail: SectionFourDetail,
        SectionFiveDetail: SectionFiveDetail,
    }
}
</script>

<style>

</style>