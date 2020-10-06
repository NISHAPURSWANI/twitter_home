<template>
  <div class="container">
    <div class="left">
      <b-button pill variant="outline-primary" class="t_but">
        <i
          class="fab fa-twitter"
          style="font-size:40px; color:rgba(21, 161, 242, 1); "
        ></i
      ></b-button>
      <b-button pill variant="outline-primary" class="t_button">
        <i class="fas fa-home" style="font-size:30px; "></i
        ><span class="textbtn">Home</span></b-button
      >
      <b-button pill variant="outline-primary" class="t_button">
        <i class="fas fa-hashtag" style="font-size:30px; "></i
        ><span class="textbtn">Explore</span></b-button
      >
      <b-button
        pill
        variant="outline-primary"
        class="t_button"
        style="width:180px;margin-left:30px;"
      >
        <i class="far fa-bell" style="font-size:30px; "></i
        ><span class="textbtn">Notifications</span></b-button
      >
      <b-button pill variant="outline-primary" class="t_button">
        <i class="far fa-envelope" style="font-size:30px; "></i
        ><span class="textbtn">Messages</span></b-button
      >
      <b-button
        pill
        variant="outline-primary"
        class="t_button"
        style="width:180px;margin-left:30px;"
      >
        <i class="far fa-bookmark" style="font-size:30px; "></i
        ><span class="textbtn">Bookmarks</span></b-button
      >
      <b-button pill variant="outline-primary" class="t_button">
        <i class="far fa-list-alt" style="font-size:30px; "></i
        ><span class="textbtn">Lists</span></b-button
      >
      <b-button pill variant="outline-primary" class="t_button">
        <i class="far fa-user" style="font-size:30px; "></i
        ><span class="textbtn">Profile</span></b-button
      >
      <b-button pill variant="outline-primary" class="t_button">
        <i class="fas fa-ellipsis-h" style="font-size:30px; "></i
        ><span class="textbtn">More</span></b-button
      >

      <b-button pill variant="primary" class="twitter_button">Tweet</b-button>
    </div>
    <div class="navigate">
      <div class="home">
        <div class="hometext">
          Home
          <span class="star">
            <i
              class="far fa-star"
              style="margin-top:8px;
  margin-bottom: 14.1px; font-size:20px;color:rgba(21, 161, 242, 1);"
            ></i>
          </span>
        </div>
      </div>
    </div>
    <div class="whhc">
      <div class="contentarea">
        <div class="whatshappening">
          <div class="whatshappeningcontent">
            <div>
              <i
                class="fas fa-user-circle"
                style="font-size:49px;margin-left:-50px;"
              ></i>
            </div>
            <div style="margin-top:-50px;">
              <input type="text" placeholder="What's happening?" class="whc" />
            </div>
            <div class="whci">
              <button class="toi_but">
                <i
                  class="far fa-image"
                  style="margin-top:10px;color:rgba(21, 161, 242, 1);font-weight:lighter"
                ></i>
              </button>
              <button class="toi_but">
                <i
                  class="far fa-calendar-alt"
                  style="margin-top:10px;color:rgba(21, 161, 242, 1);font-weight:lighter"
                ></i>
              </button>
              <button class="toi_but">
                <i
                  class="far fa-chart-bar"
                  style="margin-top:10px;color:rgba(21, 161, 242, 1);font-weight:lighter"
                ></i>
              </button>
              <button class="toi_but">
                <i
                  class="far fa-smile"
                  style="margin-top:10px;color:rgba(21, 161, 242, 1);font-weight:lighter"
                ></i>
              </button>
              <b-button pill variant="primary" class="tweet_button"
                >Tweet</b-button
              >
            </div>
          </div>
        </div>
        <div
          style="height:10px;width:598px;  border: 1px solid rgb(195,195,195);
1px;  background-color: rgb(245, 248, 250);
;margin-top:-5px;"
        ></div>

        <div class="newsarea">
          <div class="feedarea">
            <div class="mycards">
              <div class="card1" style="margin-top:10px;">
                <img
                  alt="Vue logo"
                  src="../assets/toi.png"
                  style="height:49px; width:49px; border-radius:100%; margin-left:-40px; margin-top:10px;"
                />

                The Times of India
                <i
                  class="fas fa-check-circle"
                  style="color: rgba(21, 161, 242, 1);"
                ></i
                ><span style="color:gray; font-size:15px;">
                  @times of india</span
                >

                <img
                  alt="Vue logo"
                  src="../assets/refimg.png"
                  style="height:235px; width:507px; border-radius:10px;  border: 1px solid rgb(195,195,195);
