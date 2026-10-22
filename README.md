# MY-IELTS

> 🌐 **GitHub Pages 在线访问：https://lucinwen.github.io/MY-IELTS/**
>
> - 互动工作台：https://lucinwen.github.io/MY-IELTS/（即 `dist/index.html`）
> - 完整离线学习计划：https://lucinwen.github.io/MY-IELTS/plan.html
> - 写作与口语练习题卡：https://lucinwen.github.io/MY-IELTS/writing-prompts.html
>
> 任何人打开链接即可在线预览，无需拉取到本地。站点由 GitHub Actions 自动部署 `dist/` 目录生成（工作流见 `.github/workflows/deploy.yml`），每次推送 `main` 后自动更新。

原「IELTS 8+ · 四个月作战计划」的静态网页与离线阅读版。保留原网页功能与文件内容。

## 使用

- 互动工作台：`dist/index.html`
- 完整离线学习计划：`dist/plan.html`
- 写作与口语练习题卡：`dist/writing-prompts.html`

纯静态 HTML/CSS/JavaScript，无需安装依赖或构建。下载仓库后可以打开离线学习计划；互动工作台建议通过本地 HTTP 服务访问：

```sh
python -m http.server 8000 --directory dist
```

然后打开 http://localhost:8000 。

## 学习记录与日期

打卡、笔记和成绩保存在当前浏览器的本地存储中，不会上传至 GitHub，也不会自动从原站点迁移。迁移时请先在原站点设置页导出 JSON，再在新地址导入。页面中的规划考试日不是已预约考试的证明。

## 上传范围与检查

本仓库仅包含可直接使用的网页成品和说明，不包含原部署内部配置、本地 Node 生成脚本、测试脚本或个人学习记录。

上传前已通过 JavaScript 语法检查、本地资源引用检查，并在原源码包中运行日期/数据迁移测试通过。未在本次上传中重新核查所有外部学习资源或实测完整浏览器交互。

本仓库已开启 GitHub Pages，上方在线访问链接由 GitHub Actions 部署 `dist/` 生成；后续如改动网页内容，推送到 `main` 分支即会自动重新部署。
