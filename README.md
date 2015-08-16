# perfect-footer

解决页面中footer的问题：页面内容多footer在页面底部， 页面内容少不足一屏幕，footer显示在屏幕底部。

## why

参考 [https://www.google.com/](https://www.google.com/) , 使 `footer` 智能的显示在页面底部或者屏幕底部原理是： 

- `footer`的容器高度适中保持100%
- 使用 `position:relative` 定位
- `footer` 使用 `position: absolute;` 定位，并设置 `bottom: 0`

## demo