1px solid rgba(45, 50, 58, 0.4);; margin-left:20px; "
                />

                <p
                  style="font-weight:lighter; margin-left:30px; font-size:15px;"
                >
                  8:26 PM · Oct 3, 2020·TweetDeck
                </p>
                <p class="iconsonfeed" style="margin-left:15px;">
                  <i class="far fa-comment" style="margin-left:20px;"></i> 1
                  <i
                    class="fas fa-retweet"
                    style="margin-left:100px; font-weight:lighter;"
                  ></i>
                  2 <i class="far fa-heart" style="margin-left:100px;"></i> 3
                  <i class="far fa-share-square" style="margin-left:90px;"></i>
                  4
                </p>
              </div>
            </div>

            <div class="feed">
              <div class="mycards">
                <div class="card1">
                  <img
                    alt="Vue logo"
                    src="../assets/toi.png"
                    style="height:49px; width:49px; border-radius:100%; margin-left:-40px; margin-top:10px;"
                  />

                  The Times of India
                  <i
                    class="fas fa-check-circle"
                    style="color: rgba(21, 161, 242, 1);"
                  ></i
                  ><span style="color:gray; font-size:15px;">
                    @times of india</span
                  >
                  <p class="cardtext">
                    adds 14,348 #Covid19 cases, taking state's tally to
                    14,30,861; toll mounts to 37,758 with 278 deaths, reports
                    PTI quoting state health department.
                  </p>

                  <p
                    style="font-weight:lighter; margin-left:30px; font-size:15px;"
                  >
                    8:26 PM · Oct 3, 2020·TweetDeck
                  </p>
                  <p class="iconsonfeed" style="margin-left:15px;">
                    <i class="far fa-comment" style="margin-left:20px;"></i> 55
                    <i
                      class="fas fa-retweet"
                      style="margin-left:100px; font-weight:lighter;"
                    ></i>
                    55 <i class="far fa-heart" style="margin-left:90px;"></i> 25
                    <i
                      class="far fa-share-square"
                      style="margin-left:90px;"
                    ></i>
                    20
                  </p>
                </div>
              </div>

              <div class="feed">
                <div class="mycards">
                  <div class="card1">
                    <img
                      alt="Vue logo"
                      src="../assets/toi.png"
                      style="height:49px; width:49px; border-radius:100%; margin-left:-40px; margin-top:10px;"
                    />

                    The Times of India
                    <i
                      class="fas fa-check-circle"
                      style="color: rgba(21, 161, 242, 1);"
                    ></i
                    ><span style="color:gray; font-size:15px;">
                      @times of india</span
                    >
                    <p class="cardtext">
                      adds 14,348 #Covid19 cases, taking state's tally to
                      14,30,861; toll mounts to 37,758 with 278 deaths, reports
                      PTI quoting state health department.
                    </p>
                    <img
                      alt="Vue logo"
                      src="../assets/refimg.png"
                      style="height:235px; width:507px; border-radius:10px;  border: 1px solid rgb(195,195,195);
1px solid rgba(45, 50, 58, 0.4);; margin-left:20px; "
                    />

                    <p
                      style="font-weight:lighter; margin-left:30px; font-size:15px;"
                    >
                      8:26 PM · Oct 3, 2020·TweetDeck
                    </p>
                    <p class="iconsonfeed" style="margin-left:15px;">
                      <i
                        class="far fa-comment"
                        style="margin-left:20px; font-weight:lighter;"
                      ></i>
                      20
                      <i class="fas fa-retweet" style="margin-left:100px;"></i>
                      20
                      <i class="far fa-heart" style="margin-left:100px;"></i> 2
                      <i
                        class="far fa-share-square"
                        style="margin-left:90px;"
                      ></i>
                      22
                    </p>
                  </div>
                </div>

                <div class="feed">
                  <div class="mycards">
                    <div class="card1">
                      <img
                        alt="Vue logo"
                        src="../assets/toi.png"
                        style="height:49px; width:49px; border-radius:100%; margin-left:-40px; margin-top:10px;"
                      />

                      The Times of India
                      <i
                        class="fas fa-check-circle"
                        style="color: rgba(21, 161, 242, 1);"
                      ></i
                      ><span style="color:gray; font-size:15px;">
                        @times of india</span
                      >

                      <img
                        alt="Vue logo"
                        src="../assets/refimg.png"
                        style="height:235px; width:507px; border-radius:10px;  border: 1px solid rgb(195,195,195);
