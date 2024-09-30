<template>
  <div class="home-container">
    <v-parallax class="first-block" :height="600" src="https://i0.hdslb.com/bfs/new_dyn/d582eaba6ae303579fff1f0559f80985291344932.png@2560w.webp">
      <div class="d-flex flex-column fill-height justify-center align-center text-white float-in-up">
        <div class="home-logo d-flex flex-column">
          <img width="200" height="200" class="home-logo-image" src="@/assets/lite_logo.png" />
        </div>
        <div class="d-flex flex-column justify-center align-center py-8 text-shadow">
          <h2 class="subheading">Arcomua Lite</h2>
          <p>QQ群: 856952931</p>
          <p>版本: 1.20.4-1.20.1</p>
        </div>
      </div>
    </v-parallax>
    <v-container>
      <div class="page-container">
        <div class="page-section-color">
          <h1 class="text-primary float-in-right">整合介绍</h1>
          <p class="subheading my-4 float-in-left">Arcomua Lite是一个对原版进行高度性能优化的整合包，适合追求极致的原版生存和服务器玩家。在追求着更好的性能表现的同时，尽可能保持原版游戏性不变并带给玩家舒适的游戏体验。</p>
          <h2 class="text-primary mt-8 float-in-right">内容概览</h2>
          <p class="subheading my-4 float-in-left">包含多项性能优化、错误修复；内置多种生电相关工具。</p>
        </div>
        <v-divider></v-divider>
        <div>
          <h2 class="text-primary float-in-right">下载链接</h2>
          <div class="float-in-left">
            <h3 class="mt-8 mb-2">推荐下载</h3>
            <v-btn color="green-lighten-1" hover href="https://modrinth.com/modpack/arcomua-lite">Modrinth</v-btn>
            <h3 class="mt-6 mb-2">备用下载</h3>
            <div class="d-flex flex-wrap ga-3">
              <v-btn color="red-lighten-1" hover href="https://www.miaofile.com/s/Ayrib">MiaoFile</v-btn>
            </div>
          </div>
        </div>
      </div>
    </v-container>
  </div>
</template>

<style lang="scss" scoped>
h1,
h2,
p,
th {
  user-select: text;
}

.page-section-color {
  display: flex;
  flex-direction: column;
}

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

.text-shadow {
  text-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
}
  </style>
