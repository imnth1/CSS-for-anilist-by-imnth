# CSS-for-anilist-by-imnth

/*CSS for anilist by imnth */

#app {
    background-color:
rgba(0, 0, 0, 0.3);
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;}

body {
    background-color: rgba(var(--color-background));
    background: url("https://i.imgur.com/dSwhbyy.jpg");

    background-position: center / 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;}

/* Transparent banner - use together with background image */
 .banner[data-v-4f7beb35] {
   background-image: none !important;
   background-color: rgb(36,37,56,0);
}

.logo img[data-v-4fbac4e1] {
    content: url(https://i.imgur.com/gKjNnZB.png);}


/*  -----------------------------------------| BANNER |-------------------------------------------- */


.banner-content > .name::after {
    content: "imnth";
    position: relative;
    left: 10px;
    top: -1px;
    background: rgba(var(--color-blue),.8);
    border-radius: 4px;
    color: rgba(255,225,255, 1);
    padding: 5px 8px;
    margin-bottom: 20px;
    margin-right: 16px;
    transition: .4s;
    font-size: 1.2rem;
    transition: .5s;
    text-transform: capitalize;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    animation-name: rainbow;
    animation-timing-function: ease-in-out;}


/*  -----------------------------| PROFILE | ACTIVITIES |----------------------------------- */

.activity-entry > .wrap, .input,  .reply, .list-stats,
.user .about > div.content-wrap, .activity-history, .genre-overview, .favourite {
    border-radius: 4px;
    border: 2px solid #a11515;
    font-size: 1.3rem;

    overflow: hidden; 
    transition: transform 0.7s; 
    position: relative;}

.activity-entry > .wrap:hover, .list-stats:hover, .user .about > div.content-wrap:hover, 
.activity-history:hover, .genre-overview:hover, .load-more:hover, .el-textarea:hover{
     border: solid firebrick 2px;
     opacity: 1;
     transform: scale(1.05);
     transition: all 0.45s ease-in-out;}

.favourites .favourite:hover {
     transition: transform 0.5s;
     transform: scale(1.2);
     z-index: 20;}

.favourites > .favourites-wrap {
    overflow: visible;}


/*  -----------------------------| ACTIVITIES |----------------------------------- */

.wrap > .text > .header > .avatar, .reply > .header > .avatar {
    border-radius: 100%; 
    transition: transform .2s;} 

.wrap > .text > .header > .avatar:hover, .reply > .header > .avatar:hover{
    transform: scale(1.59);}


/*  ---------------------------------| NAME TAGS |--------------------------------------- */


.text > .header > .name::after, .reply > .header > .name::after {
  content: 'Cool People';
  position: relative;
  top: -1px;
  left: 4px;
  border-radius: 20px;
  color: rgba(255,225,255, 1);
  padding: 5px 8px;
  margin-bottom: 20px;
  margin-right: 16px;
  transition: .4s;
  font-size: 1.2rem;
  transition: .5s;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  animation-name: rainbow;
  animation-timing-function: ease-in-out;}

a[href="/user/ChriSenpai/"]:not(.avatar):not(.user):not(.link):not(.primary-link)::after{ content: 'CSS God'; }

a[href="/user/HaarisHussain/"]:not(.avatar):not(.user):not(.link):not(.primary-link)::after { content: 'BestBoi'; }

a[href="/user/TatsuMaki01/"]:not(.avatar):not(.user):not(.link):not(.primary-link)::after { content: 'BestBoi'; }

a[href="/user/imnth/"]:not(.avatar):not(.user):not(.link):not(.primary-link)::after{ content: 'idiot'; }

/* Tooltip title */
.title[data-v-3f86aedd] {
    background: transparent;
}

/* Tooltip */
.tooltip[data-v-3f86aedd] {
    background: rgba(var(--color-blue),.8);
    border-radius: 10px;
    color: rgba(255,225,255, 1);
    transition: .3s;
    transition: .4s;
    animation-duration: 10s;
    animation-iteration-count: infinite;
    animation-name: rainbow;
    animation-timing-function: ease-in-out;
}

/* Studio Names */
.favourite.studio[data-v-0317d914] {
    font-weight: 800;
}

/* Chrome scrollbar */
::-webkit-scrollbar {
    width: 6px;
    background: #01232d;
}
::-webkit-scrollbar-corner {
    background: #01232d;
}
::-webkit-scrollbar-thumb {
    background: #ff1e00;
    -webkit-border-radius: 1ex;
}
/*Hides hoh download button*/
.hohDownload {
    display: none;
}
/* Anime/manga progress bar color */
.user-page-unscoped.red .progress .bar {
    background: linear-gradient(to right, #f00 5%, #ffed00 97%);
}

/* Change 7th fav chara cover (Armin) */
#app > div.page-content > div > div.content.container > div > div:nth-child(1) > div:nth-child(6) > div > a.character.favourite:nth-of-type(7) {
    content: url(https://i.imgur.com/hjZW3Un.gif);
}
