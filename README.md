# MY-IELTS

原「IELTS 8+ · 四个月作战计划」网页源码与离线阅读版。

## 使用

- 互动工作台：`dist/index.html`
- 完整离线学习计划：`dist/plan.html`
- 写作与口语练习题卡：`dist/writing-prompts.html`
- 原始说明与更新记录：`README.txt`

纯静态 HTML/CSS/JavaScript，无需安装依赖或构建。下载仓库后可以打开离线学习计划；互动工作台建议通过本地 HTTP 服务访问：

```sh
python -m http.server 8000 --directory dist
```

然后打开 http://localhost:8000 。

## 学习记录与日期

打卡、笔记和成绩保存在当前浏览器的本地存储中，不会上传至 GitHub，也不会自动从原站点迁移。迁移时请先在原站点设置页导出 JSON，再在新地址导入。

本次保留原网页及默认日期（2026-10-08），没有重新安排计划；可在设置中自行修改。页面中的规划考试日不是已预约考试的证明。

## 检查

```sh
node tests/date-migration.cjs
```

本次上传已通过 JavaScript 语法检查、本地资源引用检查与上述日期/数据迁移测试。未在本次上传中重新核查所有外部学习资源或实测完整浏览器交互。

源码上传不等于开启 GitHub Pages；本次未更改仓库站点托管设置。
