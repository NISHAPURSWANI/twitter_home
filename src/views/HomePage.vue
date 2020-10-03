<template>
  <div class="container">
    <div class="leftside_nav">
      <div class="leftside">
        <i
          class="fab fa-twitter"
          style="font-size:50px; padding-top:6px; padding-bottom:6px; color:rgba(21,161,242,1);"
        >
        </i>
        <i
          class="fas fa-home"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="fas fa-hashtag"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="far fa-bell"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="far fa-envelope"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="far fa-bookmark"
          style="font-size:50px; padding-top:10px; padding-bottom:10px; margin-left:2px;"
        ></i>
        <i
          class="far fa-list-alt"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="far fa-user"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <i
          class="fas fa-ellipsis-h"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;"
        ></i>
        <div class="mytext">
          Home
          <p class="heading">Explore</p>
          <p class="heading">Notifications</p>
          <p class="heading">Messages</p>
          <p class="heading">Bookmarks</p>
          <p class="heading">Lists</p>
          <p class="heading">Profile</p>
          <p class="heading">More</p>
        </div>

        <b-button pill variant="primary" class="twitter_button">Tweet</b-button>
      </div>
    </div>
    <div class="navbar">
      <div class="home">
        <div class="hometext">
        Home 
        <span class="star"><i class="far fa-star" style="margin-top:8px;
  margin-bottom: 14.1px; font-size:20px;"></i></span>
        </div>
        
      </div>
      <div class="searcharea">
        <input type="search" placeholder="Search Twitter" class="searchbox"  >
                 
        </div>
    </div>
    <div class="contentarea">
              <i class="far-fa user" style="height:49px; width:49px;"></i>

      <div class="whatshappening">
        <div class="whatshappeningcontent" >
          <!-- <i class="fas fa-user-circle" style="font-size:40px;margin-left:-50px;margin-top:15px;" ></i> -->
          <div><i class="fas fa-user-circle" style="font-size:49px;margin-left:-50px;" ></i></div>
          <!-- <i class="fas fa-user-circle" style="margin-left:-10px;"></i> -->
          <div style="margin-top:-50px;"><input type="text" placeholder="What's Happening?" class="whc" ></div>
          <div class="whci">
          <i class="far fa-image" style="margin-top:10px;"></i>
          <i class="far fa-calendar-alt" style="margin-left:10px;"></i>
          <i class="fas fa-chart-bar" style="margin-left:10px;"></i>
          <i class="far fa-smile" style="margin-left:10px;"></i>
          <b-button pill variant="primary" class="tweet_button">Tweet</b-button>
          </div>
         <div class="feedarea">
           <div class="card1">
             The Times of India         
              <i class="fas fa-check-circle" style="color: rgba(21, 161, 242, 1);"></i><span style="color:gray; font-size:15px;">  @times of india</span>
             <p class="cardtext">adds 14,348 #Covid19 cases, taking state's tally to 14,30,861; toll mounts to 37,758 with 278 deaths, reports PTI quoting state health department.
<br>8:26 PM · Oct 3, 2020·TweetDeck
</p>
<p class="iconsonfeed">
  <i class="far fa-comment" ></i>
  <i class="fas fa-retweet" style="margin-left:100px;"></i>
  <i class="far fa-heart" style="margin-left:100px;"></i>
  <i class="far fa-share-square" style="margin-left:100px;"></i>
</p>
             </div>
         </div>

        <!-- <div class="listarea">
                  <div class="list">
          <p class="listheading">What's Happening</p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
                    <p class="listtext"></p>
          <p class="listtext"></p>
                    <p class="listtext"></p>
          <p class="listtext"></p>
                    <p class="listtext"></p>
          <p class="listtext"></p>
                    <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="showmore">Show more</p>
        </div> -->
        <!-- <div class="followlist">
          <p class="followlistheading">Who to follow</p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followshowmore">Show more</p>
        </div> -->
      <!-- </div>     -->

  
        </div>
             </div>
      <div class="lists">
          <div class="list">
          <p class="listheading">What's Happening</p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="showmore">Show more</p>
        </div>
           <!-- <div class="followlist">
          <p class="listheading">What's Happening</p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="showmore">Show more</p>
        </div> -->
        <div>
        <!-- <div class="followlist">
          <p class="followlistheading">Who to follow</p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followshowmore">Show more</p>
        </div> -->
        </div>
      </div>

    </div>
  </div>
