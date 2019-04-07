<template>
  <div class="profile-card">
    <div class="card card-profile text-center">
      <div class="card-block">
        <img alt="" class="card-img-profile" src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/42/Han_Kuo-yu%28cropped%29.jpg/250px-Han_Kuo-yu%28cropped%29.jpg" width="160" height="160">

        <h4 class="card-title">
          {{ username }}
          <small>{{ job }}</small>
        </h4>

        <div class="card-links">
          <a class="fab fa-facebook-f" href="https://zh-tw.facebook.com/twherohan/" target="_blank"></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProfileCard',
  props: {
    username: String,
    job: String
  }
}
</script>

<style scoped>
.card-profile {
    width: 340px;
    margin: 50px auto;
    border-radius: 0;
    border: 0;
    box-shadow: 1em 1em 2em rgba(0, 0, 0, 0.2);
}
.card-profile .card-img-profile {
    max-width: 100%;
    border-radius: 50%;
    margin-top: -80px;
    margin-bottom: 35px;
    border: 5px solid #c7c7c7;
}
.card-profile .card-title {
    margin-bottom: 50px;
}
.card-profile .card-title small {
    display: block;
    font-size: .6em;
    margin-top: .2em;
}
.card-profile .card-links {
    margin-bottom: 25px;
}
.card-profile .card-links .fab {
    margin: 0 1em;
    font-size: 1.6em;
}
.card-profile .card-links .fab.fa-facebook-f {
    color: #3b5999;
}
.card-profile .card-links .fab.fa-facebook-f:hover {
    color: #2d4474;
}
.card-profile .card-links .fab:focus, .card-profile .card-links .fab:hover {
    text-decoration: none;
}
</style>
