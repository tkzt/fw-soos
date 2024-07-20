---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Fine Weather
info: |
  ## Fine Weather
  Codekitchen SOOS Sprint 5
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Fine Weather

代码厨房开源松 Sprint 5

By Allen @tkzt

---
transition: fade-out
---

# 项目介绍

<v-clicks>

- 📸 一个[相册应用](https://fine-weather-gallery.tkzt.cn/)

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-60%">
<img src="/assets/Snipaste_2024-07-20_21-21-44.jpg" class="h-90%"/>
</div>

</v-clicks>

<v-click>

- 🛠️ 基于：
  - <div class="flex items-center" ><img src="https://api.iconify.design/vscode-icons:file-type-vue.svg" class="mr-2"/> Vue </div>
  - <div class="flex items-center" ><img src="https://api.iconify.design/logos:unocss.svg" class="mr-2"/> UnoCSS </div>
  - <div class="flex items-center" ><img src="https://api.iconify.design/logos:vueuse.svg" class="mr-2"/> VueUse </div>
  - <div class="flex items-center" ><img src="https://animate.style/img/favicon.ico" class="mr-2"/> AnimateCSS </div>
  - <div class="flex items-center" ><img src="https://api.iconify.design/ic:outline-blur-on.svg" class="mr-2"/> Blurhash </div>
  - <div class="flex items-center" ><img src="https://iconify.design/favicon.ico" class="inline-block w-4 h-4 mr-2"/> Iconify </div>
  - <div class="flex items-center" ><img class="inline-block w-4 h-4 mr-2" src="https://bootstrap-flask.readthedocs.io/en/stable/_static/bootstrap-flask-favicon.png"/> BootstrapFlask </div>

</v-click>

<v-clicks>

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-60%">
<img src="https://images.tkzt.cn/blog/fwg-image-card.gif"/>
</div>

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-60%">
<img src="https://images.tkzt.cn/blog/fwg-blurha-intro.png" />
</div>

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-60%">
<img src="/assets/Snipaste_2024-07-20_20-36-07.jpg" />
</div>

</v-clicks>

<style>
h1 {
  background-color: #21D4FD;
  background-image: linear-gradient(45deg, #21D4FD 0%, #c373ea 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# 一些反馈

<v-clicks>

<div class="absolute top-50% left-50% translate--50%">
<img src="/assets/WX20240719-223517@2x.png"/>
</div>

<div class="absolute top-50% left-50% translate--50%">
<img src="/assets/WX20240719-223630@2x.png" />
</div>

<div class="absolute top-50% left-50% translate--50%">
<img src="/assets/WX20240719-223255@2x.png" />
</div>

</v-clicks>


<style>
h1 {
  background-color: #21D4FD;
  background-image: linear-gradient(45deg, #21D4FD 0%, #c373ea 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# 任务

<div class="absolute flex justify-center top-50% left-50% translate--50%">

- 详情模式增加翻页（Load More）<span class="inline-block py-.1 px-1 rounded-xl bg-green-100 text-xs text-gray-700">简单</span>
- 基于 [PythonAnywhere](https://www.pythonanywhere.com/) 和 [GitHub Pages](https://docs.github.com/zh/pages/getting-started-with-github-pages) 部署一个社区版 **Fine Weather** <span class="inline-block py-.1 px-1 rounded-xl bg-yellow-100 text-xs text-gray-700">中等</span>
  - 前者参考 [这里](https://github.com/tkzt/emoji-reaction/blob/main/.github/workflows/cd.yml)
  - 后者参考 [这里](https://tutorial.helloflask.com/deploy/)
- 添加 `Emoji Reaction` 组件，并可配置启用与否 <span class="inline-block py-.1 px-1 rounded-xl bg-yellow-100 text-xs text-gray-700">中等</span>
  - 需要在后台添加 Reaction 新增、删除、查看 相关接口
  - 具体可以参考 [这里](https://github.com/tkzt/fine-weather-gallery/blob/main/src/components/FineWeatherGalleryView.vue)

</div>

<style>
h1 {
  background-color: #21D4FD;
  background-image: linear-gradient(45deg, #21D4FD 0%, #c373ea 100%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# That's It

Thank you : )