</template>
<style scoped>
.mytext {
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 10px;
  padding-bottom: 10px;
  font-size: 20px;
  font-weight: bold;
  line-height: 1;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-left: 30px;
  position: absolute;
  margin-left: 50px;
  margin-top: 55px;
}
.leftside_nav {
  position: fixed;
  width: 300px;
  display: flex;
  -webkit-box-direction: normal;
  -webkit-box-orient: vertical;
  border: 0px solid black;
  display: flex;
  flex-basis: auto;
  flex-direction: column;
  flex-shrink: 0px;
  margin-left: 0px;
  margin-right: 0px;
  margin-bottom: 0px;
  margin-top: 0px;
  padding-top: 0px;
  padding-bottom: 0px;
  padding-left: 10px;
  padding-right: 10px;
  position: fixed;
  font-size: 15px;
}
.leftside {
  display: flex;
  flex-direction: column;
  padding-left: 10px;
  padding-right: 10px;
  overflow-y: auto;
  margin: auto;
  align-content: flex-start;
  position: absolute;
}
.twitter_button {
  margin-top: 20px;
  width: 250px;
  height: 49px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(21, 161, 242, 1);
  border: 0px;
}
.heading {
  margin-top: 30px;
}
.navbar{
  margin-left:300px;
  height:auto;
  width:auto;
  /* border:1px solid black; */
  position:fixed;
  background-color: white;
}
.home{
  width:600px;
  height:53px;
  border:1px solid;
  margin-left:-16px;
  margin-top:-10px;
}
.hometext{
  padding-top:0px;
  padding-bottom: 0px; 
  margin-top:11.1px;
  margin-bottom: 14.1px;
  margin-left: 15px;
  font-size:20px;
  font-weight: bold;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.star{
  display:flex;
  float:right;
  margin-right: 15px;
  
}
.searcharea{
  margin-left:30px;
}
.searchbox{
  padding:10px;
  width:350px;
  border-radius: 30px;
  height:53px;
  outline:none;
  background-color: rgba(255,255,255,0.1);
}
.contentarea{
margin-left:300px;
  height:auto;
  width:auto;
  /* border:1px solid black; */
  position:fixed;
  background-color: white;
  margin-top:57px;

}
.whatshappening{
   width:600px;
  height:117px;
  border:1px solid;
}
.whatshappeningcontent{
  margin-left: 55px;
  padding:10px;
    font-size:20px;
  font-weight: bold;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.whc{
   padding:10px;
   height:48.94px;
   width:505px;
   border:none;
}
.whci{
  margin-left: 10px;
  margin-top: 10px;
  font-size: 25px;
  color: rgba(21, 161, 242, 1);
  font-weight: 10;
}
.tweet_button {
  /* margin-top: -32px; */
  /* width: 250px; */
  /* height: 49px; */
  display:flex;
  float:right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(21, 161, 242, 1);
  border: 0px;
}
.lists{
  margin-left:630px;
  margin-top:-80px;
}
.list {
  position: absolute;
  /* margin-left: 637px; */
  width: 350px;
  height: auto;
  border-radius: 15px;
  border: 1px solid;
  margin-top: -15px;
  /* margin-top: 90px; */
}
.listheading {
  border-bottom: 1px solid;
  /* height: 48px; */
  padding-top: 12.1px;
  padding-bottom: 12.1px;
  font-size: 20px;
  padding-left: 15px;
  /* background-color: rgba(00, 0, 0,1); */
  /* border:none; */
}
.listtext {
  height: 49px;
  border-bottom: 1px solid;
}
.showmore {
  height: 29px;
  /* padding-top: 15px; */
  padding-left: 15px;
}
.followshowmore {
  height: 35px;
  padding-top: 15px;
  padding-left: 15px;
}
/* .followlist{
  margin-top: 35px;;
} */
.card1{
  height:auto;
  width:500px;
  /* border:1px solid; */
  /* margin-top:15px; */
  margin-left:57px;
  padding-top:5px;
  /* font-size: 15px; */
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  /* font-weight: lighter; */

}
.cardtext{
    
  /* margin-top:15px; */
  /* margin-top:5px; */
  font-size: 18px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-weight: lighter;
  /* color: grey; */

}
.feedarea{
  height:auto;
  border:1px solid;
  width:600px;
  margin-left:-65px;
  margin-top:15px;

}
.iconsonfeed{
  margin-top: -15px;
}
</style>
