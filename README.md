vue-music
---
> 使用vue2.0构建音乐播放器


组件划分
---

**基础组件**

- confirm 确认对话框组件
- listview 通讯录列表组件
- loading 加载态组件
- no-result 无结果展示页面
- progress-bar 进度条组件
- progress-circle 圆形进度条组件
- scroll 移动端滚动组件
- search-box 搜索框组件
- search-list 搜索列表组件
- slider 轮播图组件
- switches 开关切换组件
- top-list 顶部消息提示组件
- song-list 歌曲列表组件

**业务组件**

- add-song 添加歌曲列表到组件
- disc 歌单详情页组件
- m-header 页面头部组件
- music-list 歌曲列表页面组件
- player 播放器内核组件
- playlist 播放列表组件
- rank 排行榜页面组件
- recommend 推荐页面组件
- search 搜索页面组件
- singer 歌手页面组件
- singer-detail 歌手详情页组件
- suggest 搜索提示列表组件
- tab 顶部导航栏组件
- top-list 排行榜详情页组件
- user-center 用户中心也组件



技术栈
---
[前端]
- Vue：vue.js(2.0)
- Vuex：Vue集中状态管理，在多个组件共享数据
- Vue Router：为单页面应用提供的路由系统
- vue-lazyload：第三方图片懒加载库，优化页面加载速度
- better-scroll：移动端滑动体验更加流畅
- ES6：ECMAScript 新一代语法，模块化、解构赋值、Promise、Class 等方法
- stylus：css 预编译处理器

[后端]
- Node.js：在本地测试启动服务器(利用了Express,具体底层就不是太了解了...)
- axios ：官方推荐服务端通讯工具, 结合了node.js代理后端请求(再也不用跟后台大佬们说跨域的问题了...)

[自动化构建及其他工具]
- webpack: 项目的编译打包(目前还只是会模板中的webpack)
- vue-cli: Vue 官方脚手架工具
- eslint: 代码风格检查工具(在实际项目当中即使你开了eslint,也有个别队友神助攻自行关闭eslint,然后你就满世界的去找问题去吧...)




收获
---
其实收获还是很大的,跟着黄老师的课程来撸代码,不光学习到了vue的api,vuex数据更新,也学习到了平时开发工作的一些小技巧。在这里上传代码只是想练习一下git工具,如有不便请及时联系我




使用方法
---

```
git clone https://github.com/Fdango/vue-music.git

# 进入根目录
cd vue-music

# 安装依赖
npm install

# 开发
npm run dev

# 构建
npm run build
```


License
---

© 2017 A poetries's [Ideas](https://github.com/poetries/ideas).

