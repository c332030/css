
# 笔记

- 伪类
    - :before :after :empty 显示图标文字
    - :checked 显示隐藏附加输入组件

```css
.tip-with-icon:before {

  content: '';

  display: inline-block;

  margin-right: 5px;

  width: 16px;
  height: 16px;

  background-image: url("/resource/images/u95.png");
  background-size: 100%;
}
```

- 常量
```css
:root {
  --theme-color: #20a0ff;
  background: var(--theme-color);
}
```

- span 标签默认 inline-block

- 使用 pointer-event: none 来禁止 div 块输入
    - 子标签可覆盖实现 hover
