# React-Native StyleSheet Guide

`React-Native` 支持的样式相当于是 `CSS` 的一个子集，并且属性名不完全一致，所以当你开始在编写 `React-Native` 之前，可以先简要了解一下。

## 目录

* [view](#user-content-view)
* [Image](#user-content-view)
* [Text](#user-content-view)
* [Layout 布局](#user-content-layout)
    * [Dimension 尺寸](#user-content-dimension)
    * [Positioning 定位](#user-content-positioning)
    * [Margin 外部白](#user-content-margin)
    * [Padding 内补白](#user-content-padding)
    * [BorderWidth 边框厚度](#user-content-border-width)
    * [Flex 弹性盒](#user-content-flex)


<a name="layout"></a>
## Layout 布局

<a name="dimension"></a>
### Dimension 尺寸
属性名 | 取值 | 描述
---|---|---
width | number | 对应 `CSS` 中的 `width` 属性
height | number | 对应 `CSS` 中的 `height` 属性

<a name="positioning"></a>
### Positioning 定位
属性名 | 取值 | 描述
---|---|---
position | absolute/relative | 对应 `CSS` 中的 `position` 属性，但取值有变化
top | number | 对应 `CSS` 中的 `top` 属性
right | number | 对应 `CSS` 中的 `right` 属性
bottom | number | 对应 `CSS` 中的 `bottom` 属性
left | number | 对应 `CSS` 中的 `left` 属性

<a name="margin"></a>
### Margin 外部白
属性名 | 取值 | 描述
---|---|---
margin | number | 对应 `CSS` 中的 `margin` 属性
marginHorizontal | number | `CSS`中没有对应的属性，相当于同时设置marginRight和marginLeft
marginVertical | number | `CSS`中没有对应的属性，相当于同时设置marginTop和marginBottom
marginTop | number | 对应 `CSS` 中的 `margin-top` 属性
marginRight | number | 对应 `CSS` 中的 `margin-right` 属性
marginBottom | number | 对应 `CSS` 中的 `margin-bottom` 属性
marginLeft | number | 对应 `CSS` 中的 `margin-left` 属性

<a name="padding"></a>
### Padding 内部白
属性名 | 取值 | 描述
---|---|---
padding | number | 对应 `CSS` 中的 `padding` 属性
paddingHorizontal | number | `CSS`中没有对应的属性，相当于同时设置paddingRight和paddingLeft
paddingVertical | number | `CSS`中没有对应的属性，相当于同时设置paddingTop和paddingBottom
paddingTop | number | 对应 `CSS` 中的 `padding-top` 属性
paddingRight | number | 对应 `CSS` 中的 `padding-right` 属性
paddingBottom | number | 对应 `CSS` 中的 `padding-bottom` 属性
paddingLeft | number | 对应 `CSS` 中的 `padding-left` 属性

<a name="border-width"></a>
### BorderWidth 边框厚度
属性名 | 取值 | 描述
---|---|---
borderWidth | number | 对应 `CSS` 中的 `border-width` 属性
borderTopWidth | number | 对应 `CSS` 中的 `border-top-width` 属性
borderRightWidth | number | 对应 `CSS` 中的 `border-right-width` 属性
borderBottomWidth | number | 对应 `CSS` 中的 `border-bottom-width` 属性
borderLeftWidth | number | 对应 `CSS` 中的 `border-left-width` 属性