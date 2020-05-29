# 云极客工具の开发博客

## 写在前面

这篇博客记录我是如何开发 [ygktool](https://www.ygktool.cn) 的。

### 缘起

大概是19年7月份的时候，那时我已经厌倦了停留在html和css无脑拼装的层次上，希望能向前端大神更近一步，加之一直追随的前辈也有自己的（很强的）工具箱，就想到了做工具箱的点子上。

### 志向
<S>至少在中国有和一个木函一样的影响吧？</s>

能被别人的文章推荐到。譬如知乎

## 技术选型
20年二月份之前，一直都是传统的php和jq结构。为了营造出SPA的效果还死磕`iframe`. 没想到视觉效果还不错。
### 技术栈
感谢这些优秀的库/框架。另外一些小规模使用的库没有列出。
* Create-react-app
* Typescript
* Sass
* MDUI
* Express

## 应用技术细节

### 检测设备的夜间模式
```js
window.matchMedia && window.matchMedia('prefers-color-scheme: dark').matches
```
## 思考