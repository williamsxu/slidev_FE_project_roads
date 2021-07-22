---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
background: './slidev_FE_project_roads/img/conver.jpeg'
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
download: true
layout: cover

info: |
  ## About
  ### 徐健
  ### 蜂泰科技--研发管理中心

---

# 大前端技术栈系列

-- -- 前端工程化之路

<div class="pt-12">
  <span class="px-2 p-1">
  蜂泰科技  |  徐 健
  </span>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: 'intro'
---

# 徐 健

<div class="leading-8 opacity-80">
<div class="flex "><svg width="24" height="24" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="48" height="48" fill="white" fill-opacity="0.01"/><path d="M48 0H0V48H48V0Z" fill="white" fill-opacity="0.01"/><path d="M41 18H19C18.4477 18 18 18.4477 18 19V41C18 41.5523 18.4477 42 19 42H41C41.5523 42 42 41.5523 42 41V19C42 18.4477 41.5523 18 41 18Z" fill="none" stroke="#333" stroke-width="4" stroke-linejoin="round"/><path d="M9.96906 6H6V10.0336" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M9.99705 30H6V26.012" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M26.0023 6H30V10.0152" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M16.0283 6H20.0083" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M6 16C6 18.6536 6 19.9869 6 20" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M30 16C30 18.6765 30 19.3456 30 18.0074" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M15.9927 30H18.0001" stroke="#333" stroke-width="4" stroke-linecap="round"/></svg><span class="mx-4">大前端工程师</span></div>
<div class='flex'><svg width="24" height="24" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="48" height="48" fill="white" fill-opacity="0.01"/><path fill-rule="evenodd" clip-rule="evenodd" d="M11 14L25 4V44H11V14Z" fill="none" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M25 13L39 23V44" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M4 44H44" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/></svg><span class="mx-4">研发管理中心架构组成员</span></div>
<div class='flex'><svg width="24" height="24" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="48" height="48" fill="white" fill-opacity="0.01"/><path d="M23.1033 20.817C23.4701 20.0737 24.5299 20.0737 24.8967 20.817L27.8818 26.8654C28.0275 27.1606 28.3091 27.3652 28.6348 27.4125L35.3096 28.3824C36.1298 28.5016 36.4574 29.5096 35.8638 30.0881L31.0339 34.7962C30.7982 35.0259 30.6906 35.3569 30.7463 35.6813L31.8865 42.3292C32.0266 43.1461 31.1691 43.769 30.4355 43.3834L24.4653 40.2446C24.174 40.0915 23.826 40.0915 23.5347 40.2446L17.5645 43.3834C16.8309 43.769 15.9734 43.1461 16.1135 42.3292L17.2537 35.6813C17.3094 35.3569 17.2018 35.0259 16.9661 34.7962L12.1362 30.0881C11.5426 29.5096 11.8702 28.5016 12.6904 28.3824L19.3652 27.4125C19.6909 27.3652 19.9725 27.1606 20.1182 26.8654L23.1033 20.817Z" fill="none" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M36 4H12V14L24 19L36 14V4Z" fill="none" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/></svg><span class="mx-4">超过8年客户端/前端研发经验</span></div>
</div>


<img src="/slidev_FE_project_roads/img/avatar.jpeg" class="rounded-full w-40 abs-tr mt-45 mr-30"/>

---

# 怎么看前端?

> 前端开发是创建WEB页面或APP等前端界面呈现给用户的过程，通过HTML，CSS及JavaScript以及衍生出来的各种技术、框架、解决方案，来实现互联网产品的用户界面交互。 —— 百度百科

前端技术演进历史：
<div class="grid grid-cols-5 gap-x-4">
<div>
<div class="mx-5" style="color:rgba(200,16,46,1)">

**上古时代**<br>
**1990 - 2004**
</div>
<div class="mx-4 sub-title">

* 静态页面
</div>
<div class="mx-4 sub-title">

* js诞生
</div>
<div class="mx-4 sub-title">

* 简单交互
</div>
</div>

