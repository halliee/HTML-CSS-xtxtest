## 小兔鲜儿商城 

通过HTML和CSS实现小兔鲜儿商城pc客户端前端静态页面



## 项目功能
该项目共分为七大部分：快捷导航栏、header头部模块、banner图、新鲜好物模块、人气推荐模块、生鲜模块、footer版权模块

## 项目信息
#### 所用知识点：
1. 精灵图 ： <br />
&ensp; a. 创建一个盒子设置盒子的尺寸和小图尺寸相同 <br />
&ensp; b. 将精灵图设置为盒子的背景图片 <br />
&ensp; c. 修改背景图位置 <br />
&ensp; d. 通过PxCook测量小图片左上角坐标，分别取**负值**设置给盒子的background-psitioni：xy<br />
2. 背景图片大小 <br />
&ensp; a. contain: 如果图的宽度或高与盒子的尺寸相同了，另一个方向停止缩放-一导致盒子可能存在留白。<br />
&ensp; b. cover : 如果图片比例和盒子的比例不相同，会导致图片显示不全。<br />
&ensp; c. 若图的比例和盒子的比例是相同的，contain 和 cover 效果完全相同。
3. 盒子阴影<br />
&ensp; a. 默认就是外阴影，不能添加outset，会导致属性报错。要么不加，要么加inset。
4. 过渡骨架<br />
&ensp; a. 过渡需要:默认状态和hover状态样式不同，才能有过渡效果。<br />
&ensp; b. transition属性给需要过渡的元素本身加。<br />
&ensp; c. transition属性设置在不同状态中，效果不同：<br />
 &ensp;&ensp;1. 给默认状态设置，鼠标移入移出都有过渡效果。<br />
 &ensp;&ensp;2. 给hover状态设置，鼠标移入有过渡效果，移出没有过渡效果。<br />
5. 结构标签
6. SEO三大标签
7. 标题图标<br />
&ensp; a. link:favicon浏览器标题栏图标

##  文件和目录准备<br>

- 1.新建项目文件夹 xtx-pc-client，在VScode中打开：
       - 在实际开发中，项目文件夹不建议使用中文
       - 所有项目相关文件都保存在 xtx-pc-client 目录中
- 2.复制 favicon.ico 到 xtx-pc-client 目录
       - 一般习惯将ico图标放在项目根目录
- 3.复制 images 和 uploads 目录到 xtx-pc-client 目录中
      - images: 存放网站固定使用的图片素材，如: logo、样式修饰图片...等
      - uploads:存放网站非固定使用 的图片素材，如: 商品图片、宣传图片...等
- 4.新建index.html在根目录
- 5.新建css文件夹保存网站的样式，并新建以下css文件：
  - base.css：基础公共样式
  - common.css：该网站中多个网页相同模块的重复样式，如：头部，底部
  - index.css：首页样式

- 6.说明

