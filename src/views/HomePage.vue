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
          <span class="star"
            ><i
              class="far fa-star"
              style="margin-top:8px;
  margin-bottom: 14.1px; font-size:20px;"
            ></i
          ></span>
        </div>
      </div>
      <div class="searcharea">
        <input type="search" placeholder="Search Twitter" class="searchbox" />
      </div>
    </div>
    <div class="contentarea">
      <i class="far-fa user" style="height:49px; width:49px;"></i>
 
      <div class="whatshappening">
        <div class="whatshappeningcontent">
          <!-- <i class="fas fa-user-circle" style="font-size:40px;margin-left:-50px;margin-top:15px;" ></i> -->
          <div>
            <i
              class="fas fa-user-circle"
              style="font-size:49px;margin-left:-50px;"
            ></i>
          </div>
          <!-- <i class="fas fa-user-circle" style="margin-left:-10px;"></i> -->
          <div style="margin-top:-50px;">
            <input type="text" placeholder="What's happening?" class="whc" />
          </div>
          <div class="whci">
            <i class="far fa-image" style="margin-top:10px;"></i>
            <i class="far fa-calendar-alt" style="margin-left:10px;"></i>
            <i class="fas fa-chart-bar" style="margin-left:10px;"></i>
            <i class="far fa-smile" style="margin-left:10px;"></i>
            <b-button pill variant="primary" class="tweet_button"
              >Tweet</b-button
            >
          </div>
          <div class="feedarea">
            <div class="mycards">
            <div class="card1">
              <img
                alt="Vue logo"
                src="../assets/toi.png"
                style="height:49px; width:49px; border-radius:100%; margin-left:-40px;"
              />
 
              The Times of India
              <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ><span style="color:gray; font-size:15px;"> @times of india</span>
              <p class="cardtext">
                adds 14,348 #Covid19 cases, taking state's tally to 14,30,861;
                toll mounts to 37,758 with 278 deaths, reports PTI quoting state
                health department.
              </p>
              <img
                alt="Vue logo"
                src="../assets/refimg.png"
                style="height:235px; width:507px; border-radius:10px;border:1px solid; margin-left:20px; "
              />
 
              <p style="font-weight:lighter; margin-left:30px; font-size:20px;">
                8:26 PM · Oct 3, 2020·TweetDeck
              </p>
              <p class="iconsonfeed" style="margin-left:15px;">
                <i class="far fa-comment"></i>
                <i class="fas fa-retweet" style="margin-left:100px;"></i>
                <i class="far fa-heart" style="margin-left:100px;"></i>
                <i class="far fa-share-square" style="margin-left:100px;"></i>
              </p>
            </div>
            </div>
              <p class="borderbottom"></p>
            <!-------------->
            <div class="mycards">
            <div class="card1">
              <img
                alt="Vue logo"
                src="../assets/toi.png"
                style="height:49px; width:49px; border-radius:100%; margin-left:-40px;"
              />
 
              The Times of India
 
              <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ><span style="color:gray; font-size:15px;"> @times of india</span>
              <img
                alt="Vue logo"
                src="../assets/refimg.png"
                style="height:235px; width:507px; border-radius:10px;border:1px solid; margin-left:20px; "
              />
              <p class="cardtext" style="margin-top:5px;">
                adds 14,348 #Covid19 cases, taking state's tally to 14,30,861;
                toll mounts to 37,758 with 278 deaths, reports PTI quoting state
                health department. <br />8:26 PM · Oct 3, 2020·TweetDeck
              </p>
              <p class="iconsonfeed">
                <i class="far fa-comment" style="margin-left:15px;"></i>
                <i class="fas fa-retweet" style="margin-left:100px;"></i>
                <i class="far fa-heart" style="margin-left:100px;"></i>
                <i class="far fa-share-square" style="margin-left:100px;"></i>
              </p>
                          </div>

            </div>
              <p class="borderbottom"></p>
                          <div class="mycards">

            <div class="card1">
              <img
                alt="Vue logo"
                src="../assets/toi.png"
                style="height:49px; width:49px; border-radius:100%; margin-left:-40px;"
              />
 
              The Times of India
              <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ><span style="color:gray; font-size:15px;"> @times of india</span>
              <p class="cardtext">
                adds 14,348 #Covid19 cases, taking state's tally to 14,30,861;
                toll mounts to 37,758 with 278 deaths, reports PTI quoting state
                health department. <br />8:26 PM · Oct 3, 2020·TweetDeck
              </p>
              <p class="iconsonfeed">
                <i class="far fa-comment" style="margin-left:15px;"></i>
                <i class="fas fa-retweet" style="margin-left:100px;"></i>
                <i class="far fa-heart" style="margin-left:100px;"></i>
                <i class="far fa-share-square" style="margin-left:100px;"></i>
              </p>
                          </div>

                          </div>

              <p class="borderbottom"></p>
              <div class="mycards">
            <div class="card1">
              <img
                alt="Vue logo"
                src="../assets/toi.png"
                style="height:49px; width:49px; border-radius:100%; margin-left:-40px;"
              />
 
              The Times of India
              <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ><span style="color:gray; font-size:15px;"> @times of india</span>
              <p class="cardtext">
                adds 14,348 #Covid19 cases, taking state's tally to 14,30,861;
                toll mounts to 37,758 with 278 deaths, reports PTI quoting state
                health department. <br />8:26 PM · Oct 3, 2020·TweetDeck
              </p>
              <p class="iconsonfeed">
                <i class="far fa-comment" style="margin-left:15px;"></i>
                <i class="fas fa-retweet" style="margin-left:100px;"></i>
                <i class="far fa-heart" style="margin-left:100px;"></i>
                <i class="far fa-share-square" style="margin-left:100px;"></i>
              </p>
            </div>
              </div>
 
            <!-------------->
          </div>
        </div>
      </div>
      <div class="lists">
        <!--------------->
        <div class="list">
          <p class="listheading">What's happening</p>
          <img
            alt="Vue logo"
            src="../assets/refimagg.png"
            style="height:79px; width:79px; border-radius:15px;display:flex;float:right; margin-right:15px;"
          />
          <div class="listtext">
            <p>Covid-19 Live</p>
            <p class="boldtext">Covid-19 in India</p>
          </div>
          <div class="listtext">
            <p style="padding-top:15px;">Check</p>
            <p class="boldtext">check for working of Lists</p>
          </div>
          <div class="listtext">
            <img
              alt="Vue logo"
              src="../assets/ipl.png"
              style="height:69px; width:69px; border-radius:15px;display:flex;float:right; margin-right:15px;margin-top:10px;"
            />
            <p style="padding-top:5px;">IPL 2020 .LIVE</p>
            <p class="boldtext">IPL: Delhi wins by 18 runs</p>
            <p style="margin-top:-15px;">#Trending</p>
          </div>
 
          <!-- </p> -->
          <div class="listtext">
            <p
              style="  padding-top:15px;
