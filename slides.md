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

<div>

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

</div>

<style>
  div {
    font-size: 14px;
  }
</style>
---
transition: slide-up
layout: two-cols
---

# 注意事项

<div>

## 嵌入式

- 用cjson数据交互格式，统一采用parson.c文件移植，稍后会发群里
- 会有很多基础任务和拓展任务，需要合理地安排项目分配
- “项目组成员独立完成项目设计”，所以遇到问题要先查再问、多查减问，加强项目内部成员交流


## 硬件

- 最后统一以stm32rct6完成最终系统设计，所以吃资源分配，需要和嵌入式方面加强沟通
- 封装的使用建议依据stm32f103精英版的PCB封装库，LED、电阻、电容的封装使用0805。USB封装也按照精英版的。（重中之重）。
- 建议采用“立创EDA”设计板子（10cm*10cm以下大小可免费打板），如果实在感到困难，再考虑使用AD设计版图（需要耗费一定的钱）。
- 投板前建议将工程文件发给自己的硬件组长审核，避免错误。
- 芯片焊接存在相当难度，届时硬件组长会教授方法。

</div>

::right::

<br>
<br>
<br>
<div class="p-l-5">

## 网络
  - 前端: NodeJS、Fetch(或者axios)、Vue(或者React)
  - 后端: 查找 mqtt 协议内容、MySQL(或者MongoDB)
  - 多与嵌入式方向的同学交流，网络的东西不是学了就可以完成任务的，一定要多查资料
  - 前端学习资料: [mqtt](https://blog.plumbiu.club/2023/02/08/2023-2-8-mqtt%E5%8D%8F%E8%AE%AE%E5%AE%9E%E6%88%98/)、[nodejs-mqtt](https://blog.plumbiu.club/2023/02/08/2023-2-8-%E4%BD%BF%E7%94%A8nodejs%E6%90%AD%E5%BB%BAmqtt/)
  - 后端学习资料: [golang](https://blog.csdn.net/emqx_broker/article/details/108748657)、[java](https://blog.csdn.net/emqx_broker/article/details/126605202)
  
</div>

<style>
  div {
    font-size: 13px;
  }
</style>
---
transition: slide-up
---

