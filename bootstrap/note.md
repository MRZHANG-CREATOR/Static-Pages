# 响应式布局

媒体查询完成
bootstrap
原理：通过媒体查询惊醒布局和样式设置
设备划分
超小设备768  小屏平板992
中等1200
宽屏大于1200
需要一个父级作为布局容器
类前缀
xs-extra small 超小
sm-small 小
md-medium 中等
lg-large 大
列嵌套最好加行  消除父元素的padding值 高度自动调整
列偏移 col-md-offset
交换顺序 col-md-pull
隐藏  .hidden-xs 超小隐藏
.hidden-sm
.hidden-md
.hidden-lg