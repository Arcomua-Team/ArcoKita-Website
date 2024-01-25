<template>
  <div class="home-container">
    <v-parallax class="first-block" :height="600"
      src="https://i0.hdslb.com/bfs/new_dyn/ab88fd50796d5f715a1e09053e122b38291344932.jpg@2560w.webp">
      <div class="d-flex flex-column fill-height justify-center align-center text-white float-in-up">
        <div class="home-logo d-flex flex-column">
          <img width="200" height="200" class="home-logo-image" src="@/assets/logo.svg" />
          <img width="200" class="home-logo-text" src="@/assets/fontlogo-white.webp" />
          <h1 style="display: none">Arcomua Team</h1>
        </div>
        <div class="d-flex flex-column justify-center align-center py-8 text-shadow">
          <h4 class="subheading">Minecraft整合包制作小组</h4>
        </div>
      </div>
    </v-parallax>

    <div class="second-block d-flex flex-shrink-0 flex-column flex-wrap justify-center align-center pa-8">
      <div class="second-block-line d-flex flex-shrink-0 flex-wrap justify-center align-center">
        <HomeFeature icon="mdi-memory" title="性能">高强度的优化<br>让游戏体验更佳</HomeFeature>
        <HomeFeature icon="mdi-pinwheel" title="前沿">使用更新的技术<br>为玩家提供稳定的游戏环境</HomeFeature>
        <HomeFeature icon="mdi-cog" title="热忱">由热爱驱动<br>勤奋的更新与修复</HomeFeature>
      </div>
      <div class="second-block-line d-flex flex-shrink-0 flex-wrap justify-center align-center">
        <HomeFeature icon="mdi-hand-heart" title="质量上乘">致力制作高质量整合包<br>丰富玩家的游戏体验</HomeFeature>
        <HomeFeature icon="mdi-thumb-up" title="回馈社区">使用宽松的创作协议<br>供玩家自由修改</HomeFeature>
      </div>
    </div>

    <v-parallax class="third-block" :height="300"
      src="https://i0.hdslb.com/bfs/new_dyn/146385c27d1d04cdb6b2d8843ae667a1291344932.png@2560w.webp">
      <div class="d-flex flex-column fill-height justify-center align-center text-white">
        <h2 class="subheading">Where All Miracles Begin.</h2>
      </div>
    </v-parallax>
  </div>
</template>

<script setup>
import HomeFeature from "@/components/HomeFeature.vue"
</script>

<script>
export default {
  data: () => ({
    snackbar: false,
  }),
}
</script>

<style lang="scss" scoped>
.first-block {
  &.v-parallax--active>.v-img__img {
    filter: brightness(0.8) blur(2px);
  }

  p,
  h4 {
    user-select: text;
  }
}

.second-block,
.second-block-line {
  max-width: 100%;
  gap: 2em;
}

.third-block {
  &.v-parallax--active>.v-img__img {
    filter: blur(32px);
  }

  h2 {
    user-select: text;
  }
}

.home-logo {
  gap: 8px;
  filter: drop-shadow(0 6px 8px rgba(0, 0, 0, 0.3));
}

.home-logo-image {
  filter: brightness(100);
}

.text-shadow {
  text-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
}
</style>
