
# Flex 弹性布局

## 左右 布局
```html
<div class="main">
  <div class="left"></div>
  <div class="right"></div>
</div>
```

```css
.main {
  display: flex;
}

.main > div {
  height: 100px;
}
```

### 填满剩余空间
```css
.main > .left {
  /* 避免宽度设置失效 */
  /* flex-shrink: 0; */
  width: 100px;
}

.main > .right {
  flex: 1;
  /*flex-grow: 1;*/

  min-width: 1000px;
}
```

### 按比例
```css
.main > .left {
  flex: 1;
}

.main > .right {
  flex: 2;
}
```
