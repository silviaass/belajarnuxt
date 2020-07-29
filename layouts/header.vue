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
              <a class="nav-link" href="./">Become a member</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./">Sign in</a>
            </li>
            <li class="nav-item">
              <div class="btn btn-green">Get started</div>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <br><br>
    <nuxt/>
  </div>
</template>

<style>
    .navbar{
        box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.1);
        padding-left: 0;
        padding-right: 0;
    }

    .nav-link{
      color: #000000;
    }
    
    .nav-item{
      font-size: 14px;
    }

    .btn-green{
      border: 1px solid green; 
      font-size: 14px; 
      color: green;
      margin: 2px 5px;
    }
</style>