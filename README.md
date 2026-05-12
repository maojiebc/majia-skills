# majia-skills

我收集的 Claude Code / Codex 公开 skill，**按用途分类目录，按 stars 倒序**。

> 🔐 **API key 不在这个仓库**。需要 key 的 skill 在表格里有标注，key 单独存私有仓库 [`majia-private-skills/config/api-keys.env`](https://github.com/maojiebc/majia-private-skills)。

## 🎯 一眼选 skill — 我想干啥用哪个？

| 想做什么 | 进哪个目录 | 数量 |
|---------|-----------|-----:|
| 🎨 **生成图片/插画/封面/漫画/Slide/Infographic** | [`skills/01-visual-creation/`](skills/01-visual-creation/) | 11 |
| ✍️ **翻译/排版/写推文/生成知识网站** | [`skills/02-writing/`](skills/02-writing/) | 6 |
| 🌐 **网页/视频/推特抓取转 Markdown/NotebookLM** | [`skills/03-content-fetch/`](skills/03-content-fetch/) | 7 |
| 📤 **发到 X / 微信公众号 / 微博** | [`skills/04-publish/`](skills/04-publish/) | 4 |
| 📊 **加密货币新闻 / X 数据 / AI Builder 动态** | [`skills/05-data-api/`](skills/05-data-api/) | 3 |
| 🛠 **压图 / 设计建议 / Spotify 控制** | [`skills/06-utilities/`](skills/06-utilities/) | 3 |

---

## 完整列表（按 stars 倒序）

> 数据采集：2026-05-12。Stars 来自 GitHub API，跑 `bash sync.sh` 可刷新。

| Skill | Stars | Version | 用途 | 需要 |
|-------|------:|--------:|------|------|
| **[agent-reach](skills/03-content-fetch/agent-reach/)** | 19,244 | — | 联网搜索/阅读 | — |
| **[baoyu-translate](skills/02-writing/baoyu-translate/)** | 17,825 | 1.59.0 | 中英文翻译 | — |
| **[baoyu-url-to-markdown](skills/03-content-fetch/baoyu-url-to-markdown/)** | 17,825 | 1.61.0 | 网页→Markdown（Chrome CDP） | — |
| **[baoyu-imagine](skills/01-visual-creation/baoyu-imagine/)** | 17,825 | 1.58.0 | AI 图片生成（推荐用此） | `GOOGLE_API_KEY` |
| **[baoyu-image-gen](skills/01-visual-creation/baoyu-image-gen/)** | 17,825 | 1.56.4 | AI 图片生成（旧版 deprecated） | `GOOGLE_API_KEY` |
| **[baoyu-article-illustrator](skills/01-visual-creation/baoyu-article-illustrator/)** | 17,825 | 1.57.1 | 文章自动配图 | 可选图片后端 |
| **[baoyu-infographic](skills/01-visual-creation/baoyu-infographic/)** | 17,825 | 1.57.1 | 信息图 21 种布局 | 可选图片后端 |
| **[baoyu-format-markdown](skills/02-writing/baoyu-format-markdown/)** | 17,825 | 1.57.0 | Markdown 格式化 | — |
| **[baoyu-comic](skills/01-visual-creation/baoyu-comic/)** | 17,825 | 1.56.1 | 知识漫画创作 | 可选图片后端 |
| **[baoyu-cover-image](skills/01-visual-creation/baoyu-cover-image/)** | 17,825 | 1.56.2 | 文章封面图 | 可选图片后端 |
| **[baoyu-image-cards](skills/01-visual-creation/baoyu-image-cards/)** | 17,825 | 1.56.2 | 小红书/微信图文卡片 | 可选图片后端 |
| **[baoyu-slide-deck](skills/01-visual-creation/baoyu-slide-deck/)** | 17,825 | 1.56.2 | 幻灯片生成 | 可选图片后端 |
| **[baoyu-xhs-images](skills/01-visual-creation/baoyu-xhs-images/)** | 17,825 | 1.56.2 | 小红书图（已被 image-cards 取代） | 可选图片后端 |
| **[baoyu-danger-gemini-web](skills/01-visual-creation/baoyu-danger-gemini-web/)** | 17,825 | 1.56.1 | 逆向 Gemini Web（图+文） | Google 登录 |
| **[baoyu-danger-x-to-markdown](skills/03-content-fetch/baoyu-danger-x-to-markdown/)** | 17,825 | 1.56.1 | X 推文/文章→Markdown | X 登录态 |
| **[baoyu-markdown-to-html](skills/02-writing/baoyu-markdown-to-html/)** | 17,825 | 1.56.1 | Markdown→HTML | — |
| **[baoyu-post-to-x](skills/04-publish/baoyu-post-to-x/)** | 17,825 | 1.56.1 | 发 X 推文/长文 | X 登录态 |
| **[baoyu-post-to-wechat](skills/04-publish/baoyu-post-to-wechat/)** | 17,825 | 1.56.1 | 发微信公众号 | `WECHAT_APP_ID`/`SECRET` |
| **[baoyu-post-to-weibo](skills/04-publish/baoyu-post-to-weibo/)** | 17,825 | 1.56.1 | 发微博 | 微博登录态 |
| **[baoyu-compress-image](skills/06-utilities/baoyu-compress-image/)** | 17,825 | 1.56.1 | 图片压缩 | — |
| **[baoyu-diagram](skills/01-visual-creation/baoyu-diagram/)** | 17,825 | — | SVG 结构化图表 | — |
| **[baoyu-youtube-transcript](skills/03-content-fetch/baoyu-youtube-transcript/)** | 17,825 | 1.1.0 | YouTube 字幕提取 | — |
| **[defuddle](skills/03-content-fetch/defuddle/)** | 7,521 | — | 网页正文提取（npm 包） | — |
| **[follow-builders](skills/05-data-api/follow-builders/)** | 4,124 | — | AI builders 内容追踪 | — |
| **[anything-to-notebooklm](skills/03-content-fetch/anything-to-notebooklm/)** | 1,611 | — | 多源内容→NotebookLM | — |
| **[opennews](skills/05-data-api/opennews/)** | 1,234 | 1.0.0 | 加密货币新闻聚合（6551 API） | `OPENNEWS_TOKEN` |
| **[opentwitter](skills/05-data-api/opentwitter/)** | 847 | 1.0.0 | X/Twitter 数据查询（6551 API） | `TWITTER_TOKEN` |
| **[x-article-publisher](skills/04-publish/x-article-publisher/)** | 756 | — | X 长文发布 | X 登录态 |
| **[knowledge-site-creator](skills/02-writing/knowledge-site-creator/)** | 325 | — | 一句话生成知识网站 | — |
| **[qiaomu-design-advisor](skills/06-utilities/qiaomu-design-advisor/)** | 233 | — | 偏执型设计顾问 | — |
| **[yt-search-download](skills/03-content-fetch/yt-search-download/)** | 107 | — | YouTube 搜索/下载 | — |
| **[skill-publisher](skills/02-writing/skill-publisher/)** | 24 | — | 一键发布 skill 到 GitHub | — |
| **[qiaomu-music-player-spotify](skills/06-utilities/qiaomu-music-player-spotify/)** | 21 | 1.0.0 | Spotify 播放控制 | — |
| **[bullet-viral-post](skills/02-writing/bullet-viral-post/)** | — | — | 中文 X 推文分点结构生成 | — |

总计：**34 个 skill**

---

## 维护

- 上游来源 + stars + version + needs_api 全在 [`sources.json`](sources.json)
- 跑 `bash sync.sh` 从上游拉最新 + 自动刷新 stars 和 version
- 添加新 skill：编辑 sources.json → 跑 sync.sh → commit + push

更多管理操作见私有仓库的 [majia-skill-manager](https://github.com/maojiebc/majia-private-skills/tree/main/skills/majia-skill-manager) skill。
