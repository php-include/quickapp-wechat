# 快应用实现的微信

> 本项目不求完全实现微信功能，目的是熟悉和学习快应用开发，欢迎大家star,fork,PR

<img src="./assets/0.png" width="50%" height="50%" />
<img src="./assets/1.png" width="50%" height="50%" />
<img src="./assets/2.png" width="50%" height="50%" />
<img src="./assets/3.png" width="50%" height="50%" />
<img src="./assets/4.png" width="50%" height="50%" />


## 快应用开发中发现的问题：

### CSS问题

- 默认是flex布局，css就不用显示设置了；
- 一定要看文档提示，有些属性不支持，比如 `justify-content` 不支持 `space-around`

### 布局问题

- 自定义布局导入到父布局后默认宽高还是屏幕尺寸，并不是限制到父布局宽高

### 事件

- 没有touch事件

### DOM

- 不能操作document，比如所document.getElementById
- onReady后才能操作DOM
- $element(id) 不能直接修改style

### MVVM

- VM的属性值必须在onInit之前修改好，等onReady后再修改无效，view不能更新

## 欢迎大家关注`快应用栈`公众号

![](/assets/wx.jpg)