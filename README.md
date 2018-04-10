# Feed reader
feed reader 抓取不同网站的文章内容，在页面最底部显示测试结果。

## 使用说明
1. 使用浏览器打开根目录下的`index.html`文件；
2. 点击左上角的按钮，弹出网站列表;
3. 通过点击网站，会抓取相关网站的文章，并以列表加文章标题的形式呈现;
4. 点击文章标题跳转到文章详细页面浏览。

## 结构说明
* css/[style.css](https://github.com/SoleGH/frontend-nanodegree-feedreader/blob/master/css/style.css):css样式；
* [index.html](https://github.com/SoleGH/frontend-nanodegree-feedreader/blob/master/index.html):页面呈现和导入相关js文件；
* js/[app.js](https://github.com/SoleGH/frontend-nanodegree-feedreader/blob/master/js/app.js):主逻辑；
* jasmine/spec/[feedreader.js](https://github.com/SoleGH/frontend-nanodegree-feedreader/blob/master/jasmine/spec/feedreader.js):测试逻辑。

## 测试功能：
1. 校验`allFeeds`是否定义，并且长度不为零；
2. 校验`allFeeds`各元素是否定义**key**`name`和`url`,且对应值长度不为零；
3. 校验导航菜单`menu`是否默认隐藏；
4. 点击`menu icon`时，改变导航栏可见性；
5. 测试初始化异步加载`loadFead()`；
6. 测试当新的项目被选中时，更新`content`。


