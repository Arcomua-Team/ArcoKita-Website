<template>
  <div class="home-container">
    <v-parallax class="first-block" :height="600" src="https://i0.hdslb.com/bfs/new_dyn/360b70d7960e2ff8ce317451c83f8b7e291344932.png@2560w.webp">
      <div class="d-flex flex-column fill-height justify-center align-center text-white float-in-up">
        <div class="home-logo d-flex flex-column">
          <img width="200" height="200" class="home-logo-image" src="@/assets/standard_logo.png" />
        </div>
        <div class="d-flex flex-column justify-center align-center py-8 text-shadow">
          <h2 class="subheading">Arcomua Modpack - 艺术美化</h2>
        </div>
      </div>
    </v-parallax>
    <v-container>        
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
    </v-container>
  </div>
</template>
  
<style lang="scss">
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
  