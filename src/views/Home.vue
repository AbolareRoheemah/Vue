<template>
  <div class="home">
    <nav class="navbar navbar-light navbar-expand-sm bg-success">
      <div class="container">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <a href="#" class="navbar-brand mr-auto">Brand</a>
        <div id="Navbar">
        <ul class="navbar-nav">
          <li class="nav-item text-white"><router-link to="/" class="nav-link">Home</router-link></li> 
          <li class="nav-item"><router-link to="/about" class="nav-link">About</router-link></li> 
          <li class="nav-item"><router-link to="/samplePage" class="nav-link">Sample</router-link></li>
        </ul>
        </div>
      </div>
    </nav>
      <div class="container">
        <div class="card">
          <div class="card-header text-danger"><h3>Yay It's My First Vue App!</h3></div>
          <div class="card-body text-success">
            <img alt="Vue logo" src="@/assets/logo.png">
            <h4>So I learnt Vue js and in less than a week since i started learning,<br><strong>I was able to build this site</strong> </h4>
            <h1><span class="badge badge-danger rounded-pill badge-lg">HOT</span></h1>
          </div>
        </div>
        <router-link to="/samplePage"><button class= "btn-success p-3 mt-5 rounded-pill">Click here to see the next page</button></router-link>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
}
</script>

<style scoped>
button {
  padding: 20px;
  background-color: rgb(16, 16, 59);
  color: white;
}
</style>