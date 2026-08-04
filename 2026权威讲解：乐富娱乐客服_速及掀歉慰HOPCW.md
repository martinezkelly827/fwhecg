乐富娱乐客服【Q-——333307——】乐富娱乐客服【 辋芷《888yx●vip》 】
乐富娱乐客服【Q-——333307——】乐富娱乐客服【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整指南

> 还在羡慕别人的技术博客？其实用 GitHub Pages + Hexo，30分钟就能搞定一个免费、高效、支持自定义域名的个人站点。本文手把手教你完成搭建，还附赠 SEO 优化技巧。

 为什么选择 GitHub Pages + Hexo？

很多开发者想写博客，却卡在“服务器费用”或“维护成本”上。GitHub Pages 免费托管静态页面，Hexo 生成速度快、主题丰富，两者搭配堪称“零成本建站神器”。

核心优势：
- 完全免费，无需购买服务器
- 支持绑定自定义域名
- 基于 Git 管理，版本回溯简单
- 海量主题和插件，灵活扩展

 第一步：环境准备

安装 Node.js（建议 LTS 版本）和 Git。安装完成后，在终端验证：

```bash
node -v
git --version
```

 第二步：安装并初始化 Hexo

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面即为成功。

 第三步：部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名为 `用户名.github.io`
2. 修改站点配置文件 `_config.yml`：

```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
  branch: main
```

3. 安装部署插件并上传：

```bash
npm install hexo-deployer-git --save
hexo d
```

访问 `https://用户名.github.io`，博客正式上线！

 第四步：SEO 优化与收录技巧

想让文章被百度、谷歌收录，需要注意：

1. TDK 设置：每篇文章自定义 Title、Description、Keywords
2. URL 优化：使用 `permalink: :year/:month/:title/` 格式
3. 提交站点地图：安装 `hexo-generator-sitemap`，到百度站长平台提交链接
4. 内链建设：文章间互相推荐，提升爬虫抓取深度

 额外建议：提升博客质感

- 标签与分类：让内容结构更清晰
- 开启阅读统计：使用不蒜子或 LeanCloud
- 图片懒加载：使用 `hexo-lazyload-image` 插件

---

你的技术积累，值得被更多人看到。用 GitHub Pages 搭起第一个博客，坚持输出，时间会给你答案。

如果你在搭建过程中遇到报错，或者有更好的优化技巧，欢迎在评论区留言交流。点赞 + 收藏，方便下次照着做！

相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E7%A7%91%E6%8A%80%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%AE%98%E6%96%B9_%E5%A5%96%E8%86%B3%E5%B2%A9%E6%AD%A2%E5%AE%B6GTNVP.md

<img src="https://i.postimg.cc/wT1Y39gp/lefu-00019.png" />

相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/14afc9a2d421a74c3d1f6ea7b2eb8d634fa46af0

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/2026%E7%A7%91%E6%8A%80%E7%83%AD%E6%A2%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E7%A8%8D%E7%BF%81%E8%BE%83%E9%B8%A5%E7%9B%8EDXDKY.md

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/790139a0d1694994dd9b164cbcd340a40e519722

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
