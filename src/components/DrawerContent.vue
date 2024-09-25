<template>
  <v-list>
    <v-list-item prepend-icon="mdi-home" title="首页" to="/" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-palette" title="颜色" to="color" active-color="primary"></v-list-item>
  </v-list>
<v-divider />
  <v-list>
    <v-list-subheader>Minecraft 整合包</v-list-subheader>
    <v-list-item prepend-icon="mdi-star-circle" title="Standard" to="standard" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-anvil" title="Anvil" to="anvil" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-lightning-bolt" title="Lite" to="lite" active-color="primary"></v-list-item>
  </v-list>
  <v-divider />
  <v-list>
    <v-list-subheader>帮助</v-list-subheader>
    <v-list-item prepend-icon="mdi-note-multiple" title="帮助中心" href="https://support.arcomua.com/"></v-list-item>
  </v-list>
</template>
