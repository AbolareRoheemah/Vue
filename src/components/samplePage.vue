<template>
  <div class="hello">
    <nav class="navbar navbar-light navbar-expand-sm bg-success">
      <div class="container">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <router-link to="/"><a class="navbar-brand mr-auto">Brand</a></router-link>
        <div id="Navbar">
        <ul class="navbar-nav">
          <li class="nav-item text-white"><router-link to="/" class="nav-link">Home</router-link></li> 
          <li class="nav-item"><router-link to="/about" class="nav-link">About</router-link></li> 
          <li class="nav-item"><router-link to="/samplePage" class="nav-link">Sample</router-link></li>
        </ul>
        </div>
      </div>
    </nav>
    <div class="card">
          <div class="card-header text-danger"><h3>Yay This is a sample page using Vue!</h3></div>
          <div class="card-body text-success">
            <img alt="Vue logo" src="@/assets/logo.png">
            <h4>So I learnt Vue js and in less than a week since i started learning,<br><strong>I was able to build this site</strong> </h4>
          </div>
    </div>
    <h1><span class="badge badge-danger rounded-pill badge-lg mt-4">HOT</span></h1>
    <router-link to="/about"><button class= "btn-success p-3 mt-5 rounded-pill">Click here to see the about page</button></router-link>
  </div>
</template>

<script>
export default {
  name: 'samplePage',
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->