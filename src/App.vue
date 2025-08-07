<template>
  <!-- <MeetGreet name="Bruce" hero-name="Batman"/>
  <MeetGreet name="Clark"  hero-name="Superman"/>
  <MeetGreet name="Diana"  hero-name="Wonder Woman"/>
  <MeetGreet :name="name"  :hero-name="channel"/> -->

  <MeetArtiicle id="my-article" title="Article Title" :likes= "500" :isPublished="true"/>
</template>

<script>
// import MeetGreet from './components/Greet.vue'
import MeetArtiicle from './components/Article.vue'

export default {
  name: 'App',
  components: {
    // MeetGreet,
    MeetArtiicle,
  },
  data() {
    return {
      name:'Dan',
      channel:"Code"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
