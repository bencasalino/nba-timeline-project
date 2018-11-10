<template>
  <div id="main">
    <div class="team-wrapper">
      <div class="team" id="atl">
        ATL
      </div>
      <div class="player-wrapper">
        <div class="player">T. YOUNG</div>
        <div class="player alt">K. BAZEMORE</div>
        <div class="player">T. PRINCE</div>
        <div class="player alt">O. SPELLMAN</div>
        <div class="player">A. LEN</div>
      </div>
    </div>

    <div class="team-wrapper">
      <div class="team" id="orl">
        ORL
      </div>
      <div class="player-wrapper">
        <div class="player">D. AUGUSTIN</div>
        <div class="player alt">E. FORUNIER</div>
        <div class="player">J. ISSAC</div>
        <div class="player alt">A. GORDON</div>
        <div class="player">N. VUCEVIC</div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
@import "../scss/colors.scss";

.team {
  width: 50px;
  max-width: 50px;
  text-align: center;
  font-weight: bold;
}

.team-wrapper,
.player-wrapper {
  display: flex;
  flex-direction: row;
}

.team-wrapper {
  padding-bottom: 20px;
}

.player {
  display: flex;
  justify-content: center;
  align-items: center;
}
.player.alt {
  background-color: #dcdcdc;
}

.player {
  background-color: #d3d3d3;
  max-width: 100px;
  width: 100px;
  font-size: 12px;
  text-align: center;
  // padding: 5px 2px 0 2px;
  // height: 20px;
}

#atl {
  color: $atl-3;
  background-color: $atl-1;
  // border-bottom: 2px solid $atl-1;
}
#orl {
  color: $orl-2;
  background-color: $orl-1;
  // border-bottom: 2px solid $orl-3;
}
</style>



