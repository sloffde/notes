# 贡献指南 · 学习笔记站（notes）

感谢你为 SLOFFDE 整理学习笔记！本仓库用 [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) 构建。

## 加一篇笔记

1. 把笔记转成 Markdown（Pandoc / OCR / 手工均可）。
2. 顶部加 front matter，字段见 `docs/大一/系统解剖学/运动系统-骨学总论.md`（格式样例）。
3. **脱敏**：原作者真实姓名改为脱敏署名（如「2022 级 学长 A」）。
4. 放 `docs/<年级>/<科目>/<章节>.md`，图片放该章节 `_images/`。
5. 提 PR；合并后 GitHub Actions 自动构建上线。

## front matter 字段

`title` / `grade` / `subject` / `chapter` / `knowledge_points` / `author` / `contributor` / `date` / `tags` / `source` / `license` / `review_status`

## 贡献方式

同历年题站：Issue / 网页端编辑 / PR 任选。

## 医学免责

所有笔记页脚须保留医学准确性声明（见 `docs/disclaimer.md`）。
