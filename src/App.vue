<template>
  <div>
    <Hero />
    <Feature />
    <Content01 />
    <Content02 />
    <Presentation />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import "@/assets/styles/reset.css";
import "@/assets/styles/global.css";

import Hero from "./components/Hero.vue";
import Feature from "./components/Feature.vue";
import Content01 from "./components/Content01.vue";
import Content02 from "./components/Content02.vue";
import Presentation from "./components/Presentation.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Hero,
    Feature,
    Content01,
    Content02,
    Presentation,
    Contact,
    Footer,
  },
};
</script>


<style>
@font-face {
  font-family: "Karla";
  src: url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.eot");
  src: url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/750e3658d4460a397a551dfac26bb272.svg#Karla")
      format("svg");
}
/* @font-face {
  font-family: "Karla Bold";
  src: url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.eot");
  src: url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/b45be274b8b65fc9c72b038d72486edd.svg#Karla")
      format("svg");
} */

@font-face {
  font-family: "Lucida Grande";
  src: url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.eot");
  src: url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/0bbba3e6da511a469bc943bdf02310e7.svg#Lucida Grande")
      format("svg");
}
/* @font-face {
  font-family: "Lucida Grande";
  src: url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.eot");
  src: url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.eot?#iefix")
      format("embedded-opentype"),
    url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.woff2")
      format("woff2"),
    url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.woff")
      format("woff"),
    url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.ttf")
      format("truetype"),
    url("//db.onlinewebfonts.com/t/4dacabda65930685b68591f097311829.svg#Lucida Grande")
      format("svg");
} */
</style>



