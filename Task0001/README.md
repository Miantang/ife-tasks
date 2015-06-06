###CSS float 属性

在 CSS 中，任何元素都可以浮动。浮动元素会生成一个块级框，而不论它本身是何种元素。

如果浮动非替换元素，则要指定一个明确的宽度；否则，它们会尽可能地窄。

假如在一行之上只有极少的空间可供浮动元素，那么这个元素会跳至下一行，这个过程会持续到某一行拥有足够的空间为止。


###[视觉格式化模型](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Visual_formatting_model)

1. 块级元素与块盒(Block-level elements and block boxes)

[块格式化上下文](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Block_formatting_context)


块格式化上下文block formatting context 是页面 CSS 视觉渲染的一部分。它是用于决定块盒子的布局及浮动相互影响范围的一个区域。

下列情况将创建一个块格式化上下文：

- 根元素或其它包含它的元素
- 浮动 (元素的 float 不为 none)
- 绝对定位元素 (元素的 position 为 absolute 或 fixed)
- 内联块 inline-blocks (元素的 display: inline-block)
- 表格单元格 (元素的 [display](https://developer.mozilla.org/zh-CN/docs/CSS/display): table-cell，HTML表格单元格默认属性)
- 表格标题 (元素的 display: table-caption, HTML表格标题默认属性)
- overflow 的值不为 visible的元素
- 弹性盒 flex boxes (元素的 display: flex 或 inline-flex)

[双飞翼布局介绍-始于淘宝UED](http://www.dqqd.me/flying-wing/)

###表格布局

`border-collapse: collapse` 这样tr才有border属性？

class tag选择器比 class选择器优先级高？


###index 

