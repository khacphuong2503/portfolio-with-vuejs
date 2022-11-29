<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.light.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6" class="header">
          <h1 class="gray--text text--darken-4 top">Hello, I'm Phuong</h1>
          <p class="grey--text">
            I am a 4rd year student of Japan-oriented Information Technology
            program. With the professional knowledge I have learned,I hope to
            find a suitable job so that I can promote my abilities well.
            <br />
            My orientation is interface design for web applications.
          </p>
          <v-btn
            tile
            color="gray"
            light
            class="pa-4 secondary text-no-wrap rounded-pill"
          >
            view more
          </v-btn>
          <br />
          <br />
          <br />
          <v-row align="center" justify="space-around">
            <a
              href="https://www.facebook.com/khacphuong2503"
              target="_blank
              "
              style="text-decoration: none"
            >
              <v-icon large color="black">fab fa-facebook</v-icon></a
            >

            <a
              href="https://github.com/khacphuong2503"
              target="_blank
              "
              style="text-decoration: none"
              ><v-icon large color="black">fab fa-github</v-icon></a
            >
            <a
              href="https://www.linkedin.com/in/ph%C6%B0%C6%A1ng-nguy%E1%BB%85n-kh%E1%BA%AFc-968885253/"
              target="_blank
              "
              style="text-decoration: none"
              ><v-icon large color="black">fab fa-linkedin-in</v-icon></a
            >
          </v-row>
        </v-col>
        <v-col cols="6">
          <v-img
            src="../assets/banner-img.png"
            contain
            max-height="1100"
          ></v-img>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
          <h4 class="gray--text">Recent Works</h4>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#3f3d56" dark> View All </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="../assets/IBook.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="../assets/DS-102.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="gray" light text class="ml-n4"> IBOOK </v-btn><br />

          <v-btn color="#A7121D" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="gray" light text class="ml-n4"> DS102 </v-btn><br />

          <v-btn color="#A7121D" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img src="../assets/img-porti.png" contain max-height=""></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="250px"
            color="#1E1E1E"
          >
            <v-img
              src="../assets/game-python.jpg"
              contain
              max-height=""
            ></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="gray" light text class="ml-n4"> PORTFOLIO </v-btn><br />

          <v-btn color="#A7121D" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="gray" light text class="ml-n4"> Pygame </v-btn><br />
          <v-btn color="#A7121D" dark text class="ml-n4">
            know more
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
    <Foo_ter />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Foo_ter from "../components/Foo_ter.vue";

export default {
  name: "Home_view",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Foo_ter,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.header {
  padding-left: 60px;
}

.footer__contact {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>
