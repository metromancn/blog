---

title: MAC上Hexo+GitHub搭建博客

date: 2016-02-10 14:47:26

tags: 学习

---

### 安装
* 安装 [Node.js](https://nodejs.org/en/)
* 安装 [Git](http://git-scm.com/)
* 安装 [Hexo](https://hexo.io/zh-cn/docs/index.html)

``` bash
$ npm install -g hexo-cli
```
### 建站

``` bash
$ hexo init <folder>
$ cd <folder>
$ npm install  
```

启动服务器

``` bash
$ hexo server
```

访问网址：[http://localhost:4000/](ttp://localhost:4000/)

生成静态网站

``` bash
$ hexo generate
```

### GitHub
* 注册账号 如：[metromancn](https://github.com/metromancn)
* 新建同名仓库 如：[metromancn.github.io](https://pages.github.com/)
* 安装 [GitHub Desktop](https://desktop.github.com/)
* 提交上面生成的静态网站
* 访问网站 [metromancn.github.io](http://metromancn.github.io/)

### 配置

### 基本操作
* 写作

``` bash
$ hexo new "title"
```
