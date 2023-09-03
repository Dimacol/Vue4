<template>
  <Header />
  <HomeMain />
  <BlogMain />
  <BlogDetailsMain />
  <Project />
  <Footer />
</template>

<script>

import Header from './components/Header.vue';
import HomeMain from './components/HomeMain.vue';
import BlogMain from './components/BlogMain.vue';
import BlogDetailsMain from './components/BlogDetailsMain.vue';
import Project from './components/Project.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    HomeMain,
    BlogMain,
    BlogDetailsMain,
    Project,
    Footer
  }
}
</script>

<style lang="scss">


* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: 'DM Serif Display', serif;
  font-family: 'Jost', sans-serif;
  background-color: #fff;
}

a {
  text-decoration: none;
}

img {
  max-width: 100%;
}

.center {
  padding-left: calc(50% - 600px);
  padding-right: calc(50% - 600px);
}
</style>
