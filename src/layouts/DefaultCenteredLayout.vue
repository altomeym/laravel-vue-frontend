<template>
  <v-app>
    <AppHeader />
    <v-main>
      <v-container
        fill-height
        class="d-flex justify-center"
      >
        <slot />
      </v-container>
    </v-main>
    <AppFooter />
  </v-app>
</template>

<script setup lang="ts">
import AppHeader from '@/components/AppHeader.vue';
import AppFooter from '@/components/AppFooter.vue';

</script>
