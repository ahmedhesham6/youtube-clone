<template>
  <div class="block-videos">
    <div class="block-videos__container">
      <div v-for="video in videos" :key="video.key">
        <WidgetVideo
          :channel="video.channel"
          :title="video.title"
          :thumbnail="video.thumbnail"
          :views="video.views"
        />
      </div>
    </div>
  </div>
</template>

<script>
import WidgetVideo from '../widgets/WidgetVideo.vue';
import videos from '../../data/videos';

export default {
  name: 'BlockVideos',
  components: {
    WidgetVideo,
  },
  data() {
    return {
      videos,
    };
  },
};
</script>
