#CSS Note

####Rem
```css
html { font-size: 62.5%; } 
body { font-size: 14px; font-size: 1.4rem; } /* =14px 兼容低版本IE */
h1   { font-size: 24px; font-size: 2.4rem; } /* =24px 兼容低版本IE */
```

####CSS高消耗属性

```css
box-shadows

border-radius

transparency

transforms

CSS filters /* 性能杀手 */
```

####CSS换行

* 强制换行

```css
word-break: break-all; /* 只对英文起作用，以字母作为换行依据 */
word-wrap: break-word; /* 只对英文起作用，以单词作为换行依据 */
white-space: pre-wrap; /* 只对中文起作用，强制换行 */
```

* 禁止换行
```css
white-space:nowrap;
overflow:hidden;
text-overflow:ellipsis; /* 超出的内容以...来表示 */
```

####Media Queries
```css
/* For Small Desktop */
@media (min-width: 980px) and (max-width: 1150px) {}
```

```css
/* Tablet (Portrait) Design for a width of 768px */
@media (min-width: 768px) and (max-width: 979px) {}
```

```css
/* Mobile (Portrait) Design for a width of 320px */
@media only screen and (max-width: 767px)  {}
```

```css
/* Mobile (Landscape) Design for a width of 480px */
@media only screen and (min-width: 480px) and (max-width: 767px) {}
```