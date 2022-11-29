<template>
  <v-footer light padless>
    <v-col cols="6" class="header">
      <h1 class="gray--text bot">
        Ready to make something <br />
        amazing ?
      </h1>

      <div class="footer__contact">
        <a style="text-decoration: none" href="tel:0332386722" class="bot">
          <v-icon medium color="black"> fas fa-phone-alt</v-icon>
          <p class="grey--text">0332386722</p>
        </a>
        <a style="text-decoration: none" href="mailto:phuongnk0912@gmail.com">
          <v-icon medium color="black"> fas fa-envelope</v-icon>
          <p class="grey--text">phuongnk0912@gmail.com</p>
        </a>
      </div>
      <v-row align="center" justify="space-around">
        <a
          href="https://www.facebook.com/khacphuong2503"
          target="_blank
              "
          style="text-decoration: none"
        >
          <v-icon medium color="black">fab fa-facebook</v-icon></a
        >

        <a
          href="https://github.com/khacphuong2503"
          target="_blank
              "
          style="text-decoration: none"
          ><v-icon medium color="black">fab fa-github</v-icon></a
        >
        <a
          href="https://www.linkedin.com/in/ph%C6%B0%C6%A1ng-nguy%E1%BB%85n-kh%E1%BA%AFc-968885253/"
          target="_blank
              "
          style="text-decoration: none"
          ><v-icon medium color="black">fab fa-linkedin-in</v-icon></a
        >
      </v-row>
    </v-col>
    <v-col cols="6">
      <v-img src="../assets/footer-img.png" contain max-height="900"> </v-img>
    </v-col>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
.second {
  width: 100%;
  height: 400px;
  /* background: #d6d5d5; */
  text-align: center;
  /* padding: 2rem 2rem; */
}
.secondchild1 {
  display: flex;
  flex-direction: row;
  /* background-color: #d6d5d5; */
  padding: 2rem 6rem;
  /* vertical-align: middle; */
  text-align: left;
  margin-top: 250px;
}
.header {
  padding-left: 60px;
}

.footer__contact {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
#contact {
  display: flex;
  flex-direction: row;
}
.top {
  margin-top: 180px;
}
.bot {
  margin-bottom: 30px;
}
.trans {
  position: absolute;
  top: 0;
  right: 0;
  transform: translateX(25%);
  z-index: -1;
}
</style>
