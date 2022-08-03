# admxn 一个可以离线使用的PC浏览器主页
> 原版是以移动端为主的H5仿夸克浏览器主页 https://github.com/liumingye/quarkHomePage  
> 改版以PC端为主，做为一个可本地化离线使用的直观便捷的浏览器主页  
> **如下载后放到D盘运行index.html并设置为浏览器主页即可**  

## 计划
* 左侧搜索33.33% 右侧导航66.77%
* 左侧部分搜索结果右侧框架/ajax执行
* 右侧部分工具/api在左侧或右侧框架/ajax执行
* 用颜色或者图标区分（如某些工具在框架内打开更为便捷）


## 记录
### 2022年8月1日
touchstart事件不兼容PC，改click事件；  
添加多个cursor:pointer；  
快搜补全购物url；  
部分location.href改为window.open(url)新窗打开；  
新增鼠标右击菜单,惯用右击设置；  

## 感谢开源项目
* jquery
* sortablejs
* Swiper
* TouchSwipe
* requirejs
