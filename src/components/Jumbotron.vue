<template>
  <div class="jumbotron">

    <div class="row">

      <div class="left">
        <h3>Vuoi diventare un supereroe della programmazione web?</h3>
      </div>
      <div class="right">
        <h1>Scegli </h1>
        <a class="img-logo" href="http://www.boolean.careers" target="_blank">
          <img src="https://hiringplatform.boolean.careers/images/logo.png" alt="">
        </a>
      </div>
    </div>
  </div>           
</template>

<script>
export default {
  name: 'Jumbotron',
  props: {
    msg: String,
    src: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1 {
  font-size: 4rem;
}

h3 {
  margin: 40px 0 0;
  font-size: 2rem;
}

a {
  color: #42b983;
}

.jumbotron {

  background-image: url(http://marvelheroes.altervista.org/wp-content/uploads/2018/05/585f9357cb11b227491c3582.png);
  background-size: cover;
  background-repeat: no-repeat;
  width: 100%;
  min-height: 500px;
  padding: 50px 0;
  border: 5px ridge #41b883;
  overflow-x: none;
}

.row {
  padding: 50px;
  color: white;
  text-shadow: 2px 1px 2px #333;
}

.left {
  float: left;
  height: 100%;
  width: 30%;
  color: white;
}

.right {
  float: right;
  width : 70%;
  height: 100%;
}

.img-logo img {
  width: 100%;
  background: rgba(255,255,255, 0.5);
}

</style>
