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

代码厨房开源松 Sprint 6

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

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-full">
<img src="https://images.tkzt.cn/blog/fwg-image-card.gif" class="rounded-lg shadow-2xl"/>
</div>

<div class="absolute top-0 right-0 h-full flex items-center justify-center w-full">
<img src="https://images.tkzt.cn/blog/fwg-blurha-intro.png" class="rounded-lg shadow-2xl w-94%"/>
</div>

<ManagerClickJump />

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
<img src="/assets/WX20240719-223517@2x.png" class="rounded-lg shadow-2xl"/>
</div>

<div class="absolute top-50% left-50% translate--50%">
<img src="/assets/WX20240719-223630@2x.png" class="rounded-lg shadow-2xl"/>
</div>

<div class="absolute top-50% left-50% translate--50%">
<img src="/assets/WX20240719-223255@2x.png" class="rounded-lg shadow-2xl"/>
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

<div class="w-full absolute flex justify-center top-50% left-50% translate--50%">

<v-switch>
<template #1>

- 相册程序
  - <TaskNo>1</TaskNo> 设定没有照片时的展示状态 <LevelBadge />
  - <TaskNo>2</TaskNo> 图片详情页面没有地点和时间时隐藏对应的图标 <LevelBadge />

</template>
<template #2>

- 后台管理
  - <TaskNo>3</TaskNo> 添加相册设置页面 <LevelBadge />
    - <TaskNo>4</TaskNo> 支持自定义首页介绍和标题 <LevelBadge />
    - <TaskNo>5</TaskNo> 支持自定义页面标题 <LevelBadge />
    - <TaskNo>6</TaskNo> 支持自定义图片无描述的展示信息 <LevelBadge />
    - <TaskNo>7</TaskNo> 支持设置不同颜色主题 <LevelBadge level="m"/>
  - <TaskNo>8</TaskNo> 优化图片上传表单 <LevelBadge />
    - 每行显示一个输入框
    - 描述使用多行输入框
    - 时间选择使用标准组件
  - <TaskNo>9</TaskNo> 用户管理 <LevelBadge />
    - <TaskNo>10</TaskNo> 用户管理页面
    - <TaskNo>11</TaskNo> 用户注册和批准（激活）
    - <TaskNo>12</TaskNo> 用户权限控制 <LevelBadge level="m"/>

</template>
<template #3>

- 文档
  - <TaskNo>13</TaskNo> 添加文档框架 <LevelBadge level="m"/>
  - 创建文档
    - <TaskNo>14</TaskNo> 中文部署文档 <LevelBadge />
    - 英文部署文档
    - <TaskNo>15</TaskNo> 中文使用文档 <LevelBadge />
    - 英文使用文档
    - <TaskNo>16</TaskNo> 创建设计文档（架构图）<LevelBadge level="m"/>

</template>
</v-switch>

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
