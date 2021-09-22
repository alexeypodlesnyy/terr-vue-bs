<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Terrariums Glassroots</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse  justify-content-center" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <router-link to="/" class="nav-link active" aria-current="page">Home</router-link>
            <router-link to="/about" class="nav-link">About</router-link>
            <router-link to="/terrariums" class="nav-link">Terrariums</router-link>
          </div>
        </div>
      </div>
    </nav>
    <router-view/>
  </div>
</template>