<div>
<div class="mx-5" style="color:rgba(200,16,46,1)">

**web2.0时代**<br>
**2004 - 2008**
</div>
<div class="mx-4 sub-title">

* 交互需求增多
</div>
<div class="mx-4 sub-title">

* Ajax流行、异步请求
</div>
<div class="mx-4 sub-title">

* 典型:jQuery
</div>
</div>

<div>
<div class="mx-4" style="color:rgba(200,16,46,1)">

**发展大爆炸时代**<br>
**2008 - 2015**
</div>
<div class="mx-4 sub-title">

* V8引擎发布
</div>
<div class="mx-4 sub-title">

* Node.js爆发
</div>
<div class="mx-4 sub-title">

* MVVM/MVC<br>/SPA等类型应用
</div>
</div>

<div>
<div class="mx-5" style="color:rgba(200,16,46,1)">

**今天的前端**<br>
**2015 - 2020**
</div>
<div class="mx-4 sub-title">

* 小程序、跨容器、跨平台、跨OS等跨端
</div>
<div class="mx-4 sub-title">

* 包管理、构建、框架、混合等标准成熟
</div>
</div>

<div>
<div class="mx-5" style="color:rgba(200,16,46,1)">

**未来的前端**<br>
**2020 ~ ?**
</div>
<div class="mx-4 sub-title">

* 可视化
</div>
<div class="mx-4 sub-title">

* 智能化
</div>
<div class="mx-4 sub-title">

* 工具链
</div>
<div class="mx-4 sub-title">

* serverless
</div>
<div class="mx-4 sub-title">

* lowcode/nocode
</div>
<div class="mx-4 sub-title">

* WebAssembly
</div>
</div>

</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
.sub-title{
  color:#505759;line-height:33px;
}
</style>
<!--
前端的开发工作在一些场景下被认为只是日常的一项简单工作，或只是某个项目的"附属品"，并没有被当做一个"软件"而认真对待（无论是产品负责人还是开发者）。然而无论你如何对待它，也无法否定前端是一种 GUI 软件的事实，因此其也就必然遵循时间、质量、成本相互制约的特性。对于时间和成本的控制必然将导致最终产出倾向于出现"质量低"、"可维护性差"、"可用性差"等问题。过去我们以牺牲质量的方式换取时间和成本，现在趟了前辈们早已趟过的坑，然后发现还是要重新审视"前端"这一软件开发活动，并且使用软件工程这套早已存在的体系去对前端项目进行管理。
-->
---

# 工程化的意义?
> The only constant in the world is change.<br>
> 世界上唯一不变的是变化。——《谁动了我的奶酪》作者 斯宾塞·约翰逊

工程化之前遇到的问题：
<br>
- 最早的前端开发就是实现页面，顶多再写写JS让页面可以有交互的特效。
- 但是随着需求的增加，我们不仅要做Web应用，还要做App、小程序以及各种端。在这种需求日增的情况下，必须得考虑一种新的方式，优化前端的开发工作，
- 例如，解决代码冗余，项目可维护性，提升版本迭代速度等等一系列的问题。前端工程化的概念也就是在这中情况下被提出了。
<br>
<br>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
IT 行业变化太快了，尤其是前端开发（Frontend Development）。如果能穿越回 10 年前，碰上一位 Web 开发软件工程师，他一定会告诉你玩转前端就是精通 jQuery 和搞定 IE 浏览器兼容性。不过随着前端的不断发展，jQuery 遭遇 “官方逼死同人” 逐渐退出历史舞台（元素选择和操作被标准的 DOM API 所统一）；而饱为诟病的 IE 浏览器兼容性问题，因为 IE 市场的逐渐萎缩以及一些兼容性工具（Polyfill）的出现，让其从之前的核心优化问题降级为如今的瘙痒问题，不再成为前端工程师的标配。
虽然前端工程化的概念兴起还没几年的时间，但是对于“工程化”这个词并不是一个新鲜词了，在其他软件开发的领域很早就已经有了高度的工程化，例如Web服务端开发。只不过那个时候，前端工程师并没有工程化的意识，也没有必要对前端进行工程化的操作，毕竟在那个时期，前端的开发工作只能算是整个项目开发过程中的“附属品”。
-->

