

**效果图：**

<img src="http://images-of-blog.test.upcdn.net/images/jdfinance-page4.png" alt="页面图">

**手机扫码查看：**

<img src="http://images-of-blog.test.upcdn.net/images/jdfinance-show.png" width="200" height="200" alt="扫码查看" />


## 运行项目

```shell
    git clone https://github.com/lijq123/jdfinancetest.git
    cd jdfinancetest
    npm install （安装依赖）
    npm run start （运行项目）
    npm run build （生产构建）
```

## 目录结构

```

│  package.json
│  webpack.config.js（Webpack配置文件）
└─app
    ├─css
    │      element.scss（核心组件样式）
    │      layout.scss（布局样式）
    │      reset.scss（重置样式）
    ├─js
    │  │  App.vue（主组件）
    │  │  main.js（入口文件）
    │  │  test.vue
    │  │  viewport.js（移动端自适应）
    │  ├─core（核心组件）
    │  │      btn.vue（按钮）
    │  │      panel.vue（面板）
    │  │      slider.vue（轮播图）
    │  ├─home（主页）
    │  │      borrow.vue
    │  │      hslider.vue
    │  │      index.vue（每页都有的入口文件，引入当前页的其他组件）
    │  │      life.vue
    │  │      money.vue
    │  │      novice.vue
    │  │      product.vue
    │  ├─ious（白条页）
    │  ├─money（理财页）
    │  ├─my（我的页）
    │  ├─public（公共组件）
    │  │      footer.vue（copyright）
    │  │      header.vue（头部）
    │  │      navbar.vue（导航条）
    │  ├─raise（众筹页）
    │  ├─router（路由）
    │  │      index.js
    │  └─special
    │          download.vue（下载页）
    └─views
            index.html

```

## 构建环境

- Webpack 3.10.0
- npm scripts做任务管理

## CSS模块化设计

- 原则：可复用、能继承、要完整、周期性迭代
- 方法：先整体后部分再颗粒化、先抽象再具体

## JS模块化设计

- 原则：高内聚低耦合、周期性迭代
- 方法：先整体后部分再颗粒化、尽可能抽象

## 自适应方案

- 很据屏幕宽度、设备像素比设置html的font-size：[hotcss](https://github.com/imochen/hotcss)
- px自动转成rem：[px2rem-loader](https://github.com/Jinjiang/px2rem-loader)

## SPA设计

- history（pushState、onpopstate）
- hash（location.href、onhashchange）

