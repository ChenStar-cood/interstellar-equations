# 时空几何、黑洞物理与虫洞拓扑：公式汇编

[English](README.md) | [简体中文](README.zh-CN.md)

本目录包含六幅公式截图的 LaTeX 转录稿，并提供英文与简体中文两个版本。

## 来源

本转录稿的公式内容来源于电影《星际穿越》（*Interstellar*）中的“引力公式”相关截图。本文档仅将这些截图中的公式整理为 LaTeX 文稿，不对公式本身的物理正确性作额外考证。仓库中不包含原始截图，只包含 LaTeX 转录稿与编译后的 PDF。

## 文件

- `main.tex`：中文版 XeLaTeX 源文件，使用 `ctexart` 文档类。
- `main.pdf`：中文版 6 页 PDF。
- `main-en.tex`：英文版 XeLaTeX 源文件，使用 `article` 文档类。
- `main-en.pdf`：英文版 6 页 PDF。
- `README.md`：英文说明。
- `README.zh-CN.md`：本说明。

## 编译

在包含源文件的目录中运行：

```powershell
# 中文版
xelatex main.tex
xelatex main.tex

# 英文版
xelatex main-en.tex
xelatex main-en.tex
```

需要安装 TeX Live（中文版还需 `ctex`，英文版使用标准宏包）。两份文档均已用 TeX Live 2025 的 XeLaTeX 编译通过。

## 说明

- 公式按主题重新编排为三部分：基础时空几何、黑洞与吸积盘、虫洞与时空拓扑。
- 公式、张量指标和符号按原图录入；仅统一了数学字体、行距、分段与页面版式。
- 原图中的中文标题保留，并补充了少量层级小标题以便查阅。
- 本转录稿由人工整理，可能有误，欢迎指正。
