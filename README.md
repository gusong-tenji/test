# 基于Vue2.0+Vuex+Axios+NodeJs+Express+MySQL??京?移?web商城
- ??一个多月?算完成第一个版本
## 前端架?
- ?面??(H5,CSS3,原生JS)
- 框架(基于Vue脚手架:vue-cli)?行搭建
- 数据?求?理框架(Axios)
- Vue-Router?行路由?理
- Vue-LazyLoad?行?片?加?

## 服?端架?
- ?用NodeJs?行后台??
- Express中?件?行服?的配置，路由、?求的?理
	- 官网 [http://www.expressjs.com.cn/](http://www.expressjs.com.cn/ "express官网")
- Mysql中?件?理与数据?的"通信"
- Body-Parser中?件?行前端?求参数的?取
- Cookie-Parser、Cookie-Session?行cookie与session的?理


## 数据??取
- 采用MySQL?行相?数据?的??与??

## 目前?目已??功能
1. 首?数据的展示
2. 分??数据的展示
3. ?物?
4. 我的
5. 注册
6. 登?
7. 商品?情?
8. 商品搜索


## 安装

已安装MySQL数据?，然后?入migou.sql文件

然后通?`npm`安装本地服?第三方依?模?(需要已安装[Node.js](https://nodejs.org/))

```
cd vue-jd
```

```
npm install 或 cnpm install(个人比?喜?使用后者，下?依?模?速度?快)
```

```
npm run dev
```

最后??后台服?

```
node server.js
```

## 目???
<pre>
.
├── README.md           
├── libs               		// 后台常用工具模?的封装，比如格式化事件、MD5加密等
├── route              		// 后台接口的?写目?
├── server.js          		// 后台服?的配置文件
├── webpack.config.js  		// webpack配置文件
├── index.html         		// ?目入口文件
├── package.json       		// ?目配置文件
├── src                		// 生?目?
│?? ├── assets         		// css js 和?片?源
│?? ├── components     		// 各?Vue?件
│?? ├── store          		// vuex状?管理器
│?? ├── App.vue        		// ?目中全局Vue
│?? ├── main.js        		// Webpack ???入口
│?? └── router.config.js    // vue路由配置文件
</pre>

## ?目效果?


![](http://i.imgur.com/hc4Kdcv.png)

![](http://i.imgur.com/e1dli1Y.png)

![](http://i.imgur.com/j9bdh5O.png)

![](http://i.imgur.com/KNlLcjv.png)

![](http://i.imgur.com/m2H0mLg.png)

![](http://i.imgur.com/8GpE1qc.png)

![](http://i.imgur.com/sIfHd0z.png)


....未完待? QQ交流群:526450553已??，大家可以叫我个人QQ：386271623，拉大家?微信群

"# test" 
