# 禁止响应式
不喜欢响应式？可以尝试禁用：

删除 head 里的视口设置 meta 标签；

```html
<!-- 注释掉 -->
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
```

固定容器 .am-container 宽度（可以自己添加一个 class，不一定要使用内置的）：

```css
.container {
  width: 970px !important;
}
```