---

# 什么是前端工程化?
> 解放生产力、提高生产效率。通过制定相应的规范，借助一系列工具和手段解决整个工作流程中的痛点。

特点：
<div class="grid grid-cols-4 gap-x-4 gap-y-4 mt-4 mx-4">
<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
  <h1 class="title mb-16 text-bg">模块化</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">组件化</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">规范化</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">自动化</h1>
  </div>
</div>

</div>


以工程的角度去理解前端。工程是工程，而不是某项技术。

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
模块化

组件化

规范化

自动化

-->

---


# 前端工程化--模块化
> 模块化是指将一个文件拆分成多个相互依赖的文件，最后进行统一的打包和加载，这样能够很好的保证高效的多人协作。

<div class="grid grid-cols-2 gap-x-8">
  <img src="/slidev_FE_project_roads/img/node_module.png" class="rounded-xl w-60 mx-20"/>
  <img src="/slidev_FE_project_roads/img/webpack.png" class="mx-12 rounded-xl w-60"/>
</div>

- JS 模块化：CommonJS、AMD、CMD 以及 ES6 Module。
- CSS 模块化：Sass、Less、Stylus、BEM、CSS Modules 等。其中预处理器和 BEM 都会有的一个问题就是样式覆盖。而 CSS Modules 则是通过 JS 来管理依赖，最大化的结合了 JS 模块化和 CSS 生态，比如 Vue 中的 style scoped。
- 资源模块化：任何资源都能以模块的形式进行加载，目前大部分项目中的文件、CSS、图片等都能直接通过 JS 做统一的依赖关系处理。

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
<!-- <iframe src="https://nodejs.org/docs/latest/api/modules.html" width="900" height="200"></iframe> -->
-->

---

# 前端工程化--组件化
> 不同于模块化，模块化是对文件、对代码和资源拆分，而组件化则是对 UI 层面的拆分。

- 通常，我们会需要对页面进行拆分，将其拆分成一个一个的零件，然后分别去实现这一个个零件，最后再进行组装。 
- 在我们的实际业务开发中，对于组件的拆分我们需要做不同程度的考量，其中主要包括细粒度和通用性这两块的考虑。
- 对于业务组件，你更多需要考量的是针对你负责业务线的一个适用度，即你设计的业务组件是否成为你当前业务的 “通用” 组件。

<img src="/slidev_FE_project_roads/img/web-part.jpeg" class="mx-60 rounded-xl w-80"/>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 前端工程化--规范化

> 正所谓无规矩不成方圆，为了更好的协作和维护代码。在开发过程中会不断演进各种规范。

- 项目目录结构、命名规范;
- 编码规范：对于编码这块的约束，一般我们都会采用一些强制措施，比如 ESLint、StyleLint 等;
- 联调规范;
- 样式管理规范：目前流行的样式管理有 BEM、Sass、Less、Stylus、CSS Modules 等方式;
- git flow 工作流：其中包含分支命名规范、代码合并规范等;
- code review;

<img src="/slidev_FE_project_roads/img/flow.jpeg" class="mx-60 rounded-xl w-80"/>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 前端工程化--自动化

> 自动化合并、构建、打包能为我们节省很多工作。

- webpack/parcel/ESbuild;
- CI/CD;
- 容器;

<img src="/slidev_FE_project_roads/img/website-build.jpeg" class="mx-60 rounded-xl w-80"/>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 本次宣讲的目标

- 了解前端工程化；
- 掌握从0到1「愉快地」开发一个现代化web应用的能力；

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---

# 如何开始 
> Well begun is half done.<br>
> 好的开始，是成功的一半。 —— 贺拉斯

<div class="grid grid-cols-4 gap-x-4 gap-y-4 mt-16 mx-4">
<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
  <h1 class="title mb-16 text-bg">技术选型</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">开始工程</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">制造组件</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">生产构建</h1>
  </div>
