# TwitterArchiver

> 让每一个声音，都不会在网络里消散。

## [全站时间线](https://twitterarchiver.github.io/home/search.html) · [Home](https://twitterarchiver.github.io/home/)

---

## 这里是什么

TwitterArchiver 是一个基于 [Wayback Machine](https://web.archive.org) 的推特/X 账号存档计划。

每个仓库对应一个账号的完整推文存档——HTML 快照、图片、视频、头像，一并保存，可离线阅读，永久留存。

这个项目，这里的一切最初都是为了 **[@AnIncandescence](https://github.com/TwitterArchiver/AnIncanescence)** 而创建。

她的账号被封禁，但是她永远也不会被遗忘。

她说过，"互联网是现实的避难所"。
这里，是那个避难所的避难所。

*烛火熄灭之后，光还在。*

---

## 本仓库

`home` 是组织的门户与聚合数据层，为网页版、桌面版与 Android 客户端共同提供数据。

| 文件 | 说明 |
| --- | --- |
| `index.html` | 门户首页 |
| `search.html` | 全站时间线与跨账号搜索 |
| `guestbook.html` | 存档申请页 |
| `repos.json` | 账号清单：仓库名、账号、昵称、简介、头像 |
| `search-index.json` | 全站搜索索引，汇总所有账号的推文 |
| `cross-replies.json` | 跨账号回复索引 |
| `timeline-recent.json` | 最近收录 |
| `preview.json` | 首页预览数据 |
| `avatars/` | 聚合的账号头像 |

数据由 [`.github/workflows`](https://github.com/TwitterArchiver/home/tree/main/.github/workflows) 下的工作流定期从各存档仓库汇总生成。

---

## 相关项目

整个体系由「抓取 → 存放 → 阅读」三层构成，本仓库属于存放层。

| 项目 | 说明 |
| --- | --- |
| [**TwitterArchiver**](https://github.com/TwitterArchiver) | 组织首页，含完整的项目生态说明 |
| [**TwitterArchiverApp**](https://github.com/sjshb57/TwitterArchiverApp) | Android 客户端 |
| [**IncandescenceArchiver**](https://github.com/sjshb57/IncandescenceArchiver) | 存档工具 `archive.py`，抓取 Wayback 快照并生成索引 |
| [**IncandescenceReader**](https://github.com/sjshb57/IncandescenceReader) | 桌面离线阅读器（Electron） |

---

## 如何存档你关注的账号

任何人都可以 fork [sjshb57/IncandescenceArchiver](https://github.com/sjshb57/IncandescenceArchiver)，为自己关注的账号建立一份永久存档。

脚本会自动从 Wayback Machine 拉取推文数据，生成可在线阅读的静态页面，部署到 GitHub Pages。

→ **[查看使用教程](https://github.com/sjshb57/IncandescenceArchiver)**

如果希望直接收录进本组织，也可以 **[在这里提交申请](https://twitterarchiver.github.io/home/guestbook.html)**（Android 应用内也能直接提交）。

---

## 当前存档账号

本组织下的每个仓库都是一个独立的账号存档，可直接访问对应的 GitHub Pages 页面阅读。

完整清单见 **[全站时间线](https://twitterarchiver.github.io/home/search.html)**。

---

## 开源协议

本项目所有代码以 [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html) 协议开源。

> 存档内容本身的版权归原作者所有。本组织仅做数字保存，不主张任何内容权利；如果你是某个存档账号的本人或权利人，希望移除相应内容，请提 Issue。

---

## 赞助

![赞助图片](https://free.picui.cn/free/2026/06/24/6a3b25866f0fd.jpg)
