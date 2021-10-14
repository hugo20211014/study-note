# CSS3

***

## Margin

### 水平居中
* 新版浏览器中可以直接使用 `display: flex; justify-content: center;`来做到el水平居中的效果。
* 在旧版如IE8-9 这样不支持弹性盒布局这样的浏览器中，要实现在父元素中居中，可使用 `margin: 0 auto;`。

### 外边距重叠
* 上下元素的下上外边距重叠时，实际空出的空间长度会为两外边距中的较长值，而不是两边距之和。["更多 MDN"](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing)

***