<script setup lang="ts"></script>

<template>
  <div class="grass-mascot">
    <div class="grass-leaves-box">
      <div class="grass-leaves leaves1">
        <img src="@/assets/image/base.png" class="img" />
        <div class="leaves-progress progress1">
          <img src="@/assets/image/prog.png" class="img" />
        </div>
      </div>
      <div class="grass-leaves leaves2">
        <img src="@/assets/image/base.png" class="img" />
        <div class="leaves-progress progress2">
          <img src="@/assets/image/prog.png" class="img" />
        </div>
      </div>
      <div class="grass-leaves leaves3">
        <img src="@/assets/image/base.png" class="img" />
        <div class="leaves-progress progress3">
          <img src="@/assets/image/prog.png" class="img" />
        </div>
      </div>
      <div class="grass-leaves leaves4">
        <img src="@/assets/image/base.png" class="img" />
        <div class="leaves-progress progress4">
          <img src="@/assets/image/prog.png" class="img" />
        </div>
      </div>
      <div class="grass-leaves leaves5">
        <img src="@/assets/image/base.png" class="img" />
        <div class="leaves-progress progress5">
          <img src="@/assets/image/prog.png" class="img" />
        </div>
      </div>
    </div>
    <div class="grass-stem">
      <img src="@/assets/image/stem.png" class="img" />
    </div>
  </div>
</template>

<style scoped>
.img {
  width: 100%;
  height: 100%;
}

.grass-mascot {
  position: absolute;
  width: 316px;
  height: 399px;
}

.grass-mascot .grass-leaves-box {
  position: relative;
  width: 316px;
  height: 316px;
}

.grass-mascot .grass-leaves-box .grass-leaves {
  position: absolute;
  width: 140px;
  height: 166px;
  z-index: 2;
}

.grass-mascot .grass-leaves-box .leaves1 {
  transform: rotate(0deg);
  left: 88px;
}

.grass-mascot .grass-leaves-box .leaves2 {
  transform: rotate(72deg);
  right: 10px;
  top: 56px;
}

.grass-mascot .grass-leaves-box .leaves3 {
  transform: rotate(144deg);
  right: 40px;
  bottom: 5px;
}

.grass-mascot .grass-leaves-box .leaves4 {
  transform: rotate(216deg);
  left: 40px;
  bottom: 5px;
}

.grass-mascot .grass-leaves-box .leaves5 {
  transform: rotate(288deg);
  left: 10px;
  top: 56px;
}

.grass-mascot .grass-leaves-box .grass-leaves .leaves-progress {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
  -webkit-mask-image: url('@/assets/image/mask.svg');
  mask-size: 100% 100%;
  mask-repeat: no-repeat;
  mask-position: 0px 60px;
}

.grass-mascot .grass-stem {
  position: absolute;
  top: 147px;
  left: 143px;
  width: 108px;
  height: 252px;
}
</style>
