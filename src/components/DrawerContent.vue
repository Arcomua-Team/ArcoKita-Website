<template>
  <v-list>
    <v-list-item prepend-icon="mdi-home" title="首页" to="/" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-palette" title="颜色" to="color" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-download" title="下载" to="download" active-color="primary"></v-list-item>
  </v-list>
<v-divider />
  <v-list>
    <v-list-subheader>整合包</v-list-subheader>
    <v-list-item prepend-icon="mdi-star-circle" title="标准版" to="standard" active-color="primary"></v-list-item>
    <v-list-item prepend-icon="mdi-lightning-bolt" title="Lite" to="lite" active-color="primary"></v-list-item>
  </v-list>
  <v-divider />
  <v-list>
    <v-list-subheader>帮助</v-list-subheader>
    <v-list-item prepend-icon="mdi-note-multiple" title="Notion"
      href="https://arcomua.notion.site/cd99af7b88b644c0a989ffe7f66d4f89?v=b38e3ce4a21a41a3974e5a94618f813f&pvs=4"></v-list-item>
    <v-list-item prepend-icon="mdi-file-word" title="腾讯文档" href="https://docs.qq.com/doc/DUEpVbVVsQUVsWmtH"></v-list-item>
  </v-list>
</template>
