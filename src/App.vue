<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        Класифікація військової техніки на зображеннях
      </div>
      <v-spacer></v-spacer>
    </v-app-bar>
    <v-main>
      <v-container>
        <v-row>
          <v-card>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>
                  Модель може розпізнавати наступні види військової техніки
                </v-list-item-title>
                <v-list-item-subtitle>
                  IMR-2, MiG-31, T-72, Tornado-G, Mi-8
                </v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
            <v-list-item>
              <v-list-item-content>
                <v-list-item-title>
                  Щоб класифікувати техніку на зображені, завантажте зображення, натисніть Відправити і очікуйте результат
                </v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-row>
        <v-row>
          <v-file-input label="Оберіть зображення"></v-file-input>
        </v-row>
        <v-row>
          <v-btn>Відправити</v-btn>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  components: {},

  data: () => ({
    //
  }),
};
</script>
