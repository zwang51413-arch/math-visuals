# 交互教学小程序

把有认知门槛的数学概念，压成一张能动手玩的图。每个题目都是一个零依赖的单文件 HTML，打开即用，支持鼠标与触摸。

## 目录

| 链接 | 学段 | 说明 |
| --- | --- | --- |
| [triangle-angle-sum](./triangle-angle-sum/) | 初中 · 入门 | 三角形内角和：箭头沿边走一圈，三个内角拼成一条直线 |
| [cube-net](./cube-net/) | 小学 · 空间 | 正方体展开图：11 种合法展开图可拖动折叠，相对面自动配对，另含反例 |

## 本地使用

直接双击对应目录下的 `index.html`，或在本目录起一个静态服务：

```bash
python3 -m http.server 8080
# 打开 http://localhost:8080
```

## 部署

本站部署在 GitHub Pages，`main` 分支根目录即发布内容。新增题目时：把单文件 HTML 放进 `题目ID/index.html`，并在根 `index.html` 的列表里加一条即可。
