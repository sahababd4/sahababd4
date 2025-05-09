<style>
  .container {
  position: relative;
  width: 24px;
  height: 24px;
}

.chevron {
  position: absolute;
  width: 28px;
  height: 2px;
  opacity: 0;
  transform: scale3d(0.5, 0.5, 0.5);
  animation: move 3s ease-out infinite;
}

.chevron:first-child {
  animation: move 3s ease-out 1s infinite;
}

.chevron:nth-child(2) {
  animation: move 3s ease-out 2s infinite;
}

.chevron:before,
.chevron:after {
  content: ' ';
  position: absolute;
  top: 0;
  height: 100%;
  width: 51%;
  background: #000;
}

.chevron:before {
  left: 0;
  transform: skew(0deg, 30deg);
}

.chevron:after {
  right: 0;
  width: 50%;
  transform: skew(0deg, -30deg);
}

@keyframes move {
  25% {
    opacity: 1;

  }
  33% {
    opacity: 1;
    transform: translateY(30px);
  }
  67% {
    opacity: 1;
    transform: translateY(40px);
  }
  100% {
    opacity: 0;
    transform: translateY(55px) scale3d(0.5, 0.5, 0.5);
  }
}

.text {
  display: block;
  margin-top: 75px;
  margin-left: -30px;
  font-family: "Helvetica Neue", "Helvetica", Arial, sans-serif;
  font-size: 12px;
  color: #000;
  text-transform: uppercase;
  white-space: nowrap;
  opacity: .25;
  animation: pulse 2s linear alternate infinite;
}

@keyframes pulse {
  to {
    opacity: 1;
  }
}
</style>
<img src="https://github.com/sahababd4/sahababd4/blob/bfd6db9d75be08e4c318280b5526a228df5be22b/adv_1.png" style="width:100%;">
<div class="container">
  <div class="chevron"></div>
  <div class="chevron"></div>
  <div class="chevron"></div>
  <span class="text">Scroll down</span>
</div>
<img src="https://github.com/sahababd4/sahababd4/blob/0ee8ce6214397679663688e5bec9412565da51e4/1st_page.png" style="width:100%;"><br>
<img src="https://github.com/sahababd4/sahababd4/blob/0ee8ce6214397679663688e5bec9412565da51e4/2nd_page.png" style="width:100%;"><br>
<img src="https://github.com/sahababd4/sahababd4/blob/0ee8ce6214397679663688e5bec9412565da51e4/3rd_page.png" style="width:100%;"><br>
<img src="https://github.com/sahababd4/sahababd4/blob/0ee8ce6214397679663688e5bec9412565da51e4/4th_page.png" style="width:100%;"><br>
<img src="https://github.com/sahababd4/sahababd4/blob/0ee8ce6214397679663688e5bec9412565da51e4/5th_page.png" style="width:100%;"><br>
<div class="container">
  <div class="chevron"></div>
  <div class="chevron"></div>
  <div class="chevron"></div>
  <span class="text">Scroll down</span>
</div>
<img src="https://github.com/sahababd4/sahababd4/blob/bfd6db9d75be08e4c318280b5526a228df5be22b/adv_2.png" style="width:100%;">
