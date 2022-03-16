<template>
<div>
  <div class=article-header>
    <h1 class="article-header-title">Home</h1>
  </div>
  <div class="article-body">
    <div class="article-body">
      <div class="article">
        <img class="article-image" src="/images/denver-broncos-logo-transparent.png">
          <h2 class="article-title">Current News!</h2>
          <p class="article-text">A true fan stays updated with the current news! Please 
            <a href="https://www.denverbroncos.com/news/">click here</a> 
                  for the most recent news!
          </p>
      </div>
      <div class="article">
        <img class="article-image" src="/images/denver-broncos-logo-transparent.png">
        <h2 class="article-title">Next Game!</h2>
        <p class="article-text">A true fan stays updated with the gmaes! Please 
          <a href="https://www.denverbroncos.com/schedule/">click here</a> 
                to see the schedule!
        </p>
      </div>
    </div>
  </div>
  <a class="footer" href="https://github.com/BroncoMark/markpedersen.click/tree/main/broncos-vue">GitHub</a>
</div>
</template>

<script>

export default {
  name: 'HomeView',
}
</script>


<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

.whole-body {
    max-width: 1920px;
    background-color: lightgray;
}

.header {
    overflow: hidden;
    min-height: 300px;
    background-repeat: no-repeat;
    background-position:center;
    width: 100%;
    position: relative;
}

.git-button {
    max-width: 75px;
    position: absolute;
    right: 0;
    bottom: 0;
    border: 3px solid rgb(0, 34, 68)
}

.git-button img {
    max-width: 100%;
    width: auto;
    background-color: rgb(251, 79, 20);
}

.navbar-bronco {
    margin: 0px 0px 0px;
    height: 75px;
    padding: 0 40px;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1003;
    display: flex;
    transition: all 0.5s ease;
    background: linear-gradient(0deg, rgba(0,0,0,0.02) 0%, rgba(0,0,0,0.6) 45%, #000 100%);
}

.logo-image {
    max-width: 75px;
    max-height: 200px;
}

.nav-link {
    font-size: x-large;
}

.article-header {
    padding: 1em;
    display: flex;
    justify-content: center;
    background-color: rgb(231, 231, 231);
}

.article-body {
    display: flex;
    justify-content: center;
    padding: 1em;
    flex-wrap: wrap;
}

.article {
    border: 2px solid rgb(0, 34, 68);
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 1em;
    background-color: white;
    max-width: 100%;
}

.article-text {
    margin: 1em;
}

.article-image {
    max-width: 300px;
}

.roster {
    max-width: 100%;
}

h2 {
    margin: 1em;
}

.footer {
    position: fixed;
    text-align: center;
    font-size: x-large;
    width: 100%;
    height: 5%;
    bottom: 0;
    background-color: rgb(231, 231, 231);
    margin-right: 1em;
}

/* Mobile Styles */
@media only screen and (max-width: 591px) {
    .header {
        /* background-image: url(/images/header-image.jpeg); */
        background-size: cover;
        min-height: unset;
        padding-bottom: 50%;
    }
    
    .git-button {
        max-width: 13%;
    }
  }
  
  /* Desktop Styles */
@media only screen and (min-width: 592px) {
    .header {
        /* background-image: url(/images/header-image-large.jpeg); */
        background-size: cover;
    }
  }
</style>