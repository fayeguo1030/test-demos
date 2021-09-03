# 本地预览方法

```
yarn global add http-server
hs . -c-1
```
### 1、不用div因为div的太耗性能，特别慢还卡
### 2、文档可视区的宽高，body默认不会占全屏
### 3、canvas.width 是canvas的属性; canvas.style.width 是css属性不支持的
### 4、 ctx.strokeStyle = 'none';//不要描边
### 5、lineWidth 设太宽会出现锯齿，微软自带的画图工具也是这个问题，不能设太大
### 6、 ctx.lineCap = "round";// 解决线段不连续问题，虽然有锯齿，但是很流畅
### 7、 移动设备e包含多个手指的事件，e.touches[0].clientX

