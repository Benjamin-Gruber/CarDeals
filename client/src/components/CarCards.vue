<template>
  <v-container fluid class="d-flex flex-wrap" justify-center>
    <CarCard class="mx-3" :c="c" v-for="c of cars" :key="c" />
  </v-container>
</template>

<script>
import CarCard from '@/components/CarCard.vue';

export default {
  props: {
    cars: {
      type: Array,
    },
  },

  components: {
    CarCard,
  },
};
</script>

<style lang="scss" scoped></style>
