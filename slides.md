---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## 孵化器四轮考核PPT
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# 孵化器实验室

四轮考核

---
transition: fade-out
---

# 分组、时间安排

- 🥰 **时间** - 六周左右(期中考试之前验收)，在第三周的时候会有个中期检查，需要答辩
- 😇 **分组情况**

    | 组别 |                 成员                 |                 组长                 |
    | :--: | :----------------------------------: | :----------------------------------: |
    |  1   | 肖靖宇、张一凡、王雨浩、邵藤、张佳音 |     邓—凡、马科科、沈昕、郭兴俊      |
    |  2   | 张露玉、吴烊年、卢杰、张艳红、付泓松 |       戴俊、敬埔、张铭、邵俊腾       |
    |  3   | 冯稼焕、程鼎、施韵芝、金仪杰、陈科溯 |      戴俊、郑喆、暨欣怡、周锦馨      |
    |  4   | 王锦波、李明睿、王欣怡、田晗、周书昊 | 陈国强、肖扬、罗润阳、朱海鹏、周子茹 |
    
- 😋 **项目概况**
    
    工厂运输小车、腰带护老装置、智慧农业系统、智能卡片管理系统

---
transition: slide-up
layout: two-cols
---

# 注意事项

## 嵌入式

- 用cjson数据交互格式，统一采用parson.c文件移植，稍后会发群里

- 会有很多基础任务和拓展任务，需要合理地安排项目分配

- “项目组成员独立完成项目设计”，所以遇到问题要先查再问、多查减问，加强项目内部成员交流

## 硬件

- 最后统一以stm32rct6完成最终系统设计，所以吃资源分配，需要和嵌入式方面加强沟通

::right::

<br>
<br>
<div class="p-l-5">

  ## 网络
  - 必备：NodeJS、Fetch(或者axios)
  - 进阶：Vue、React
  - 多与嵌入式方向的同学交流，网络的东西不是学了就可以完成任务的，一定要多查资料
  - [神秘链接1](https://blog.plumbiu.club/2023/02/08/2023-2-8-mqtt%E5%8D%8F%E8%AE%AE%E5%AE%9E%E6%88%98/)、[神秘链接2](https://blog.plumbiu.club/2023/02/08/2023-2-8-%E4%BD%BF%E7%94%A8nodejs%E6%90%AD%E5%BB%BAmqtt/)
  
</div>
