<template>
  <div class="about">
    <div class=article-header>
            <h1 class="article-header-title">About</h1>
        </div>
        <div class="article-body">
          <div class="article-body">
            <div class="article">
                <img class="article-image" src="/images/denver-broncos-logo-transparent.png">
                <h2>Learn about the Denver Broncos!</h2>
                <p class="article-text">The Denver Broncos are a professional American football franchise based in Denver. The Broncos compete in the National Football League (NFL) 
                    as a member club of the league's American Football Conference (AFC) West division. The team is headquartered in Dove Valley, Colorado and 
                    plays home games at Empower Field at Mile High in Denver, Colorado.
                </p>
                <p class="article-text">The team began play in 1960 as a charter member of the American Football League (AFL) and joined the NFL as part of the merger in 1970. 
                    The Broncos are not currently owned and currently play home games at Empower Field at Mile High (the stadium was formerly known as Invesco 
                    Field at Mile High from 2001 to 2010, Sports Authority Field at Mile High from 2011 to 2017, and Broncos Stadium at Mile High from 
                    2018 to 2019). Prior to that, the club played its home games at Mile High Stadium from 1960 to 2000.
                </p>
                <p class="article-text">The Broncos were barely competitive during their 10-year run in the AFL and their first seven years in the NFL. They did not have a winning 
                    season until 1973. In 1977, four years later, they qualified for the playoffs for the first time in franchise history and 
                    advanced to Super Bowl XII. Since 1975, the Broncos have become one of the NFL's most successful teams, having suffered only 
                    eleven losing seasons. They have won eight AFC Championships (1977, 1986, 1987, 1989, 1997, 1998, 2013, 2015), and three Super Bowl 
                    championships (1997 (XXXII), 1998 (XXXIII), 2015 (50)), and share the NFL record for most Super Bowl losses (5 — tied with the 
                    New England Patriots). The Broncos have eight primary members enshrined in the Pro Football Hall of Fame: John Elway, Floyd 
                    Little, Shannon Sharpe, Gary Zimmerman, Terrell Davis, Champ Bailey and Steve Atwater, along with late club owner Pat Bowlen.
                </p>
            </div>
        </div>
        </div>
        <a class="footer" href="https://github.com/BroncoMark/markpedersen.click/tree/main/broncos-vue">GitHub</a>
  </div>
</template>

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
