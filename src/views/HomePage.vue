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

          <input type="text" placeholder="What's Happening?" class="whc">


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
  border:1px solid black;
  position:fixed;
  background-color: white;
}
.home{
  width:600px;
  height:53px;
  border:1px solid;
  margin-left:-16px;
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
  border:1px solid black;
  position:fixed;
  background-color: white;
  margin-top:73px;

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

}
</style>
