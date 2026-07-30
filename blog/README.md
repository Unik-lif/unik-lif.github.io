# Between Layers / 层间札记

博客使用纯 HTML 和 CSS，与个人主页一样不依赖构建工具。

## 发布一篇新文章

1. 复制 `posts/_template.html`，用英文短标题命名，例如 `kv-cache-notes.html`。
2. 填写标题、摘要、日期、标签和正文。
3. 在 `index.html` 的文章列表顶部加入文章卡片。
4. 在 `feed.xml` 顶部加入对应的 `<item>`，并更新 `lastBuildDate`。
5. 本地确认文章页、首页入口和 RSS 链接都能打开后提交。

文章里的事实、观点和引用由作者最终确认；如果 AI 深度参与，可在文末保留一段简短的协作说明。
