<template>
<div class="main">
<div class="team-wrapper">
      <div class="team" id="atl">
        TEAM NAME
      </div>
    </div>
    <div class="player-wrapper">
      <div class="player">PLAYER</div>
      <div class="player">PLAYER</div>
      <div class="player">PLAYER</div>
      <div class="player">PLAYER</div>
      <div class="player">PLAYER</div>
    </div>
    <div class="player-image-wrapper">
      <div class="player-image">
        <a href="#">
          <img src="#" alt="#">
        </a>
      </div>
      <div class="player-image">
        <a href="#">
          <img src="#" alt="#">
        </a>
      </div>
      <div class="player-image">
        <a href="#">
          <img src="#" alt="#">
        </a>
      </div>
      <div class="player-image">
        <a href="#">
          <img src="#" alt="#">
        </a>
      </div>
      <div class="player-image">
        <a href="#">
          <img src="#" alt="#">
        </a>
      </div>
    </div>
    </div>
    </div>
</template>

<style scoped>
.team-wrapper {
  display: flex;
}

.team {
  background-color: #666666;
  padding: 10px;
  max-width: 500px;
  width: 500px;
  text-align: center;
  border-bottom: solid 2px;
}

.player-wrapper {
  display: flex;
}

.player {
  max-width: 100px;
  width: 100px;
  font-size: 12px;
  text-align: center;
  /* background-color: #555555; */
  padding: 5px 2px 0 2px;
  height: 20px;
}

.player-image-wrapper {
  display: flex;
}

.player-image {
  max-width: 100px;
  width: 100px;
  font-size: 12px;
  text-align: center;
  /* background-color: #444444; */
  /* padding: 5px 2px 0 2px; */
  height: 60px;
}
</style>
