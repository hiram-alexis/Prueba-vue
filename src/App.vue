<template>
  <div id="app">
  <nav class ="navbar navbar-dark bg.primary">
  <a href="/" class="navbar-brand">Vuejs Firebase Database</a> 
  </nav>
  <!-- Main content-->
  <div class="container">
    <div class="row mt-5">
    <div class="col-sm-4">
      <div class="card">
      <div class="card-header">
      <h3>Add a new Webside</h3>
        </div>
        <div class="card-body">
        <form>

        </form>

        </div>
        </div>
        </div>
        <div class="col-sm-8 text-center">
    <img src="./assets/logo.png">
      <div class="card">
        <div class="card-header">
        <h3>Websites List</h3>
        </div>
        <div class="card-body">
        <table class="table  table-striped table-bordered">
        
        <thead>
        <tr>
        <th>Name</th>
        <th>Author</th>
        <th>Operations</th>
        </tr>
        </thead>
        
        <tbody>

        </tbody>

        </div>
         </div>
        </div>
      </div>
  </div>
</template>

<script>


export default {
  name: 'App' 
}
</script>

<style>
#app {
  
}
</style>
