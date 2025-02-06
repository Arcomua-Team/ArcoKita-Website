<template>
  <div class="home-container">
    <v-parallax class="first-block" :height="600" src="https://i0.hdslb.com/bfs/new_dyn/360b70d7960e2ff8ce317451c83f8b7e291344932.png@2560w.webp">
      <div class="d-flex flex-column fill-height justify-center align-center text-white float-in-up">
        <div class="home-logo d-flex flex-column">
          <img width="200" height="200" class="home-logo-image" src="@/assets/standard_logo.png" />
        </div>
        <div class="d-flex flex-column justify-center align-center py-8 text-shadow">
          <h2 class="subheading">Arcomua Cloth</h2>
          <p>QQ群: 892836166</p>
          <p>版本: 1.21.1-1.13.2</p>
        </div>
      </div>
    </v-parallax>

    <v-container class="second-block">
      <div class="page-container">
        <div class="page-section-color">
          <h1 class="text-primary float-in-right">整合介绍</h1>
          <p class="subheading my-4 float-in-left">Arcomua Cloth是 Arcomua Modpack的Fabric/Quilt移植版，该整合包以优化游戏性能为主要目标，同时对原版进行美化和增加许多小工具的整合包，适合原版生存和服务器玩家。在丰富玩家体验的同时，也追求着更好的性能表现。</p>
          <h2 class="text-primary mt-8 float-in-right">内容概览</h2>
          <p class="subheading my-4 float-in-left">包含多项性能优化、错误修复；对部分游戏界面进行了美化；内置多种生电相关工具。</p>
        </div>
        <v-divider></v-divider>
        <div>
          <h2 class="text-primary float-in-right">下载链接</h2>
          <div class="float-in-left">
            <h3 class="mt-8 mb-2">推荐下载</h3>
            <v-btn color="green-lighten-1" hover href="https://modrinth.com/modpack/arcomua">Modrinth</v-btn>
            <!-- <h3 class="mt-6 mb-2">备用下载</h3>
            <div class="d-flex flex-wrap ga-3">
              <v-btn color="primary" hover href="https://www.123pan.com/s/CBgbVv-0SYoA.html">123网盘</v-btn>
              <v-btn color="primary" hover href="https://www.miaofile.com/s/Ayrib">MiaoFile</v-btn>
            </div> -->
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
