<template>
  <container>
    <row>
      <column col="12" sm="6" class="py-2">
        <view-wrapper src="https://mdbootstrap.com/img/Photos/Others/nature-sm.jpg" alt="view">
          <mdmask flex-center waves text="No pattern, no overlay, waves effect"></mdmask>
        </view-wrapper>
      </column>
      <column col="12" sm="6" class="py-2">
        <view-wrapper overlay="blue-light" src="https://mdbootstrap.com/img/Photos/Others/nature-sm.jpg" alt="view">
          <mdmask flex-center pattern="3" text="Pattern 3, light overlay, no waves"></mdmask>
        </view-wrapper>
      </column>
      <column col="12" sm="6">
        <view-wrapper overlay="blue-strong" src="https://mdbootstrap.com/img/Photos/Others/nature-sm.jpg" alt="view">
          <mdmask flex-center waves text="No pattern, strong overlay, waves effect"></mdmask>
        </view-wrapper>
      </column>
      <column col="12" sm="6">
        <view-wrapper src="https://mdbootstrap.com/img/Photos/Others/nature-sm.jpg" alt="view">
          <mdmask flex-center waves pattern="5" text="Pattern 5, no overlay, waves effect"></mdmask>
        </view-wrapper>
      </column>
    </row>
  </container>
</template>

<script>
import ViewWrapper from '@/components/ViewWrapper.vue';
import Mdmask from '@/components/Mdmask.vue';
import Container from '@/components/Container.vue';
import Row from '@/components/Row.vue';
import Column from '@/components/Col.vue';

export default {
  name: 'MasksPage',
  components: {
    ViewWrapper,
    Mdmask,
    Container,
    Row,
    Column
  }
};
</script>

<style scoped>
</style>