</div>

</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---

# 技术选型

> 如何进行技术选型（VUE / REACT / ANGULAR / ...）?

|  | Angular | React | Vue |
| --- | --- | --- | --- |
| 发行时间 | 2010年 | 2013年 | 2014 |
| 开发方式 | TypeScript | 一切都是JavaScript的方式 | JavaScript/HTML/TypeScript |
| 模型 | Incremental DOM  | Virtual DOM | Virtual DOM |
| 学习曲线 | 陡峭 | 中等 | 平滑 |
| 性能 | 一般 | 高 | 高 |
| 复杂性 | 高 | 中 | 低 |
| 灵活性 | 低 | 中 | 高 |
| 适合场景 | 大规模、功能丰富的应用 | 现代Web渲染SPA应用 | 中小型Web SPA应用 |

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---

# 技术选型 - Incremental DOM
> 每个组件都被编译成一系列指令。这些指令创建 DOM 树并在数据更改时就地更新它们。

<div class="grid grid-cols-2 gap-x-4">
<div>

### 编写

```ts {4}
@Component({
  selector: 'todos-cmp',
  template: `
    <div *ngFor="let t of todos|async">
        {{t.description}}
    </div>
  `
})
class TodosComponent {
  todos: Observable<Todo[]> = this.store.pipe(select('todos'));
  constructor(private store: Store<AppState>) {}
}
```

</div>

<div>

### 编译后

```ts {10-15}
var TodosComponent = /** @class */ (function () {
  function TodosComponent(store) {/* store component */}
  TodosComponent.ngComponentDef = defineComponent({
    type: TodosComponent,
    selectors: [["todos-cmp"]],
    factory: function TodosComponent_Factory(t) {
      return new (t || TodosComponent)(directiveInject(Store));
    },consts: 2,vars: 3,
    template: function TodosComponent_Template(rf, ctx) {
      if (rf & 1) { // create dom
        pipe(1, "async");
        template(0, TodosComponent_div_Template_0, 2, 1, null, _c0);
      } if (rf & 2) { // update dom
        elementProperty(0, "ngForOf", bind(pipeBind1(1, 1, ctx.todos)));
      }
    },encapsulation: 2
  });
  return TodosComponent;
}());
```

</div>

</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
每个组件都被编译成一系列指令。这些指令创建 DOM 树并在数据更改时就地更新它们。模板函数包含渲染和更新 DOM 的指令。请注意，这些指令不会被框架的渲染引擎解释。它们是渲染引擎。为什么 Google 团队使用增量 DOM 而不是虚拟 DOM？他们有一个目标：应用程序必须在移动设备上运行良好。这主要意味着优化两件事：包大小和内存占用。如果视图树没有改动，那么刷新一次成本为0。因为视图树没有收到更新的指令不会从头开始渲染。
-->

---

# 技术选型 - Virtual DOM
> 每个组件每次重新渲染时都会根据需要创建和更新新的虚拟 DOM 树，然后对浏览器 DOM 应用一系列转换以匹配新的虚拟 DOM 树。

<div class="grid grid-cols-2 gap-x-4">
<div>
ORIGINAL DIV DOM
<img src="/slidev_FE_project_roads/img/dom.png" class="w-90"/>

Virtual DOM DIFF
<img src="/slidev_FE_project_roads/img/virtual_dom.png"/>
</div>
<div>
主要优点:

