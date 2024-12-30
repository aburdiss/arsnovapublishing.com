<script setup lang="ts">
import WrapperStandard from '../../Components/WrapperStandard';
import BannerLarge from '../../Components/BannerLarge';
import SectionStandard from '../../Components/SectionStandard';
import CompositionLink from '../../Components/CompositionLink';
import PartnerWebsite from '../../Components/PartnerWebsite';
</script>

<template>
  <WrapperStandard>
    <BannerLarge>Ars Nova Publishing</BannerLarge>
    <SectionStandard>
      <p>
        At Ars Nova Publishing, we strive to publish new works of music that
        bring a unique perspective, and seek out new composers. A platform for
        daring, visionary artists to refine their craft, works published in the
        Ars Nova Publishing are raw, exciting, and fresh. Visit our
        <a href="#">submissions page</a> to learn more about submitting your
        work.
      </p>
    </SectionStandard>
    <SectionStandard>
      <h2>New Arrivals</h2>
      <div class="Composition-Link-List">
        <CompositionLink />
        <CompositionLink />
        <CompositionLink />
        <CompositionLink />
      </div>
    </SectionStandard>
    <SectionStandard>
      <PartnerWebsite>
        <template #title>Band Room Online</template>
      </PartnerWebsite>
      <PartnerWebsite>
        <template #title>Musescore Help</template>
      </PartnerWebsite>
    </SectionStandard>
  </WrapperStandard>
</template>

<style scoped>
.Composition-Link-List {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}
</style>
