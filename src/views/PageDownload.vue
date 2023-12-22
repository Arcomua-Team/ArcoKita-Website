<template>
  <v-container>
    <div class="page-container">
      <div class="page-section-donation">
        <h1 class="text-primary float-in-right">下载</h1>
        <p class="subheading my-4 float-in-right">
          请在下方列表中查询对应的下载链接。
        </p>
      </div>
      <div class="page-section-donation">
        <h2 class="text-primary float-in-right">下载列表</h2>
        <div class="rounded mt-2 elevation-2 float-in-left">
          <v-table>
            <thead>
              <tr>
                <th class="text-left">
                  名字
                </th>
                <th class="text-left">
                  链接
                </th>
              </tr>
            </thead>
            <tbody>
              <tr v-for="item in modpacks" :key="item.name">
                <td>{{ item.name }}</td>
                <td>{{ item.link }}</td>
              </tr>
            </tbody>
          </v-table>
        </div>
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
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      modpacks: [
        {
          "name": "Arcomua Modpack",
          "link": "<link>"
        },
        {
          "name": "Arcomua Lite",
          "link": "<link>"
        },
        {
          "name": "Arcomua Anvil",
          "link": "<link>"
        }
      ]
    }
  }
}
</script>

<style lang="scss">
h1,
p,
th,
tr {
  user-select: text;
}

.page-section-donation {
  display: flex;
  flex-direction: column;
}

.donation-qrcode {
  margin-left: -16px;
}
</style>
