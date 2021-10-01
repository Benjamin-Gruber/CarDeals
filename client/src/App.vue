<template>
  <v-app>
    <LogoBar />   
  </v-app>
</template>

<script>
import LogoBar from '@/components/LogoBar.vue';

export default {
  name: 'App',
  data: () => ({}),

  components: {
    LogoBar,
  },
};
</script>
