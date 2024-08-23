---
layout: cover
title: できたこと、できなかったこと -title
---

# できたこと、<br/>できなかったこと

---
title: できたこと
---

<Header category="できたこと、できなかったこと" />
<div class="blur-circle-positive absolute top-0 left-0"></div>
<div class="mt-30 flex justify-around items-center">
  <h1>できたこと</h1>
  <div>
    <p v-click="1" class="text-6">ドキュメントを読む、書く、理解する</p>
    <p v-click="2" class="text-6">コミュニケーション</p>
    <p v-click="3" class="text-6">Vueの知識を活かす</p>
    <p v-click="4" class="text-6">理解度の浅い言語で処理を理解する</p>
  </div>
</div>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer utilities {
  .blur-circle-positive {
    position: absolute;
    width: 400px;
    height: 400px;
    background: rgba(100, 255, 200, 0.5);
    filter: blur(150px);
    border-radius: 50%;
  }
}
.slidev-vclick-target {
  transition: all 600ms ease;
}
</style>

---
title: できなかったこと
---

<Header category="できたこと、できなかったこと" />
<div class="blur-circle-negative absolute top-0 left-0"></div>
<div class="mt-30 flex justify-around items-center">
  <h1>できなかったこと</h1>
  <div>
    <p v-click="1" class="text-6">改善点の発見</p>
    <div class="ml-10">
      <p v-click="2" class="text-6">Vueはそのレベルを求めたい</p>
      <p v-click="3" class="text-6">バックエンド領域の知識不足</p>
    </div>
    <div class="mt-7">
      <p v-click="4" class="text-6">網羅的なコードリーディング</p>
    </div>
  </div>
</div>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer utilities {
  .blur-circle-negative {
    position: absolute;
    width: 400px;
    height: 400px;
    background: rgba(255, 200, 100, 0.5);
    filter: blur(150px);
    border-radius: 50%;
  }
}
.slidev-vclick-target {
  transition: all 600ms ease;
}
</style>
