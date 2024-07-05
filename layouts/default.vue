<template>
  <div>
    <VApp>
      <VMain>
        <v-app-bar class="top-bar" density="compact" color="#7986CB">
          <template v-slot:prepend>
            <img src="/gak-logo.png" alt="" class="gak-logo" />
          </template>

          <v-app-bar-title>UEFA EURO 2024</v-app-bar-title>

          <template v-slot:append>
            <v-btn icon="mdi-help-circle-outline" size="large"></v-btn>
          </template>
        </v-app-bar>

        <slot />
      </VMain>
    </VApp>
  </div>
</template>

<style>
.gak-logo {
  max-height: 100%;
  height: calc(100% - 18px);
  margin-left: 6px;
}

#__nuxt > div > div > div > div > main {background: #a8c0ff;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #3f2b96, #a8c0ff);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #3f2b96, #a8c0ff); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
</style>
