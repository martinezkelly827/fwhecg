乐富开户主管【Q-——333307——】乐富开户主管【 辋芷《888yx●vip》 】
乐富开户主管【Q-——333307——】乐富开户主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是否想拥有一个完全免费、无广告、可自定义的个人技术博客？GitHub Pages + Hexo 组合是程序员最青睐的解决方案。本文将带你避开所有坑，30分钟完成搭建。

 为什么选择 Hexo + GitHub Pages？

- 完全免费：托管在 GitHub 服务器，无需购买云主机
- 极速访问：全球 CDN 加速，国内访问速度优秀
- Markdown 写作：专注内容，无需关心排版
- SEO 友好：静态页面天然利于搜索引擎收录
- 版本管理：文章自动同步 Git 仓库，历史可追溯

 搭建前的环境准备（Windows/macOS 通用）

1. 安装 Node.js（建议 v18+）和 Git
2. 注册 GitHub 账号并创建仓库，命名格式：`用户名.github.io`
3. 安装 Hexo 命令行工具：`npm install -g hexo-cli`

 五步快速部署指南

第一步：初始化博客
```bash
hexo init my-blog && cd my-blog
npm install
```

第二步：关联 GitHub 仓库
修改 `_config.yml` 文件中的 deploy 配置：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/用户名.github.io.git
  branch: main
```

第三步：本地预览
```bash
hexo clean && hexo generate && hexo server
```
浏览器访问 `http://localhost:4000` 查看效果

第四步：一键部署上线
```bash
npm install hexo-deployer-git --save
hexo deploy
```

第五步：绑定自定义域名（可选）
在仓库 Settings → Pages 中填入你的域名，并在域名服务商添加 CNAME 解析。

 进阶优化技巧（提升收录与体验）

- SEO 配置：安装 `hexo-generator-seo-friendly-sitemap` 插件自动生成 sitemap
- 图片懒加载：使用 `hexo-lazyload-image` 加快首屏速度
- 代码高亮：启用 Hexo 内置的 highlight.js 主题
- 文章置顶：在 front-matter 中添加 `sticky: true` 参数

 遇到问题怎么办？

常见报错处理方案：
- `port 4000 already in use` → 执行 `hexo server -p 5000`
- `Deployer not found` → 重新执行安装 deployer 插件命令
- 样式丢失 → 清空浏览器缓存并执行 `hexo clean`

 动手实践，打造你的专属博客

完成部署后建议立即进行：添加「关于」页面 → 修改默认主题 → 发布第一篇技术笔记。遇到任何问题欢迎在评论区留言，我会第一时间回复！

如果觉得教程有用，请点赞+转发，让更多开发者告别博客搭建烦恼。你的支持是我持续输出高质量教程的最大动力！

---

本文同步发布于我的博客，搜索「Hexo博客搭建」可获取更新版本及源码仓库。

相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E7%A7%91%E6%8A%80%E6%80%BB%E7%BB%93%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C_%E6%B6%8E%E8%B0%86%E8%A7%85%E9%80%BC%E8%B0%A2YFTTA.md

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />

相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/e63e11d3087a052b1cd666e08a00898c738a395d

<img src="https://i.postimg.cc/xTBDzB1n/lefu-00020.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/%E7%A1%AC%E6%A0%B8%E5%85%A8%E9%98%B6%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C_%E9%99%B6%E6%95%9B%E6%AD%89%E7%A9%86%E8%90%84AAAPD.md

<img src="https://i.postimg.cc/50pWQ0XN/lefu-00012.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/68cfea655ebfda1eae281f963a6d77681ca1d0b5

<img src="https://i.postimg.cc/1XjxMj0W/lefu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
