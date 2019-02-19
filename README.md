# z4  打卡项目

> A Vue.js project




#### 前端使用的是vue +ElementUI +ydui

### 技术栈
##### ydui 
##### vue-upload-component
##### echarts
##### vue-router
##### axios

### 技术说明
#### axios进行请求/响应拦截token判断是否登陆，否则跳转登陆页面，因为逻辑简单该项目未用到vuex
#### 采用ydui进行下拉加载，vue-upload-component进行图片上传

##### 登陆/登陆成功页面
<br>
<p>
  <img src="./gif/login.png" >
  <img src="./gif/loginSucc.png" >
</p>

##### 注册页面
<br>
<p>
	<img src="./gif/register.png" >
</p>

##### 首页
<br>
<p>
	<img src="./gif/shouye.png" >
</p>

##### 排名/打卡页面
<br>
<p>
	<img src="./gif/paixun.png" >
 	<img src="./gif/peisu.png" >
</p>

##### 个人信息/个人信息修改
<br>
<p>
	<img src="./gif/personInfo.png" >
 	<img src="./gif/editor.png" >
</p>

<br>
<strong>......</strong>
<br>

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).



## File Structure
```
.
├─build
│      build.js
│      check-versions.js
│      logo.png
│      utils.js
│      vue-loader.conf.js
│      webpack.base.conf.js
│      webpack.dev.conf.js
│      webpack.prod.conf.js
│      
├─config
│      dev.env.js
│      index.js
│      prod.env.js
│      test.env.js
│      
├─dist
│  │  index.html
│  │  
│  └─static
│      ├─css
│      │      
│      ├─fonts
│      │  │  
│      │  └─font_oz6v4lx6byl7syvi
│      │          
│      ├─icon
│      │      iconfont.css
│      │      iconfont.eot
│      │      iconfont.js
│      │      iconfont.svg
│      │      iconfont.ttf
│      │      iconfont.woff
│      │      
│      ├─image
│      │      
│      ├─img
│      │      
│      └─js
│              app.d97b0877576b2e11fdeb.js
│              app.d97b0877576b2e11fdeb.js.map
│              index.js
│              index1.js
│              manifest.2ae2e69a05c33dfc65f8.js
│              manifest.2ae2e69a05c33dfc65f8.js.map
│              vendor.e02478e8395c5e095a26.js
│              vendor.e02478e8395c5e095a26.js.map
│              
├─gif
│      editor.png
│      login.png
│      loginSucc.png
│      paixun.png
│      peisu.png
│      personInfo.png
│      register.png
│      shouye.png
│      
├─src
│  │  App.vue
│  │  main.js
│  │  
│  ├─api
│  │      clock_in.js
│  │      home.js
│  │      http.js
│  │      stat.js
│  │      update_user.js
│  │      user.js
│  │      xinxi.js
│  │      
│  ├─assets
│  │      logo.png
│  │      
│  ├─components
│  │      article.vue
│  │      clockin.vue
│  │      ClockInList.vue
│  │      header.vue
│  │      index.vue
│  │      Nav.vue
│  │      Swiper.vue
│  │      timeLine.vue
│  │      
│  ├─config
│  │      index.js
│  │      
│  ├─router
│  │      index.js
│  │      
│  └─view
│          clockview.vue
│          daka.vue
│          gerenxinxi.vue
│          index.vue
│          login.vue
│          Rank.vue
│          register.vue
│          Stat.vue
│          users.vue
│          
├─static
│  │  .gitkeep
│  │  
│  ├─fonts
│  │  └─font_oz6v4lx6byl7syvi
│  │          demo.css
│  │          demo_fontclass.html
│  │          demo_symbol.html
│  │          demo_unicode.html
│  │          iconfont.css
│  │          iconfont.eot
│  │          iconfont.js
│  │          iconfont.svg
│  │          iconfont.ttf
│  │          iconfont.woff
│  │          
│  ├─icon
│  │      iconfont.css
│  │      iconfont.eot
│  │      iconfont.js
│  │      iconfont.svg
│  │      iconfont.ttf
│  │      iconfont.woff
│  │      
│  ├─image
│  │      01-4.jpg
│  │      1.jpg
│  │      122.jpg
│  │      2.jpg
│  │      3.jpg
│  │      3215648965.jpg
│  │      4.jpg
│  │      5.jpg
│  │      534654654.jpg
│  │      bg.jpg
│  │      bs-docs-masthead-pattern.png
│  │      default.jpg
│  │      icon02.jpg
│  │      icon1.jpg
│  │      ifle.jpg
│  │      moren.jpg
│  │      xtb.jpg
│  │      xxx.jpg
│  │      
│  └─js
│          index.js
│          index1.js
│          
└─test
    ├─e2e
    │  │  nightwatch.conf.js
    │  │  runner.js
    │  │  
    │  ├─custom-assertions
    │  │      elementCount.js
    │  │      
    │  └─specs
    │          test.js
    │          
    └─unit
        │  .eslintrc
        │  jest.conf.js
        │  setup.js
        │  
        └─specs
                HelloWorld.spec.js
