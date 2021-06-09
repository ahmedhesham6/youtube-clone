<template>
  <div class="widget-video">
    <div class="widget-video__thumbnail">
      <img :src="thumbnail" alt="" />
    </div>
    <div class="widget-video__details">
      <div class="widget-video__author">
        <img :src="channel.img" alt="" />
      </div>
      <div class="widget-video__title">
        <h3>
          {{ title }}
        </h3>
        <a href=""></a>
        <span>{{ views }}</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WidgetVideo',
  props: ['title', 'views', 'thumbnail', 'channel'],
  data() {},
};
</script>
