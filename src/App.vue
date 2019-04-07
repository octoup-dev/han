<template>
  <div id="app" class="p-5">
    <div class="container">
      <div class="row">
        <div class="col-sm">
          <ProfileCard username="韓國瑜" job="現任高雄市市長" />
        </div>
        <div class="col-sm">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ProfileCard from './components/ProfileCard.vue'

export default {
  name: 'app',
  components: {
    ProfileCard
  }
}
</script>

<style>
body {
  background-color: #f1f1f1;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
