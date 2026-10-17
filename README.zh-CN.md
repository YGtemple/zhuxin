<div align="right">

[English](README.md) · **[简体中文](README.zh-CN.md)**

</div>

# zhuxin

单文件 HTML 的简历与作品集页面。

<sub>HTML · 无需构建</sub>

---

## 是什么

一个自包含的页面：简介、项目、联系方式。无框架、无打包器、无依赖——打开文件就能用。

## 页面里有什么

- 响应式布局，窄屏会回流
- 项目条目带链接和简短说明
- 暗色 / 亮色模式，用 CSS 变量实现，`localStorage` 记住选择
- 联系方式与链接

## 运行

打开 `index.html`。要起服务的话：

```bash
python -m http.server
```

## 说明

这页是照着手机上也能读来做的，所以布局会回流成单列，长文本是换行而不是被裁掉。

## 许可证

MIT
