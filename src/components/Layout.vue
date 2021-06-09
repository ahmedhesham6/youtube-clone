<template>
  <Header />
  <div class="mainBody">
    <BlockVideos/>
  </div>
</template>

<script>
import Header from './header/Header.vue';
import BlockVideos from './blocks/BlockVideos.vue';

export default {
  name: 'Layout',
  components: {
    BlockVideos, Header,
  },
};
</script>
