#

rem 适配布局
文字能响应式变化，高度响应式变化
rem 是一个单位 root em
em 是父元素的字体大小 font-size
rem 相对于HTML元素的字体大小 font-size
可以通过html的字体大小改变整体

媒体查询：Media Query   css3新语法
@media可以针对不同的屏幕尺寸设置不同的样式
@media mediatype and| not|only （media feature）｛
css code ｝
开头关键字 媒体类型 关键字 （媒体特性）｛｝
媒体类型 all所有设备  print打印机和打印预览  screen 用于电脑屏幕，平板，手机等
关键字  and且 not非  only指定特定类型，可省略
媒体特性
width    min-width  max-width

媒体查询引入资源
两套css文件不同情况下调用

```
<link ref="" href="" media="screen and (min-width:300px)">
```
less  leaner style sheet css预处理器sass，less，stylus等
计算能力，变量共用，单位转换，易于维护，程序性语言，引入变量，混入（mixin）,嵌套
node环境安装
npm i -g less
lessc -v 

less变量
@变量名：值
不能数字开头，大小写敏感，@开头,无特殊符号
less编译
easy less  自动编译
伪类 伪元素 需要加&    &：hover
less运算
运算符两侧加空格 一个有单位，以单位为准 两个数都有单位第一个数的单位为准

rem适配方案
方案一 less 媒体查询 rem
方案二 flexible.js rem