1px solid rgba(45, 50, 58, 0.4);; margin-left:20px; "
                      />
                      <p class="cardtext" style="margin-top:10px;">
                        adds 14,348 #Covid19 cases, taking state's tally to
                        14,30,861; toll mounts to 37,758 with 278 deaths,
                        reports PTI quoting state health department.
                      </p>

                      <p
                        style="font-weight:lighter; margin-left:30px; font-size:15px;"
                      >
                        8:26 PM · Oct 3, 2020·TweetDeck
                      </p>
                      <p class="iconsonfeed" style="margin-left:15px;">
                        <i
                          class="far fa-comment"
                          style="margin-left:20px; "
                        ></i>
                        25
                        <i
                          class="fas fa-retweet"
                          style="margin-left:100px; font-weight:lighter;"
                        ></i>
                        22
                        <i class="far fa-heart" style="margin-left:100px;"></i>
                        25
                        <i
                          class="far fa-share-square"
                          style="margin-left:90px;"
                        ></i>
                        25
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div></div>
      </div>
      <div class="ssone">
        <div class="ss">
          <i
            class="fas fa-search"
            style="font-size:25px;font-weight:lighter;color:rgba(21, 161, 242, 1); margin-top:10px;"
          ></i>
          <input type="text" class="sea" placeholder="Search twitter" />
        </div>
        <!-- </div> -->
        <div class="mylistone">
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
                style="height:69px; width:69px; border-radius:15px ;display:flex;float:right; margin-right:15px;margin-top:10px;"
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
            <div class="showmore">Show more</div>
          </div>
        </div>
        <div class="mylisttwo">
          <div class="followlist">
            <div class="followlistheading">Who to follow</div>
            <div class="followlisttext">
              <img
                alt="Vue logo"
                src="../assets/upsave.png"
                style="height:49px; width:49px; border-radius:100%; margin-top:10px;"
              />
              <span class="uptext">
                upGrad
                <i
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
              <span class="uptext">
                upGrad
                <i
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
              <span class="uptext">
                upGrad
                <i
                  class="fas fa-check-circle"
                  style="color: rgba(21, 161, 242, 1);"
                ></i
              ></span>

              <b-button pill variant="outline-primary" class="followbtn"
                ><span class="followtxt">Follow</span></b-button
              >
            </div>

            <div class="followshowmore">Show more</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container {
  position: relative;
  background-color: white;
  height: auto;
}
.left {
  border: 1px solid rgb(195, 195, 195);
  padding-left: 0px;
  padding-top: 0px;
  padding-bottom: 0px;
  padding-top: 0px;
  box-sizing: border-box;
  display: flex;
  flex-basis: auto;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 300px;
  height: auto;
  border: none;
  position: fixed;
  margin-left: -200px;

}