"
            >
              Covid-19 Live
            </p>
            <p class="boldtext">Covid-19 in India</p>
          </div>
          <div class="listtext">
            <p
              style="   padding-top:15px;
"
            >
              Covid-19 Live
            </p>
            <p class="boldtext">Covid-19 in India</p>
          </div>
          <p class="showmore">Show more</p>
        </div>
        <!--------------------------------------->
        <!----------------------------->
        <div class="followlist">
          <div class="followlistheading">Who to follow</div>
          <div class="followlisttext">
            <img
              alt="Vue logo"
              src="../assets/upsave.png"
              style="height:49px; width:49px; border-radius:100%; margin-top:10px;"
            />
            <span class="uptext"> upGrad <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ></span>
              <!-- <span class="uptext"> @upGrad_edu</span> -->
            <b-button pill variant="outline-primary" class="followbtn"
              ><span class="followtxt">Follow</span></b-button
            >
          </div>
          <div class="followlisttext">
             <img
              alt="Vue logo"
              src="../assets/upsave.png"
              style="height:49px; width:49px; border-radius:100%; margin-top:10px;"
            />
                        <span class="uptext"> upGrad <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ></span>
 
            <b-button pill variant="outline-primary" class="followbtn"
              ><span class="followtxt">Follow</span></b-button
            >
          </div>
          <div class="followlisttext">
             <img
              alt="Vue logo"
              src="../assets/upsave.png"
              style="height:49px; width:49px; border-radius:100%; margin-top:10px;"
            />
                        <span class="uptext"> upGrad <i
                class="fas fa-check-circle"
                style="color: rgba(21, 161, 242, 1);"
              ></i
              ></span>
 
            <b-button pill variant="outline-primary" class="followbtn"
              ><span class="followtxt">Follow</span></b-button
            >
          </div>
 
          <!-- </p> -->
 
          <!-- </div> -->
 
          <!-- </div> -->
 
          <p class="followshowmore">Show more</p>
        </div>
        <!----------------------------->
      </div>
      <!----->
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
.navbar {
  margin-left: 300px;
  /* height: 50; */
  width: auto;
  /* border:1px solid black; */
  position: fixed;
  background-color: white;
  z-index: 1;
}
.home {
  width: 600px;
  height: 53px;
  border:1px solid rgba(45, 50, 58, 0.4);
  margin-left: -16px;
  margin-top: -10px;
  background-color: white;
}
.hometext {
  padding-top: 0px;
  padding-bottom: 0px;
  margin-top: 11.1px;
  margin-bottom: 14.1px;
  margin-left: 15px;
  font-size: 20px;
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.star {
  display: flex;
  float: right;
  margin-right: 15px;
}
.searcharea {
  margin-left: 30px;
}
.searchbox {
  padding: 10px;
  width: 350px;
  border-radius: 30px;
  height: 53px;
  outline: none;
  background-color: rgba(255, 255, 255, 0.1);
}
.contentarea {
  margin-left: 300px;
  height: auto;
  width: auto;
  /* border:1px solid black; */
  position: fixed;
  background-color: white;
  margin-top: 70px;
  position: absolute;
}
.whatshappening {
  width: 600px;
  height: 117px;
          border:1px solid rgba(45, 50, 58, 0.4);
  /* position:absolute; */
}
.whatshappeningcontent {
  margin-left: 55px;
  padding: 10px;
  font-size: 20px;
  font-weight: bold;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.whc {
  padding: 10px;
  height: 48.94px;
  width: 505px;
  border: none;
}
.whci {
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
  display: flex;
  float: right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(21, 161, 242, 1);
  border: 0px;
}
.lists {
  margin-left: 630px;
  margin-top: -80px;
}
.list {
  position: absolute;
  /* margin-left: 637px; */
  width: 350px;
  height: auto;
  border-radius: 15px;
          border:1px solid rgba(45, 50, 58, 0.4);
  margin-top: -15px;
  /* margin-top: 90px; */
  background-color: rgb(245, 248, 250);
}
.listheading {
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);;

  /* height: 48px; */
  padding-top: 12.1px;
  padding-bottom: 12.1px;
  padding-left: 15px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: 900;
  /* background-color: rgba(00, 0, 0,1); */
  /* border:none; */
  /* background-color:rgba(204,214,221,1) */
}
.listtext {
  height: 89px;
  border-bottom: 1px solid  rgba(45, 50, 58, 0.4);;;
  padding-left: 15px;
  font-size: 18px;
}
.showmore {
  height: 49px;
  /* padding-top: 15px; */
  padding-left: 15px;
  color: rgba(21, 161, 242, 1);
  font-weight: 400;
  font-size: 18px;
  padding-top: 15px;
}
/* .followshowmore {
  height: 35px;
  padding-top: 15px;
  padding-left: 15px;
} */
/* .followlist{
  margin-top: 35px;;
} */
.card1 {
  height: auto;
  width: 500px;
  /* border:1px solid; */
  /* margin-top:15px; */
  margin-left: 57px;
  padding-top: 5px;
  /* font-size: 15px; */
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  /* font-weight: lighter; */
}
.cardtext {
  /* margin-top:15px; */
  /* margin-top:5px; */
  font-size: 18px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: lighter;
  /* color: grey; */
  margin-left: 20px;
  margin-top: -15px;
}
.feedarea {
  height: auto;
  /* border: 1px solid; */
  width: 600px;
  margin-left: -65px;
  margin-top: 25px;
}
.iconsonfeed {
  margin-top: -15px;
  /* border-bottom: 1px solid; */
}
.borderbottom {
  border-bottom: 0px solid rgba(45, 50, 58, 0.4);;

  width: 600px;
  /* margin-left: -58px; */
}
.boldtext {
  font-weight: bold;
  margin-top: -15px;
}
.followlist {
  position: absolute;
  /* margin-left: 637px; */
  width: 350px;
  height: auto;
  border-radius: 15px;
        border:1px solid rgba(45, 50, 58, 0.4);
  /* margin-top: -15px; */
  /* margin-top: 90px; */
  margin-top: 590px;
  background-color: rgb(245, 248, 250);
}
.followlistheading {
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);;

  /* height: 48px; */
  padding-top: 12.1px;
  padding-bottom: 12.1px;
  padding-left: 15px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: 900;
  /* background-color: rgba(00, 0, 0,1); */
  /* border:none; */
  /* background-color:rgba(204,214,221,1) */
}
.followlisttext {
  height: 70px;
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);;

  padding-left: 15px;
  font-size: 18px;
}
.followshowmore {
  height: 35px;
  /* padding-top: 15px; */
  padding-left: 15px;
  color: rgba(21, 161, 242, 1);
  font-weight: 400;
  font-size: 18px;
  padding-top: 10px;
}
.followbtn {
  height: 30px;
  width: 78px;
  display: flex;
  float: right;
  margin-right: 15px;
  /* padding-top:15px; */
  margin-top: 20px;
}
.followtxt {
  /* padding-top:5px; */
  /* padding-left: 5px; */
  /* padding-bottom:5px; */
  margin-top: -5px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: bold;
  font-size: 18px;
}
.uptext{
  font-weight: bold;
  margin-left:5px;
}
.mycards{
  /* height:auto; */
  width: 600px;
  border:1px solid rgba(45, 50, 58, 0.4);
  margin-top:-20px;

  /* margin-left:-50px; */
  /* padding:15px; */
}
.mycards:hover{
  background-color: rgba(45, 50, 58, 0.1);
}
.listheading:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
.followlistheading:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
.listtext:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
.followlisttext:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
.showmore:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
.followshowmore:hover{
    background-color: rgba(45, 50, 58, 0.1);

}
</style>
 

 

