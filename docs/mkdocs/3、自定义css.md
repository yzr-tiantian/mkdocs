# 高级功能

## 自定义 CSS

在 `docs/stylesheets/extra.css` 中创建自定义样式：

```css
:root {
  --md-primary-fg-color: #00897b;
}

.md-typeset h1 {
  color: var(--md-primary-fg-color);
}
```

在 `mkdocs.yml` 中引用：

```yaml
extra_css:
  - stylesheets/extra.css
```

## 自定义 JavaScript

在 `docs/javascripts/extra.js` 中添加自定义脚本：

```javascript
document.addEventListener("DOMContentLoaded", function() {
  console.log("文档已加载");
});
```

在 `mkdocs.yml` 中引用：

```yaml
extra_javascript:
  - javascripts/extra.js
```

## 添加图标

Material 主题支持 Material Icons 和 FontAwesome 图标：

```markdown
<span class="twemoji">
  {% include '.icons/fontawesome/solid/home.svg' %}
</span>
```

## 搜索优化

```yaml
plugins:
  - search:
      lang:
        - zh
        - en
      separator: '[\s\-\.]+'
```

## 版本控制

```yaml
extra:
  version:
    provider: mike
```

## 社交链接

```yaml
extra:
  social:
    - type: github
      link: https://github.com/yourusername
    - type: twitter
      link: https://twitter.com/yourusername
```

## 版权信息

```yaml
copyright: Copyright &copy; 2024 Your Name
```

!!! tip "提示"
    Material 主题提供了更多高级功能，如博客支持、评论系统、分析工具等。查看 [官方文档](https://squidfunk.github.io/mkdocs-material/) 了解详情。