.leftside {
  display: flex;
  flex-direction: column;
  /* padding-left: 10px; */
  /* padding-right: 10px; */
  overflow-y: auto;
  margin: auto;
  align-content: flex-start;
  position: fixed;
  /* margin-left: -50px; */
}
.iconbtn {
  display: flex;
  float: left;
  padding-top: 10px;
  padding-bottom: 10px;
  height: 50px;
  width: 180px;
  border-radius: 50px;
  margin-bottom: 10px;
  border: 1px;
  background-color: rgb(255, 255, 255);
  border-radius: 50px;
}
.iconbtn:hover {
  background-color: rgba(29, 161, 242, 0.1);
}
.tbtn {
  width: 60px;
  border-radius: 50px;
  background-color: rgb(255, 255, 255);
  border: 1px;
}
.tbtn:hover {
  background-color: rgba(29, 161, 242, 0.1);
}
.twitter_button {
  margin-top: 20px;
  width: 200px;
  height: 49px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(21, 161, 242, 1);
  border: 0px;
}
.t_button {
  display: flex;
  float: left;
  height: 49px;
  margin-top: 20px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(255, 255, 255);
  border: 0px;
  width: 150px;
  padding-top: 10px;
  margin-right: 20px;
  color: black;
}
.textbtn {
  padding-left: 10px;
  padding-top: 2px;
  font-weight: bolder;
  font-size: 18px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.t_btn:hover {
  color: rgba(21, 161, 242, 1);
}
.home {
  width: 598px;
  height: 53px;
  border: 1px solid rgb(195, 195, 195);
  background-color: white;
  position: fixed;
  z-index: 1;
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
  background-color: white;
}
.star {
  display: flex;
  float: right;
  margin-right: 15px;
}
.contentarea {
  margin-left: 150px;
  height: auto;
  width: auto;
  position: fixed;
  background-color: white;
  margin-top: 53px;
  position: absolute;
}
.whatshappening {
  width: 598px;
  height: 117px;
  border: 1px solid rgb(195, 195, 195);
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
  display: flex;
  float: right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: bold;
  background-color: rgba(21, 161, 242, 1);
  border: 0px;
}

.showmore {
  height: 49px;
  padding-left: 15px;
  color: rgba(21, 161, 242, 1);
  font-weight: 400;
  font-size: 18px;
  padding-top: 15px;
}
.boldtext {
  font-weight: bold;
  margin-top: -15px;
}
.card1 {
  height: auto;
  width: 500px;
  margin-left: 57px;
  padding-top: 5px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: bolder;
}
.cardtext {
  font-size: 18px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: lighter;
  margin-left: 20px;
  margin-top: -15px;
}
.feedarea {
  height: auto;
  width: 598px;
  margin-top: -10px;
}
.iconsonfeed {
  margin-top: -15px;
}
.borderbottom {
  border-bottom: 0px solid rgba(45, 50, 58, 0.4);

  width: 598px;
}
.boldtext {
  font-weight: bold;
  margin-top: -15px;
}
.followlist {
  position: absolute;
  width: 350px;
  height: auto;
  border-radius: 15px;
  border: 1px solid rgb(195, 195, 195);
  margin-top: 590px;
  background-color: rgb(245, 248, 250);
  margin-top: 680px;
}
.followlistheading {
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);

  padding-top: 12.1px;
  padding-bottom: 12.1px;
  padding-left: 15px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: 900;
}
.followlisttext {
  height: 70px;
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);

  padding-left: 15px;
  font-size: 18px;
}
.followshowmore {
  height: 49px;
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
  margin-top: 20px;
}
.followtxt {
  margin-top: -5px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: bold;
  font-size: 18px;
}
.uptext {
  font-weight: bold;
  margin-left: 5px;
}
.mycards {
  width: 598px;
  border: 1px solid rgb(195, 195, 195);
  border-top: 0px;
}
.mycards:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.listheading:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.followlistheading:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.listtext:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.followlisttext:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.showmore:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.followshowmore:hover {
  background-color: rgba(45, 50, 58, 0.1);
}
.followbtn:hover {
  background-color: rgb(193, 220, 247);
}
.followbtn:hover {
  color: rgb(3, 140, 252);
}
.whcibtn:hover {
  background-color: turquoise;
}
.navigate {
  margin-left: 150px;
  height: 53px;
  position: fixed;
  z-index: 1;
}
.ss {
  height: 53px;
  width: 350px;
  border: 1px solid rgb(195, 195, 195);
  border-radius: 30px;
  padding: 5px;
  position: fixed;
  z-index: 1;
  background-color: white;
}
.ssone {
  margin-left: 830px;
  width: 350px;
}
.sea {
  width: 308px;
  height: 40px;
  border: none;
  padding: 10px;
  font-size: 18px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-weight: bold;
  position: fixed;
  z-index: 1;
  background-color: white;
}
.mylisttwo {
  padding-top: 20px;
}
.newsarea {
  width: 598px;
  height: auto;
}
.list {
  position: absolute;
  width: 350px;
  height: auto;
  border-radius: 15px;
  border: 1px solid rgba(45, 50, 58, 0.4);
  margin-top: 85px;
  background-color: rgb(245, 248, 250);
}
.listheading {
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);

  padding-top: 12.1px;
  padding-bottom: 12.1px;
  padding-left: 15px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  font-size: 18px;
  font-weight: 900;
}
.listtext {
  height: 89px;
  border-bottom: 1px solid rgba(45, 50, 58, 0.4);
  padding-left: 15px;
  font-size: 18px;
}
.btn-outline-primary:hover {
  background-color: rgb(240, 245, 245);
  color: rgba(21, 161, 242, 1);
}
.btn-primary:hover {
  background-color: rgb(18, 133, 199);
}
.t_but {
  margin-left: -100px;
  border: none;
}
.toi_but {
  border-radius: 100%;
  margin-top: -20px;
  border: none;
  background-color: white;
}
.toi_but:hover {
  background-color: rgb(240, 245, 245);
  color: rgba(21, 161, 242, 1);
}
</style>