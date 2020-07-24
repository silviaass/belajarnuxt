<template>
  <div>
    <div class="container">
      <div class="row">

      <!-- This is the article title -->

        <div class="col-8" style="margin: 0;">
          <img src="https://miro.medium.com/max/700/1*LnJwoZLOuEZ1v1eAN-UWZg.gif" style="height: 60%; width: 100%;margin-bottom:20px;">
          <div>
            <h1>Building a Text Editor for a Digital-First Newsroom</h1>
            <p style="opacity:0.7;">An inside look at the inner workings of a technology you may take for granted</p><br>
          </div>

          <!-- This is the author details -->

          <a href="https://medium.com/@sophiaciocca">
            <div style="display: flex; align-items: center;">
            <img src="https://miro.medium.com/fit/c/128/128/1*y8L8lmSpagtZ-aGZqhCIGA.jpeg" class="rounded-circle" width="40" height="40" style="margin-right: 10px;">
              <div>
                <p>Sophia Ciocca in NYT Open</p>
                <p style="margin:0;color:#00000;font-size:13px; opacity: 0.8">Apr 10 - 10 min read</p>
              </div>
            </div>
          </a>
        </div>

        <div class="latest">

        </div>

        <div class="col-3 offset-1">
          <p>Test ini isi</p>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'header'
}
</script>

<style>
p{
  margin: 0;
}

a {
  color: #000000;
}

a:hover {
    color: #000000;
    text-decoration: none;
}
</style>

