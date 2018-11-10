<template>
  <div id="main">
    <div class="team-wrapper">
      <div class="team" id="atl">
      ATL
      </div>
      <div class="player-wrapper">
        <div class="player">T. YOUNG</div>
        <div class="player">K. BAZEMORE</div>
        <div class="player">T. PRINCE</div>
        <div class="player">O. SPELLMAN</div>
        <div class="player">A. LEN</div>
      </div>
    </div>
  </div>

</template>


<style scoped>
:root {
  --atl-bg-color: #e03a3e;
  --atl-txt-color: #c1d32f;
  --atl-alt-color: #26282a;
}
.team-wrapper > #atl {
  background-color: var(--atl-bg-color);
  color: var(--atl-txt-color);
  border-color: var(--atl-alt-color);
}

.team-wrapper {
  display: flex;
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
</style>
