开发资源总结 (持续整理中)
===============

这是对自己这几年开发的一个总结，各种项目、资源、书籍、博客等

## Web 前端

#### Javascript

+ [parallel.js](https://github.com/adambom/parallel.js): 前后端通用的一个并行库
+ [zepto](https://github.com/madrobby/zepto): 用于现代浏览器的兼容 jQuery 的库
+ [totoro](https://github.com/totorojs/totoro): 稳定的跨浏览器测试工具
+ [TheaterJS](https://github.com/Zhouzi/TheaterJS): 一个用于模拟人输入状态的 JS 库
+ [stellar.js](https://github.com/markdalgleish/stellar.js): 前端用于实现异步滚动效果的库，现已不再维护
+ [skrollr](https://github.com/Prinzhorn/skrollr): 另一款实现一步滚动的开源库，使用人数众多，可实现各种狂拽酷炫掉渣天的前端效果，[看真相](http://prinzhorn.github.io/skrollr/)
+ [Framework7](https://github.com/nolimits4web/Framework7): 前端框架，是开发人员可以基于 web 技术构建 IOS7 程序
+ [regulex](https://github.com/JexCheng/regulex): 用于生成 正则表达式 的可视化流程图
+ [markdown-it](https://github.com/markdown-it/markdown-it): 新型 Markdown 解析器，快速，支持插件
+ [multiline](https://github.com/sindresorhus/multiline): 用于 Javascript 中的多行文本，类似于 Ruby 的 HERE Doc
+ [screenfull.js](https://github.com/sindresorhus/screenfull.js): 全屏插件，支持各大浏览器
+ [lunr.js](https://github.com/olivernn/lunr.js): 类似于 Solr, 但是用于浏览器上的全文搜索引擎，可以为 JSON 创建索引，离线也可以使用

###### HTML5 相关

+ [sensor.js](https://github.com/branding-fe/sensor): 在智能移动设备浏览器上，通过HTML5的api使用移动设备的功能。定位、运动、倾斜等
+ [hyhyhy](https://github.com/maciejczyzewski/hyhyhy): 用于创建 基于 HTML5 的 演示文稿
+ [swipebox](https://github.com/brutaldesign/swipebox): jQuery 插件，用于处理移动端的触摸事件
+ [FileAPI](https://github.com/mailru/FileAPI): 前端用户处理文件（拖放、多文件上传等）
+ [Sortable](https://github.com/RubaXa/Sortable): 现代浏览器上用于实现元素拖拽排序的功能，支持 Meteor, AngularJS, React，不依赖 jQuery
+ [Swiper](https://github.com/nolimits4web/Swiper): 用于实现浏览器上的滑动切换效果，支持硬件加速
+ [matter-js](https://github.com/liabru/matter-js): 2D 物理效果引擎，碰撞、弹跳等
+ [jQTouch](https://github.com/senchalabs/jQTouch): 用于辅助创建手机端的 Web 应用，支持主题、Zepto.js 等

###### AngularJS

+ [angular-masonry](https://github.com/passy/angular-masonry): Masonry 的 AngularJS 插件，用于瀑布流
+ [angular-schema-form](https://github.com/Textalk/angular-schema-form): 根据 JSON 生成响应的 Form 表单
+ [restangular](https://github.com/mgonto/restangular): Angular 中用来处理 RESTful API 的插件，可替代 $resource
+ [ng-cordova](https://github.com/driftyco/ng-cordova): Cordova 常用组件的 Angular 版本
+ [angular-translate](https://github.com/angular-translate/angular-translate): Angular 的国际化 (I18n)

#### CSS

+ [Hover](https://github.com/IanLunn/Hover): 基于 CSS3 的各种 鼠标悬停(hover)特效, [点击查看效果](http://ianlunn.github.io/Hover/)
+ [icono](https://github.com/saeedalipoor/icono): 一款用纯 CSS 实现的图标库

## Web 后端

#### Ruby

+ [ruby](https://github.com/ruby/ruby): Ruby 源代码
+ [spyke](https://github.com/balvig/spyke): 像使用 ActiveRecord 一样使用 RESTful API 
+ [reactive_record](https://github.com/twopoint718/reactive_record): 根据 ActiveRecord 的 数据库 Schema 来反向生成 Model
+ [eventmachine](https://github.com/eventmachine/eventmachine): Ruby 中著名的事件驱动库
+ [faker](https://github.com/stympy/faker): Perl 的 Data::Faker 库的一个 Ruby 实现，用于虚拟各种类型的数据


#### Python

+ [django](https://github.com/django/django): 一个全栈式的 web 框架, 类似于 Rails

#### PHP
#### NodeJS

+ [Node-Webkit.js](https://github.com/nwjs/nw.js): Node-Webkit 是基于Chromium 和 node.js的运行环境，可以用来创建桌面应用程序
+ [request](https://github.com/request/request): 基于 Node.js 的用于网络请求的库，使用简单，功能强大
+ [hapi](https://github.com/hapijs/hapi): 一个配置优先的 web 框架，[hapijs.com](http://hapijs.com/)
+ [psi](https://github.com/addyosmani/psi): 用于分析页面速度的工具，支持命令行
+ [gulp](https://github.com/gulpjs/gulp): 基于 Node.js 的流式构建系统
+ [orchestrator](https://github.com/orchestrator/orchestrator): 一个可以并行执行任务和依赖的库
+ [johnny-five](https://github.com/rwaldron/johnny-five): 用 Javascript 控制机器人
+ [popcorn-js](https://github.com/mozilla/popcorn-js): Mozilla 的一个开源项目，允许开发者基于 HTML5 音视频的时间线添加互动元素，比如注释，字幕，甚至动画
+ [connect](https://github.com/senchalabs/connect): Node 中间件支持，注：Express 4 以下依赖此库，从 4 开始支持全新的 Router，类似于 Rails Engine
+ [faker.js](https://github.com/Marak/faker.js): Faker 的 Node 实现，用于生成假数据
+ [chart](https://github.com/jstrace/chart): 用于终端生成 ASCII 图表
+ [drawille](https://github.com/asciimoo/drawille): 用于终端生成 ASCII 图形
+ [sparkly](https://github.com/sindresorhus/sparkly): spark.sh 的一个 Javascript 实现，终端生成 sparklines
+ [node-inspector](https://github.com/node-inspector/node-inspector): Node 的调试神器，使用方法，用 `node-debug` 代替 `node` 启动服务，并在你想调试的地方输入 `debugger`
+ [NodeOS](https://github.com/NodeOS/NodeOS): 基于 Node 的操作系统
+ [js-git](https://github.com/creationix/js-git): Git 的 Javascript 实现
+ [pdfkit](https://github.com/devongovett/pdfkit): Node 和 浏览器均可以使用的，用于生成 PDF 的库
+ [empty-trash](https://github.com/sindresorhus/empty-trash): 清空垃圾桶
+ [trash](https://github.com/sindresorhus/trash): 安全删除文件 -> 将文件放入垃圾桶
+ [rabbit.js](https://github.com/squaremo/rabbit.js): RabbitMQ 的 Node 客户端
+ [htmlbars](https://github.com/tildeio/htmlbars): 基于 Handlebars 的一个变种，可以编写直接操作 DOM 的辅助方法

###### Express

+ [express-admin](https://github.com/simov/express-admin): Express 的后端，支持(MySQL, MariaDB, SQLite, PostgreSQL)
+ [grant](https://github.com/simov/grant): Express 认证中间件(middleware)

#### Erlang
#### Java

## IOS 或 OSX

+ [Harpy](https://github.com/ArtSabintsev/Harpy): 用于检测应用更新
+ [CRToast](https://github.com/cruffenach/CRToast): 现代、时髦的 IOS 通知提醒库
+ [Ono](https://github.com/mattt/Ono): IOS 或者 OSX 中用于处理 XML & HTML 的库
+ [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown): IOS 或者 OSX 中用于解析或者渲染 Markdown 的库
+ [Haneke](https://github.com/Haneke/Haneke): 一个用于缓存图片的 IOS 库，无需配置
+ [HanekeSwift](https://github.com/Haneke/HanekeSwift): Haneke 的 swift 版本
+ [RFQuiltLayout](https://github.com/bryceredd/RFQuiltLayout): 一个用于实现 IOS 端瀑布流的库
+ [kxmenu](https://github.com/kolyvan/kxmenu): 用于 IOS 上实现垂直菜单，支持上下左右等方向
+ [peertalk](https://github.com/rsms/peertalk): IOS 或者 OSX 中用于处理 USB 通信
+ [REMenu](https://github.com/romaonthego/REMenu): IOS 中用于实现下拉菜单效果
+ [RESideMenu](https://github.com/romaonthego/RESideMenu): IOS 中侧边栏的异步效果实现，类似于 QQ 中的侧边栏
+ [AwesomeMenu](https://github.com/levey/AwesomeMenu): IOS 中用于实现类似于 Path 应用菜单的效果，各种酷炫

## Android

+ [Slidr](https://github.com/r0adkll/Slidr): 一个用于给 Activity 添加滑动消隐效果的库

## 代码效率

#### CoffeeScript

#### TypeScript

+ [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped): 高质量的 TypeScript 资源汇总

#### Sublime Text

+ [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel): Sublime Text 的代码补全工具，支持多种语言

## 云计算

#### Docker

+ [kubernetes](https://github.com/GoogleCloudPlatform/kubernetes): Google 开源的 Docker 集中管控系统
+ [weave](https://github.com/zettio/weave): 用于为基于不同主机的 Docker Containers 创建一个虚拟网络

#### OS

+ [smartos-live](https://github.com/joyent/smartos-live): Joyent 出品的用于云平台的智能 OS

## 开源产品(论坛、在线教育、项目管理等)

+ [Edx](https://github.com/edx/edx-platform): 在线教育平台源代码，Edx

## Awesome 系列

+ [awesome](https://github.com/sindresorhus/awesome): awesome 汇总
+ [iOS 学习资料整理](https://github.com/Aufree/trip-to-iOS): IOS 的各种学习资料整理，初学者必备

## 代码规范&设计模式

#### Ruby

+ [Airbnb 的 ruby 代码编写规范](https://github.com/airbnb/ruby): Airbnb 的 ruby 代码编写规范

###### Rails

+ [Rails 代码编写规范](https://github.com/bbatsov/rails-style-guide): Rails 代码编写规范

#### Java

+ [java-design-patterns](https://github.com/iluwatar/java-design-patterns): Java 设计模式

## 其他

+ [retter](https://github.com/maciejczyzewski/retter): 密码学相关的算法库
+ [what-happens-when](https://github.com/alex/what-happens-when): 一篇文章，详细解释了从在浏览器中输入网址之后发生的一切
+ [ShadowVPN](https://github.com/clowwindy/ShadowVPN): 科学上网之 VPN
+ [gfwlist2pac](https://github.com/clowwindy/gfwlist2pac): 科学上网之 GFWlist to Pac
+ [uBlock](https://github.com/gorhill/uBlock): Chrome, Firefox, Safari 插件用来屏蔽内容（如广告等），可自定义
+ [Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions): 各种前端面试问题
+ [rust](https://github.com/rust-lang/rust): Rust 语言源码
