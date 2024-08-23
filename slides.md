---
# You can also start simply with 'default'
theme: default
title: look back BEENOS intern
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: Zen Maru Gothic
  serif: Zen Maru Gothic
  mono: Shippori Mincho
---

# BEENOS インターン振り返り

<div class="blur-circle-positive absolute top-30 left-30"></div>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer utilities {
  .blur-circle-positive {
    position: absolute;
    width: 800px;
    height: 200px;
    background: rgba(145, 130, 32, 0.4);
    filter: blur(110px);
    border-radius:0%;
    transform: rotate(30deg);
    z-index: 100;
  }
}
</style>

---
src: ./pages/greet.md
---

---
src: ./pages/target.md
---

---
src: ./pages/task.md
---

---
src: ./pages/result.md
---

---
src: ./pages/learning.md
---

---
src: ./pages/closing.md
---
