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
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="fas fa-hashtag"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="far fa-bell"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="far fa-envelope"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="far fa-bookmark"
          style="font-size:50px; padding-top:10px; padding-bottom:10px; margin-left:2px;margin-top:10px;"
        ></i>
        <i
          class="far fa-list-alt"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="far fa-user"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <i
          class="fas fa-ellipsis-h"
          style="font-size:50px; padding-top:10px; padding-bottom:10px;margin-top:10px;"
        ></i>
        <div class="mytext">
          Home
          <p class="heading">Explore</p>
          <p style="margin-top:40px;">Notifications</p>
          <p style="margin-top:40px;">Messages</p>
          <p style="margin-top:40px;">Bookmarks</p>
          <p style="margin-top:40px;">Lists</p>
          <p style="margin-top:40px;">Profile</p>
          <p style="margin-top:40px;">More</p>
        </div>

        <b-button pill variant="primary" class="twitter_button">Tweet</b-button>
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
  margin-top: 65px;
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
  margin-top: 40px;
}
</style>