<div class='flex my-4'><img src="/slidev_FE_project_roads/img/check-circle.gif" class="w-10 h-10"/>
<span class="mx-4">对真实 DOM 进行抽象描述，除了核心属性外可以用来扩展，灵活性极强。甚至可以跨平台，渲染到DOM（web）之外的平台。比如ReactNative，Weex.</span>
</div>
<div class='flex'><img src="/slidev_FE_project_roads/img/check-circle.gif" class="w-10 h-10"/>
<span class="mx-4">拥有非常高的运行时性能，可以减少直接操作DOM，指定特定的组件进行重新渲染。避免整体更新DOM带来的高代价计算。</span>
</div>
</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
可以看到，真正的 DOM 元素是非常庞大的，因为浏览器的标准就把 DOM 设计的非常复杂。当我们频繁的去做 DOM 更新，会产生一定的性能问题。而 Virtual DOM 就是用一个原生的 JS 对象去描述一个 DOM 节点，所以它比创建一个 DOM 的代价要小很多。
虚拟 DOM 的真实意义不是他的性能，而是他提供了无限的可能，他是对 真实 DOM 的抽象，你可以用一门全新的语言写下代码，抽象为 虚拟 DOM，然后再通过社区其他成员编写完成的 虚拟 DOM 库，来转为各种平台（ios、android）的页面，只要有一个框架实现这个转换，其他框架都可以享受这个红利。
-->

---

# 技术选型 - React or Vue ?
> 我们当然选择渐进式JavaScript 框架。 -- 子可能曰过

<div class="grid grid-cols-3 gap-x-4 my-10">
<div>
<div class="my-1 mx-5" style="color:rgba(200,16,46,1)">历史因素</div>
<br>
<div class="my-1 mx-5" style="color:#505759;line-height:33px;">从Jquery时代过渡</div>
<div class="my-1 mx-5" style="color:#505759;line-height:33px;">学习曲线平滑</div>
</div>

<div>
<div class="my-1 mx-5" style="color:rgba(200,16,46,1)">性能优势</div>
<br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">数据驱动</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">灵活性</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">规模化向上/向下扩展</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">运行时性能</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">真香</span>
</div>

<div>
<div class="my-1 mx-5" style="color:rgba(200,16,46,1)">未来发展</div>
<br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">Github上升最快</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">专职团队维护</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">社区活跃性高</span><br>
<span class="my-1 mx-5" style="color:#505759;line-height:33px;">未来可期</span>
</div>

</div>

<div class="flex my-30">
<span style='color:#333;'>当然，如果现场有Angular用户，上面的当我没说。</span>
<svg width="24" height="24" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="48" height="48" fill="white" fill-opacity="0.01"/><path d="M24 44C35.0457 44 44 35.0457 44 24C44 12.9543 35.0457 4 24 4C12.9543 4 4 12.9543 4 24C4 35.0457 12.9543 44 24 44Z" fill="none" stroke="#333" stroke-width="4" stroke-linejoin="round"/><path d="M33 16L29 20L33 24" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><path d="M31 31C31 31 29 35 24 35C19 35 17 31 17 31" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/><circle cx="17" cy="20" r="4" fill="none" stroke="#333" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/></svg>
</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 初始化项目 - 初始化工程
> Talk is cheap. Show me the code.  —— Linus Torvalds

<br>
<br>

1. 使用脚手架 Vue Cli
```sh
npm install -g @vue/cli
```

2. 创建一个项目
```sh
vue create fintech-financeRecon-portal
```

<br>

* 当然，前提是需要有nodejs环境，npm包管理工具（国内使用npm缓慢，可以选用国内的「镜像源」）。

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 初始化项目 - 规范的开始
> convention over configuration  约定优于配置

* 规范工程结构
```sh
├── README.md		//说明文件
├── package.json	// 打包配置文件	 
├── src
│   ├── App.vue		// 应用入口
│   ├── api         // api 定义
│   ├── assets      // 素材文件
│   ├── components	// 自定义组件
│   │   ├── Charts
│   ├── config     // 应用内部设置
│   │   └── defaultSettings.js
│   ├── main.js    // js入口
│   ├── router.js  // 路由入口
│   ├── store      // 缓存配置
│   ├── utils      // 工具
│   │   ├── axios.js
│   │   └── utils.js
│   └── views      // 页面
│       ├── 404.vue
├── .env.dev      // 开发环境配置
├── .env.prod     // 生产环境配置
├── ...
```

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
约定优于配置（convention over configuration），也称作按约定编程，是一种软件设计范式，旨在减少软件开发人员需做决定的数量，获得简单的好处，而又不失灵活性。本质来说，系统、类库或框架应该假定合理的默认值，而非要求提供不必要的配置。比如说模型中有一个名为User的类，那么数据库中对应的表就会默认命名为user。只有在偏离这一个约定的时候，例如想要将该表命名为system_user，才需要写有关这个名字的配置。
-->

