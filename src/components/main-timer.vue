<template>
  <div class="timerContainer">
    <div class="countdownTime">
      0
    </div>
    <div class="countdownTime">
      0
    </div>
    <div class="countdownTime">
      0
    </div>
    <div class="countdownTime">
      0
    </div>
  </div>
</template>

<style>
.timerContainer{
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  align-items: center;
  align-content: center;
  justify-content: center;
  overflow: auto;
}
.countdownTime{
  font-size: 46px;
  display: inline-block;
  margin-left: 5rem;
}
</style>
