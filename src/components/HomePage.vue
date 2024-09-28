<template>
  <v-container>
    <v-row class="body mx-auto d-flex flex-column">
      <v-col>
        <img class="img" src="/src/assets/image-qr-code.png" alt="" />
      </v-col>
      <v-col class="py-0 px-7">
        <div class="heading">
          Improve your front-end skills by building projects
        </div>
        <div class="text mt-3">
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/Outfit-Bold.ttf);
}
.body {
  width: 287px;
  height: 446px;
  background-color: #ffffff;
  border-radius: 20px;
}
.img {
  border-radius: 20px;
  width: 100%;
}
.heading {
  color: black;
  font-family: f1;
  font-size: 20px;
  text-align: center;
  line-height: 1.2;
}
.text {
  color: hsl(222, 4%, 45%);
  text-align: center;
  font-size: 13px;
}
</style>