---

# 制造组件 - 组件的组织
> 不搞组件的前端不是个好前端。

<div class="grid grid-cols-2 gap-x-4">
<div>

* 组件的组织
<img src="/slidev_FE_project_roads/img/components.png" class="w-100"/>

<p>例如，你可能会有页头、侧边栏、内容区等组件，每个组件又包含了其它的像导航链接、博文之类的组件。</p>
<p>为了能在模板中使用，这些组件必须先注册以便 Vue 能够识别。可以进行<strong>全局注册</strong>和<strong>局部注册</strong>。</p>

</div>
<div>

* 简单举例：通用fintech后台管理系统结构
```sh
+---+---------------+
|   | hbTablePage   |
+---+---------------+
| M | search-bar    |
| E | action-bar    |
| N | data-table    |
| U |               |
+---+---------------+
```
</div>
</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 制造组件 - 组件的诞生1
> 前端组件化开发，将需要独立某个页面或者模块，以黑盒的形式全部封装到起来，提供对外暴露简便的入口来调用。

一个 table 示例 - 数据绑定
<div class="grid grid-cols-2 gap-x-4">
<div>

* pros属性配置初始化数据：
```js {7}
/* TablePage.vue */
props: {
    dataTable: {
      columns: [],
      rowKey: "",
    },
    dataListFun: {
      type: Function,
    },
  },
```

</div>
<div>

* 数据加载：
```js {3}
/* TablePage.vue */
loadData() {
  this.dataListFun(
    this.pagination.pageNum,
    this.pagination.pageSize,
    this.searchCondition
  ).then((res) => {
    if (res.code == RESULT_CODE.SUCCESS) {
      this.data = res.data.rows;
    }
  });
},
```
</div>
</div>
<div style="color:rgba(200,16,46,1)"> 注意点：</div>

- 所有的 prop 都使得其父子 prop 之间形成了一个单向下行绑定;每次父级组件发生变更时，子组件中所有的 prop 都将会刷新为最新的值。这意味着你不应该在一个子组件内部改变 prop。


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 制造组件 - 组件的诞生2
> 前端组件化开发，将需要独立某个页面或者模块，以黑盒的形式全部封装到起来，提供对外暴露简便的入口来调用。

一个 table 示例 - 事件绑定
<div class="grid grid-cols-2 gap-x-4">
<div>

* 传递绑定的事件：
```js {7}
/**
 * TablePage.vue
 * 列表选中一条数据事件
 * this.$emit('myEvent')
 */
onSelectChange(selectedRowKeys, selectedRows) {
  this.$emit('ON_SELECTED_DATA', this.selectedData);
}
```

</div>
<div>

* 事件监听：
```js {5}
/* Page.vue */
<template>
  <div>
    <hbTablePage
      @ON_SELECTED_DATA="onSelectedData"
    >
    </hbTablePage>
  </div>
</template>
```
</div>
</div>
<div style="color:rgba(200,16,46,1)"> 注意点：</div>

- 在有些情况下，我们可能需要对一个 prop 进行“双向绑定”。不幸的是，真正的双向绑定会带来维护上的问题;
- 这也是为什么我们推荐以 update:myPropName 的模式触发事件取而代之。


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 制造组件 - 组件的诞生3
> 前端组件化开发，将需要独立某个页面或者模块，以黑盒的形式全部封装到起来，提供对外暴露简便的入口来调用。

一个 table 示例 - 内容插槽
<div class="grid grid-cols-2 gap-x-4">
<div>

* 定义自由组合的灵活的内容插槽：
```js {2,3,6,6}
/* TablePage.vue */
<div v-if="$slots.searchBar">
  <slot name="searchBar"></slot>
  <a-divider dashed style="margin: 12px 0px" />
</div>
<div v-if="$slots.actionBar">
  <slot name="actionBar"></slot>
</div>
```

