<template>
  <v-app>
    <DefaultLayout>
      <router-view/>
      <!--router-view v-slot="{ Component }">
        <transition name="page">
          <component :is="Component" />
        </transition>
      </router-view-->
    </DefaultLayout>
  </v-app>
  <SpeedInsights />
</template>

<script setup>
import { SpeedInsights } from '@vercel/speed-insights/vue';
import DefaultLayout from "@/layouts/DefaultLayout.vue"
</script>

<!--style scoped lang="scss">
.page-enter-active {
  transition: all $ease-out-smooth 500ms;
}

.page-enter-from {
  opacity: 0;
  transform: translateX(10rem);
}
</style-->
