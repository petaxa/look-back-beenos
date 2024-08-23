---
layout: cover
title: タスク -title
---

# 取り組んだタスク

---
title: タスク
---

<Header category="取り組んだタスク" />
<p class="absolute top-[40%] left-[10%] text-[55px]"
  v-motion
  :initial="{
    x: 0,
    y: 0,
    fontSize: `${55}px`
  }"
  :click-1="{
    x: -40,
    y: -60,
    fontSize: `${40}px`,
    transition: {
      duration: 600
    }
  }"
>
  フロント側の修正
</p>
<div class="absolute top-[40%] left-[11%]">
    <p v-click="2" class="detail text-2xl">要件 > 設計 > 実装</p>
    <p v-click="3" class="detail text-2xl">導出元データの確認</p>
</div>
<img v-click="[1, 2]" class="w-80 absolute top-30 left-120 opacity-80" src="/vue.png">
<img v-click="[2, 3]" class="w-80 absolute top-30 left-120 opacity-80" src="/documents.png">
<img v-click="[3, 4]" class="w-80 absolute top-30 left-120 opacity-80" src="/laravel.png">
<div class="w-150 absolute top-15 left-110">
  <img v-click="4" class="w-50 opacity-80 absolute top-0 left-31" src="/vue.png">
  <img v-click="4" class="w-50 opacity-80 absolute top-50 left-0 ml-3" src="/documents.png">
  <img v-click="4" class="w-50 opacity-80 absolute top-50 left-60 ml-3" src="/laravel.png">
</div>

<style>
.slidev-vclick-target {
  transition: all 500ms ease;
}
.slidev-vclick-hidden {
  transform: scale(0);
}
.detail.slidev-vclick-hidden {
  transform: translate(20px);
}
</style>
