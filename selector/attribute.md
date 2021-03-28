
# 属性选择器

以 "#" 开头的页面本地链接
```css
a[href^="#"] {
  background-color: gold;
}
```

包含 "example" 的链接
```css
a[href*="example"] {
  background-color: silver;
}
```

包含 "insensitive" 的链接,不区分大小写
```css
a[href*="insensitive" i] {
  color: cyan;
}
```

包含 "cAsE" 的链接，区分大小写
```css
a[href*="cAsE" s] { 
  color: pink; 
}
```

以 ".org" 结尾的链接
```css
a[href$=".org"] {
  color: red;
}
```
