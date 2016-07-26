+ 涉及的一些属性
    - 关于父元素
        + `display: flex`
        + `display: inline-flex` 适用于行内元素
        + `display: -webkit-flex` 适用于`webkit`内核的浏览器
    - 设置在容器上的属性
        + flex-direction
            - `row` 主轴水平,起点在左端
            - `row-reverse` 主轴水平,起点在右端
            - `column` 主轴为垂直方向 起点在上沿
            - `column-reverse` 主轴为垂直方向 起点在下沿
        + flex-wrap: 默认情况下，项目都排在一条线（又称"轴线"）上。flex-wrap属性定义，如果一条轴线排不下，如何换行
        + flex-flow: 是flex-direction属性和flex-wrap属性的简写形式，默认值为row nowrap
        + justify-content: 定义了项目在主轴上的对齐方式
        + align-items: 定义项目在交叉轴上如何对齐
        + align-content: 定义了多根轴线的对齐方式。如果项目只有一根轴线，该属性不起作用
    - 关于子项目
        + order: order属性定义项目的排列顺序。数值越小，排列越靠前，默认为0
        + flex-grow: flex-grow属性定义项目的放大比例，默认为0，即如果存在剩余空间，也不放大
        + flex-shrink: flex-shrink属性定义了项目的缩小比例，默认为1，即如果空间不足，该项目将缩小
        + flex-basis: flex-basis属性定义了在分配多余空间之前，项目占据的主轴空间（main size）。浏览器根据这个属性，计算主轴是否有多余空间。它的默认值为auto，即项目的本来大小
        + flex: flex属性是flex-grow, flex-shrink 和 flex-basis的简写，默认值为0 1 auto。后两个属性可选
        + align-self: align-self属性允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items属性。默认值为auto，表示继承父元素的align-items属性，如果没有父元素，则等同于stretch


+ 参考的一些东西
  - [A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)
  - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [Flex 布局教程：实例篇](http://www.ruanyifeng.com/blog/2015/07/flex-examples.html?bsh_bid=683103006)
  - [Flex 布局教程：语法篇](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)