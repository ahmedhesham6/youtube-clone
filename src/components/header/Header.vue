<template>
  <div class="site-header">
      <Logo/>
      <Search/>
      <NavPanel/>
  </div>
</template>

<script>
import Logo from './Logo.vue';
import Search from './Search.vue';
import NavPanel from './NavPanel.vue';

export default {
  name: 'Header',
  components: {
    Logo,
    Search,
    NavPanel,
  },
};
</script>
