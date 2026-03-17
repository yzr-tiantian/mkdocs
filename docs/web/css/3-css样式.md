# 3-css样式
### 基础样式

| 属性  | 值   | 描述  |
| --- | --- | --- |
| width | % , px , hv | 宽度  |
| height | % , px , hv | 高度度 |
| background | color | 背景颜色 |

#### 颜色

```css
/* 关键字 */
color: black;

/* 十六进制 */
color: #000;

/* RGB */
color: rgb(0, 0, 0);
color: rgb(0, 0, 0);

/* 透明：1是不透明，0.5是半透明 0是全透明 */
color: rgba(0, 0, 0, 1);

/* 设置透明度，取值范围0~1之间 */
opactiy:.4;

/* HSL */
color: hsl(0, 0%, 0%);
color: hsla(0, 0%, 0%, 1);
```

### 文本样式

#### 字体组

```css
font-family: "微软雅黑", "宋体", sans-serif;
```

#### 字体大小

```css
font-size: 16px;
```

#### 简写

```css
font: font-size/line-height font-style font-weight  font-family;

font: 16px/1.5 "微软雅黑", "宋体", sans-serif;
```

#### 字体风格

```css
font-style: normal; /* 正常 */
font-style: italic; /* 斜体 */
font-style: oblique; /* 倾斜 */
```

#### 字体粗细

```css
font-weight: normal; /* 正常 */
font-weight: bold; /* 加粗 */
font-weight: bolder; /* 更粗 */
font-weight: lighter; /* 更细 */

font-weight: 100; /* 最细 */
font-weight: 500; /* 正常 */
font-weight: 900; /* 最粗 */
```

#### 字体装饰

```css
text-decoration: none; /* 无 */
text-decoration: underline; /* 下划线 */
text-decoration: overline; /* 上划线 */
text-decoration: line-through; /* 删除线 */
text-decoration: blink; /* 闪烁 */
```

#### 文本转换

```css
text-transform: none; /* 无 */
text-transform: capitalize; /* 首字母大写 */
text-transform: uppercase; /* 全大写 */
text-transform: lowercase; /* 全小写 */
```

### 文本布局

#### 文本对齐

```css
text-align: left; /* 左对齐 */
text-align: right; /* 右对齐 */
text-align: center; /* 居中对齐 */
text-align: justify; /* 两端对齐 */
light-align: 10px; /* 垂直居中 */
```

#### 文本缩进

em 是相对单位，相对于当前元素的字体大小，如果当前元素没有设置字体大小，则相对于父元素的字体大小。

```css
/* 段落首行缩进2个字符 */
text-indent: 2em; /* 缩进2个字符 */
```

#### 文本间距

```css
letter-spacing: 2px; /* 字间距 */
line-height: 1.5; /* 行间距 */
```

### 布局样式

#### 块级盒子居中

```css
margin: 0 auto;
```

### 表格

#### 表格边框合并

```html
border-collaose:caollap se
```