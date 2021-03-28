
# 兄弟选择器

## ~

选择其后的所有同级标签

```css
input.input:checked ~ div.input-ex {
  visibility: visible;
}
```

## +

选择尾随其后的标签

```css
input.input:checked + div.input-ex {
  visibility: visible;
}
```