</div>
<div>

* 插槽填充：
```js {5,8}
/* Page.vue */
<template>
  <div>
    <hbTablePage>
      <template v-slot:searchBar>
        <hbTableSearchBar />
      </template>
      <template v-slot:actionBar>
        <hbTableActionBar />
      </template>
    </hbTablePage>
  </div>
</template>
```
</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 生产构建 - 按需加载
> 上线问题千千万，打包问题一大半。

<div class="grid grid-cols-2 gap-x-4">
<div>

* 路由加载
```js {2,7-8}
/* router.js 
* 异步加载*/
{
  path: '/userLogin',
  name: 'userLogin',
  component: resolve => require(['@/views/user/Login'], 
  resolve),
}
```
```js {2,7-9}
/* router.js 
* 懒加载*/
{
  path: '/userLogin',
  name: 'userLogin',
  component:() =>import(
  /* webpackChunkName: "userLogin" */ 
  '../views/userLogin.vue')
}
```

</div>

<div>

* 组件按需引入：
```js
/* babel-plugin-component
* .babelrc */
{
  "presets": [["es2015", { "modules": false }]],
  "plugins": [
    ["component",
        {"libraryName": "ant-design-vue",
        "styleLibraryName": "theme-chalk"}]
  ]
}
```
```js
/* main.js or page.vue */
import Vue from 'vue';
import { Button, message } from 'ant-design-vue';

Vue.use(Button);
Vue.prototype.$message = message;
```
</div>
</div>

* 当然，采用CDN（开源的https://cdn.jsdelivr.net/）、分割chunk包、模板预编译等也是常用的手段；

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--

-->

---

# 生产构建 - 压缩再压缩1
> 上线问题千千万，打包问题一大半。

<div class="grid grid-cols-2 gap-x-4">
<div>

* 图片压缩
```js
/* image-webpack-loader
* vue.config.js */
{
  test: /\.(png|jpe?g|gif|svg)(\?.*)?$/,
  use:[{
    loader: 'url-loader',
    options: {
      limit: 10000,
      name: utils.assetsPath('img/[name].[hash:7].[ext]')
      }
    },{
      loader: 'image-webpack-loader',
      options: {
        bypassOnDebug: true,
      }
    }]
}
```

</div>

<div>

* 提取公共代码：
```js
/* CommonsChunkPlugin
* vue.config.js 
* package.json 里依赖的包，都会被打包进 vendor.js 文件中 */
new webpack.optimize.CommonsChunkPlugin({
  name: 'vendor',
  minChunks: function(module, count) {
    return (
      module.resource &&
      /\.js$/.test(module.resource) &&
      module.resource.indexOf(
        path.join(__dirname, '../node_modules')
      ) === 0
    );
  }
}),
/* 抽取出代码模块的映射关系 */
new webpack.optimize.CommonsChunkPlugin({
  name: 'manifest',
  chunks: ['vendor']
})
```
</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
如果项目中没有去将每个页面的第三方库和公共模块提取出来，则项目会存在以下问题：

相同的资源被重复加载，浪费用户的流量和服务器的成本。
每个页面需要加载的资源太大，导致网页首屏加载缓慢，影响用户体验。

-->

---

# 生产构建 - 压缩再压缩2
> 上线问题千千万，打包问题一大半。

<div class="grid grid-cols-2 gap-x-4">
<div>

* 去除 ES6 转为 ES5 的冗余代码
```js
/* babel-plugin-transform-runtime
* .babelrc */
"plugins": [
    "transform-runtime"
]
```
- ### Babel 插件会在将 ES6 代码转换成 ES5 代码时会注入一些辅助函数，多次引用会造成多次重复生成。
- ### 通过require('babel-runtime/helpers/createClass') 的方式导入，做到只生成一次。

</div>

<div>

