<template>
  <v-footer color="primary" id="white-pantyhose-footer">
    <div class="white-pantyhose-footer-left">
      <v-img :width="200" src="@/assets/fontlogo-white.webp"></v-img>
      <p class="white-pantyhose-footer-year">CC-BY-NC-SA-4.0 2020 - {{ new Date().getFullYear() }}</p>
      <div class="white-pantyhose-footer-left-links">
        <v-btn variant="plain" size="small" target="_blank" href="https://github.com/Arcomua-Team/">Github</v-btn>
        <v-btn variant="plain" size="small" target="_blank" href="https://github.com/Arcomua-Team/ArcoKita-Website">Source</v-btn>
      </div>
    </div>
    <div class="white-pantyhose-footer-right">
      <h3>友情链接</h3>
      <div class="white-pantyhose-footer-right-links">
        <!-- <v-btn variant="plain" size="small" target="_blank" href="https://heryin.net/">和瑛</v-btn> -->
        <v-btn variant="plain" size="small" target="_blank" href="https://mc.calibur.tv/">Calibur Pixel</v-btn>
      </div>
    </div>
  </v-footer>
</template>

<style lang="scss">
#white-pantyhose-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 32px 5vw;
}

.white-pantyhose-footer-left {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
}

.white-pantyhose-footer-year {
  font-size: 14px;
}

.white-pantyhose-footer-left-links {
  margin-left: -12px;
  margin-top: 20px;
  margin-bottom: -10px;
  display: flex;
  align-items: flex-start;
}

.white-pantyhose-footer-right {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 13px;
}

.white-pantyhose-footer-right-links {
  margin-right: -12px;
  margin-bottom: -10px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

@media screen and (max-width: 600px) {
  #white-pantyhose-footer {
    align-items: flex-end;
  }

  .white-pantyhose-footer-left-links {
    flex-direction: column;
  }

  .white-pantyhose-footer-right {
    gap: 34px;
  }
}
</style>
