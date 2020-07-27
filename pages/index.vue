<template>
  <div>
    <div class="container">
      <div class="row" style="padding: 0;">

 
      <!-- This is the left column section -->

      <!-- This is the article title -->
        <div class="col-8" style="margin: 0;">
          <br>
          <img src="https://miro.medium.com/max/700/1*LnJwoZLOuEZ1v1eAN-UWZg.gif" style="height: 40%; width: 100%;margin-bottom:20px;">
          <div>
            <h1><b>Building a Text Editor for a Digital-First Newsroom</b></h1>
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
          </a><br><br>

        <!-- This is the latest section -->

        <div class="section-title">
          Latest
        </div>

        </div>

        <!-- This is the right column section -->

        <div class="col-4" style="padding-left: 75px;">
          <div class="topic-title"><b>Software Engineering</b></div>
          <div class="topic-desc">Back-end to front-end.</div><br>
          <div class="btn">Follow</div>
          <div class="topic-desc"><br>
            Follow to see more stories about Software Engineering on your homepage and in your Medium Daily Digest
          </div><br><br>
        
        <!-- This is the Related Topics section -->

          <div class="section-title">
            Related Topics
          </div><br>
          <a href="./"><div class="related-topics">Programming</div></a>
          <a href="./"><div class="related-topics">Javascript</div></a>
          <a href="./"><div class="related-topics">Cybersecurity</div></a>
          <a href="./"><div class="related-topics">Data Science</div></a>
          <a href="./"><div class="related-topics">Visual Design</div></a>
          <br><br>
        
        <!-- This is the Popular section -->

          <div class="section-title">
            Popular in Software Engineering
          </div>


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
    @media screen and (min-width: 1200px){
      .container {
          max-width: 1225px;
      }
    }

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

    .btn{
      border: 1px solid black;
      font-size: 13px;
    }

    .section-title{
      text-transform: uppercase;
      font-weight: 700;
      font-size: 13px;
      padding-bottom: 5px;
      border-bottom: 1px solid rgba(0, 0, 0, 0.2);
    }

    .topic-title{
      font-size: 25px;
    }

    .topic-desc{
      font-size: 14px;
    }

    .related-topics{
      text-transform: uppercase;
      font-size: 13px;
      margin-bottom: 5px;
    }
</style>

