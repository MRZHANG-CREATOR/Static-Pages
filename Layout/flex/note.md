#

//父元素 容器  属性 display：flex
//felx-direction 设置主轴方向 row行从左到右（默认）  
//row-reverse右往左  column列上到下  column-reverse下到上
//justify-content 主轴上的排列方式 先确定主轴
//felx-start从头开始  flex-end尾部开始但是顺序不变 center居中排列
//平分剩余空间 space-around   平均边距    space-between 先贴边在平分
//flex-wrap 设置子元素是否换行 默认不换，强制一行
//no-wrap 不换行   wrap  换行
//align-items  设置侧轴上的子元素排列方式 没有space-around space-between用align-content
//flex-start侧轴头部   flex-end 侧轴尾部开始    stretch 侧轴方向拉伸  center 居中
//align-content设置侧轴上的子元素的排列方式 多行使用，单行无效 必有flex-wrap：wrap
//flex-start flex-end center space-around  space-between  stretch
//flex-flow  flex-direction 和 flex-warp的复合属性

//子元素 项目 属性
//flex 定义子项目分配占有剩余空间空间 flex：number   默认0
//align-self  控制子项在侧轴上的排列方式flex-start flex-end
//order 定义项目  order： number  默认0 小的在前面  

overflow-x: hidden;
/* 隐藏水平滚动条 */
-webkit-transform: translateX(-50%);
transform: translateX(-50%);
/* 左移自身一半 兼容老版本谷歌*/
/* css3盒模型包含padding和border  */
box-shadow: 0 2px 4px rgba(0, 0, 0, .2) 盒子阴影
background: url(../images/sprite.png) no-repeat -59px -279px;
background-size: 104px auto;
text-shadow: 1px 1px rgba(0, 0, 0, .2); 文本阴影
 /* 设置渐变色，必须加私有前缀 */
background: -webkit-linear-gradient(left, #FA5A55, #FA994D);