* gzip压缩：
```js
/* compression-webpack-plugin@5.0.1
* vue.config.js 
* 会打包生成.gz格式文件 */
const CompressionPlugin = require("compression-webpack-plugin");
configureWebpack: {
    plugins: [
      new CompressionPlugin({
        filename: "[path].gz",
        algorithm: "gzip",
        test: /\.js$|\.css$|\.html$/,
        threshold: 10240, // //压缩超过此大小的文件,以字节为单位
        minRatio: 0.8,
        deleteOriginalAssets: false
      })]
  }
```
```sh
/* nginx.conf 
* nginx开启gzip */
gzip  on;  #开启gzip
...
```
</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
如果项目中没有去将每个页面的第三方库和公共模块提取出来，则项目会存在以下问题：

相同的资源被重复加载，浪费用户的流量和服务器的成本。
每个页面需要加载的资源太大，导致网页首屏加载缓慢，影响用户体验。

-->

---

# 做个小结
> 来！该做个小结了！

<div grid="~ cols-2 gap-4">
<div>
<br>

* 至此，我们完成了最基础的从0到1的应用建造过程；

<br>

- 小结一下:
1. 通过vue cli初始化了一个工程；
2. 编写了一个「看起来简单的」组件；
3. 利用各种手段在生产环境中更加「顺畅的」加载;

<br>
<br>
<br>

更多VueJs的细节可以查看官网 [https://vuejs.org/](https://vuejs.org/).

</div>
<div>


</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# Where to Go From Here?
> 就这？是不是意犹未尽？<br>
> 技术栈系列接下来可能会讨论更多...

<div class="grid grid-cols-4 gap-x-4 gap-y-4 mt-4 mx-4">
<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
  <h1 class="title mb-16 text-bg">跨端技术</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">大前端的演进</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">性能指标</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">测试与安全</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">Flutter实战</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
    <h1 class="title mb-16 text-bg">前端智能化</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl inset-0 bg-gradient-to-r from-blue-400 to-green-200" style="display:flex;justify-content: center;align-items: center;">
      <h1 class="title mb-16 text-bg">可视化技术</h1>
  </div>
</div>

<div class="container mx-auto">
  <div class="w-40 h-40 rounded-2xl" style="display:flex;justify-content: center;align-items: center;">
    ......
  </div>
</div>

</div>


<style>
h1,h2 {
  background-color: #2B90B6;
  background-image: linear-gradient(30deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
.title {
    font-family: Montserrat,Georgia,Cambria;
    font-size: 1.2rem;
    line-height: 2rem;
    font-weight: 700;
    --tw-text-opacity: 1;
    color: rgba(31,41,55,var(--tw-text-opacity));
}
.text-bg {
    background-image: linear-gradient(0deg,rgba(153,255,213,.501961) 54%transparent 0,transparent);
    width: -webkit-fit-content;
    width: -moz-fit-content;
    width: fit-content;
}
</style>


---

# 总结与后续思考

- 前端工程化的特点是？
- 现代前端框架(reactjs、vuejs、angularjs)与jquery的明显区别是？
- 单页面（SPA）应用的优缺点？

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---


# 作业与答疑

- 从0初始化一个基于vuejs的web应用;
- 利用vuejs的特性定制一个日历组件；

<img src="/slidev_FE_project_roads/img/programmer.png" class="mx-60 rounded-xl w-100"/>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---
layout: center
class: text-center
---

# THANK YOU !
# 智造高质量的现代前端应用

## 蜂泰科技 ｜ 徐健

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 20%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

<!--
xxxx
-->

---
layout: center
class: text-center
---

# One More Thing

## 本次演示所用的代码基于：[https://sli.dev](https://sli.dev)

<style>
h1,h2 {
  background: linear-gradient(
141.27deg
,#ff904e -4.24%,#ff5982 21.25%,#ec68f4 44.33%,#79e2ff 83.46%);
background-size: 200%;
-webkit-background-clip: text;
background-clip: text;
-webkit-animation: gradient-data-v-fb6d3afe 10s ease infinite;
animation: gradient-data-v-fb6d3afe 10s ease infinite;
-webkit-text-fill-color: transparent;
}
</style>