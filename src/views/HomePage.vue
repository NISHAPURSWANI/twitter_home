<template>
  <div class="container">
    <div class="leftside_nav">
      <div class="leftside">
        <p>
          <i
            class="fab fa-twitter"
            style="font-size:40px; padding-top:6px; padding-bottom:6px;"
          >
          </i>
        </p>
        <p>
          <i
            class="fas fa-home"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Home</span>
        </p>
        <p>
          <i
            class="fas fa-hashtag"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Explore</span>
        </p>

        <p>
          <i
            class="far fa-bell"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Notifications</span>
        </p>
        <p>
          <i
            class="fas fa-envelope"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Messages</span>
        </p>

        <p>
          <i
            class="far fa-bookmark"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Bookmarks</span>
        </p>
        <p>
          <i
            class="far fa-list-alt"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">Lists</span>
        </p>
        <p>
          <i
            class="fas fa-user"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">profile</span>
        </p>
        <p>
          <i
            class="far fa-list-alt"
            style="font-size:30px;padding-top:4px; padding-bottom:4px;"
          ></i
          ><span class="text">More</span>
        </p>
        <p>
          <b-button pill variant="primary" class="twitter_button"
            >Twitter</b-button
          >
        </p>
      </div>
    </div>
    <div class="centerarea">
      <div class="topbar">
        <div class="home">
          Home
          <div class="searching">
            <input
              type="search"
              class="searchbox"
              placeholder="Search twitter"
            />
          </div>
        </div>
        <div class="list">
          <p class="listheading">What's Happening</p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="listtext"></p>
          <p class="showmore">Show more</p>
        </div>
        <div class="followlist">
          <p class="followlistheading">Who to follow</p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="followlisttext"></p>
          <p class="showmore">Show more</p>
        </div>
      </div>
      <div class="progressbar"></div>
      <div class="post"></div>
      <div class="extrarea"></div>
      <!----->
      <div>
        <div class="feed">
          <div class="texts">
            hello
          </div>
          <div class="articlearea">
            <div class="heading">
              hello
            </div>
            <b-card
              title="Card Title"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 507px;max-height:256.38px border:10px solid green;"
              class="card"
            >
            </b-card>
          </div>
        </div>
      </div>
      <div>
        <div class="feed">
          <div class="texts">
            hello
          </div>
          <div class="articlearea">
            <div class="heading">
              hello
            </div>
            <b-card
              title="Card Title"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 507px;max-height:256.38px border:10px solid green;"
              class="card"
            >
            </b-card>
          </div>
        </div>
      </div>
      <div>
        <div class="feed">
          <div class="texts">
            hello
          </div>
          <div class="articlearea">
            <div class="heading">
              hello
            </div>
            <b-card
              title="Card Title"
              img-src="https://picsum.photos/600/300/?image=25"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 507px;max-height:256.38px border:10px solid green;"
              class="card"
            >
            </b-card>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style >
.container {
  position: relative;
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
  width: 150px;
}
.text {
  margin-top: -20px;
}
.centerarea {
  -webkit-box-align: start;
  align-items: flex-start;
  flex-shrink: 1px;
  -webkit-box-flex: 1;
  flex-grow: 1;
  border: 1px solid black;
  flex-basis: auto;
  flex-direction: column;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  margin-top: 0px;
  min-width: 0px;
  min-height: 0px;
  padding-left: 0px;
  padding-right: 0px;
  padding-top: 0px;
  padding-bottom: 0px;
  position: relative;
  z-index: 0;
  margin-left: 300px;
  width: 1092px;
  height: auto;
}

.home {
  width: 600px;
  height: 53px;
  margin-right: 1px;
  border: 1px solid;
  z-index: 1;
  position: fixed;
  height: 53px;
  position: fixed;
  margin-left: 1px;
  padding-left: 15px;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-right: 15px;
  background-color: white;
}
.topbar {
  -webkit-box-align: start;
  align-items: flex-start;
  flex-shrink: 1px;
  -webkit-box-flex: 1;
  flex-grow: 1;
  border: 1px;
  flex-basis: auto;
  flex-direction: column;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  margin-top: 0px;
  min-width: 0px;
  min-height: 0px;
  padding-left: 0px;
  padding-right: 0px;
  padding-top: 0px;
  padding-bottom: 0px;
  position: relative;
  width: 1092px;
  height: auto;
}

.progressbar {
  height: 3px;
  width: 600px;
  border: 1px solid;
  position: absolute;
  margin-top: 53px;
}
.post {
  height: 117px;
  width: 600px;
  border: 1px solid;
  margin-top: 56px;
}
.extrarea {
  height: 10px;
  width: 600px;
  border: 1px solid;
  position: absolute;
}
.feed {
  height: 483.79px;
  border: 1px solid;
  width: 600px;
  padding: 15px;
  position: relative;
}
.article {
  margin-top: 53px;
}
.texts {
  width: 49px;
  height: 439.64px;
  border: 1px solid;
  position: relative;
}
.articlearea {
  width: 509px;
  height: 439.64px;
  border: 1px solid;
  position: absolute;
  margin-left: 50px;
  margin-top: -439.64px;
}
.heading {
  height: 30px;
  border: 1px solid;
  padding-left: 5px;
  padding-top: 4px;
}
.searchbox {
  margin-left: 620px;
  width: 350px;
  padding-left: 10px;
}
.list {
  position: absolute;
  margin-left: 637px;
  width: 350px;
  height: auto;
  border-radius: 30px;
  border: 1px solid;
  margin-top: 50px;
}
.listheading {
  border-bottom: 1px solid;
  height: 48px;
  padding-top: 12.1px;
  padding-bottom: 12.1px;
  font-size: 24.8px;
  padding-left: 15px;
}
.listtext {
  height: 89px;
  border-bottom: 1px solid;
}
.showmore {
  height: 49px;
  padding-top: 15px;
  padding-left: 15px;
}
.searching {
  margin-top: -30px;
}
.followlist {
  position: absolute;
  margin-left: 637px;
  width: 350px;
  height: auto;
  border-radius: 30px;
  border: 1px solid;
  margin-top: 620px;
}
.followlistheading {
  border-bottom: 1px solid;
  height: 48px;
  padding-top: 12.1px;
  padding-bottom: 12.1px;
  font-size: 24.8px;
  padding-left: 15px;
}
.followlisttext {
  height: 89px;
  border-bottom: 1px solid;
}
</style>