# taro-h5-progressDashboard
SVG画图，h5支持，微信小程序暂不支持，后续会写一个canvas版本的兼容微信小程序emmm


一些props:
radius | 半径大小 | number,

openWidth | 底缺口线条长度 | number,

strokeWidth | 线条宽度 | number,

strokeColor | 进度色, '#fff'

trailColor | 背景色, '#fff'

animatable | 动画渐进 | boolean,

percent | 进度值 | number | 必传

text数字颜色 | '#fff'

textContent内容 | '#fff' | '考试通过'

![image](https://github.com/catXiaoXiao/taro-h5-progressDashboard/blob/master/ProgressDashboard/logo1.png)
```jsx
<MeDashboard percent={percent} />


