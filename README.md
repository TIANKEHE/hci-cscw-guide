# HCI / CSCW 会议论文写作与投稿流程

一页式滚动网站：直接双击 index.html 或运行本地 HTTP 服务。

- 上下滚动阅读，顶部固定章节导航；每个大 Part 单独采用一组柔和主题色。
- 无幻灯片翻页，保留评审分数模拟。
- 文档预览：docs/review-case.html，网页内可阅读，也可新窗口打开。
- 图片资料：assets/overleaf-example.png。
- 添加 PDF：放在 docs/ 下，再在 index.html 的 allResources() 中添加 `<a href="docs/filename.pdf" target="_blank">` 链接；也可将 iframe src 指向 PDF 路径。
- Overleaf 私人链接需登录访问，无法直接公开嵌入。导出 PDF 后可放入本地 docs。

快速运行：`python3 -m http.server 8000`，浏览器打开 `http://localhost:8000/`。

新增章节：读懂 RR（两篇论文逐章节对照）、如何审论文（官方五维度和两篇2027审稿笔记）。docs/medical-ai-review.html 为提供的医疗 AI 审稿记录全文浏览版。请仅在有权共享评审资料时公开部署。


## 新增：学术传播
“学术传播”Part 展示 Audience in the Loop 的公开项目网站，解释论文录取后项目网页、正式视频、视频预览、PDF、Slides 和 BibTeX 的准备方式。网站嵌入的 iframe 可能受第三方站点安全策略限制，请使用“新窗口打开”。


新增：CHI 2021–2026 年录取率趋势图、CSCW 统计口径说明、2023–2026 Best Paper 代表性目录及环境/数字媒体/交互设计筛选。奖项目录是精选，并非完整逐年清单。
