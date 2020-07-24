<template>
  <div>
    <nav class="navbar navbar-expand-lg" >
      <div class="container">
        <a class="navbar-brand">Medium</a>
        <a class="navbar-brand" style="opacity: 0.5;">|</a>
        <a class="navbar-brand">Software Engineering</a>

        <div class="collapse navbar-collapse justify-content-end mr-auto">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="/profile">Profile</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/detail">Detail</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <br>
    <nuxt/>
  </div>
</template>

<style>
    .navbar{
        box-shadow: 0 0 4px 0 rgba(0, 0, 0, 0.1);
    }

    .nav-link{
      color: #000000;
    }
</style>