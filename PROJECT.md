# 至善鱼公开介绍页（zhishanyu-site）

- 用途：至善鱼源码仓库 `BewusstseinEwigkeit/zhiyu-zhishan` 为 private，外部访问一律 404。本目录是对外公开的单页介绍，托管在公开仓库 `BewusstseinEwigkeit/zhishanyu` 的 GitHub Pages。
- 线上地址：https://bewusstseinewigkeit.github.io/zhishanyu/
- 状态：2026-11-17 建立并上线。下载区（`<!-- DOWNLOAD:START/END -->` 之间）指向本仓库 Release v0.2.10 的便携包（本人同意公开发布 exe）。新版本：在主仓库 `npm run dist:win` → `gh release create vX -R BewusstseinEwigkeit/zhishanyu <exe>` → 改下载区链接与 SHA256。
- 技术栈：纯静态 HTML/CSS，无构建。素材复制自 `_preview-zhiyu-pr5/public/assets/brand` 与 `docs/screenshots`（演示数据）。
- 输入/输出：输入为主仓库 README/GETTING_STARTED 的面向用户部分；输出 `index.html` + `assets/`。
- 发布：本目录即公开仓库工作树，`git push` 后 Pages 自动部署（main 分支根目录）。
- 相关项目：`../_preview-zhiyu-pr5`（主仓库 feat/v03-ui-redesign 工作树）；应用内「下载页 / GitHub 仓库 / 文档卡片」链接已改指向本页。
- 在线试用链接来自主仓库 v0.2.9 Release 说明，2026-11-17 无登录访问返回 200。
- 最后更新：2026-11-17
