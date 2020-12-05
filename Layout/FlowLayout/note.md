#

移动端基本都是webkit内核
不建议纠结dp dpi pt ppi 等单位
视口可以分
布局视口（layout viewport） 
视觉视口 （visual viewport）
理想视口（ideal viewport）
meta
width=device-width 设备宽度
user-scalable=0||1 用户可缩放
initial-scale=1.0 初始比例
maximum-scale=1.0 最大比例
minimum-scale=1.0 最小比例
物理像素 分辨率
1px与物理像素不一定相等
电脑端相等
手机不全相等，
视网膜屏技术，为了增加像素提高显示细腻程度
背景缩放background-size  规定背景图像的尺寸  
1.宽度 高度  只写一个就是宽度
2.百分比  相对父元素
3.cover  完全填充，填满
4.contain  单方向填满

页面选择 
单独制作   响应式制作

box-size
content-box 传统盒模型 宽度包括padding和border
border-box css3盒模型  padding和border不撑开盒子 有些兼容性问题

清除点击的高亮   -webkit-tap-highlight-color: transparent  透明
-webkit-appearance  去掉默认样式，按钮等
-webkit-touch-callout： none   禁用长按出菜单

技术选型
单独制作移动端  1.流式布局（百分比）  2.flex弹性布局  3.rem 媒体查询布局  4.混合布局
响应式制作   1.媒体查询 2.bootstrap

图片默认和文字基线对齐  用vertical-align：middle

DPG 图片压缩格式 京东自主研发
webp 谷歌开发 加快加载速度

box-sizing