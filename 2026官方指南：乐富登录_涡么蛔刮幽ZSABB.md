乐富登录【Q-——333307——】乐富登录【 辋芷《888yx●vip》 】
乐富登录【Q-——333307——】乐富登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南（2025最新）

> 想拥有一个完全属于自己的技术博客？不想购买服务器和维护数据库？GitHub Pages + Hexo 是目前最流行的免费建站方案。本文将用最短的时间，带你完成从环境配置到发布上线的全过程。

 为什么选择 Hexo + GitHub Pages？

免费托管：GitHub Pages 提供无限流量的静态网站托管，无需购买云服务器。  
极速访问：生成纯静态 HTML，配合 CDN 加速，国内访问速度表现优秀。  
版本管理：文章内容以 Markdown 存储，天然支持 Git 版本追踪，写坏了一键回滚。  
生态丰富：拥有超过 400 个主题和插件，二次开发成本极低。

 第一步：环境准备（5分钟）

1. 安装 Node.js（推荐 v18 以上 LTS 版本）  
2. 安装 Git，并配置全局用户信息  
3. Windows 用户建议安装 Git Bash，体验类 Linux 命令行

 第二步：Hexo 初始化与部署

创建一个新博客项目并进入目录，依次执行以下命令：

```bash
npm install hexo-cli -g
hexo init my-blog
cd my-blog
npm install
hexo server
```

打开 `http://localhost:4000` 看到默认页面即为成功。接下来，修改 `_config.yml` 中的 url 字段为 `https://你的用户名.github.io`。

 第三步：推送 GitHub 与自动部署

在 GitHub 新建一个仓库，命名为 `你的用户名.github.io`。安装自动化部署插件：

```bash
npm install hexo-deployer-git --save
```

修改站点配置文件中的 deploy 参数，指定仓库地址后运行 `hexo clean && hexo g && hexo d`，第一次访问你的专属域名需要等待 1-2 分钟解析。

 进阶优化：自定义域名与 SEO

- 添加 CNAME 文件指向你的个性域名  
- 安装 `hexo-generator-sitemap` 插件，自动生成站点地图  
- 通过百度搜索资源平台提交链接，加速收录

 写在最后

看到这里，你已经掌握了博客搭建的核心流程。如果你在操作中遇到版本兼容问题，欢迎在评论区留言你的 Node 版本号。你是否也在纠结主题选择？关注我，下一期将带来 5 个被严重低估的高颜值 Hexo 主题评测，帮你快速建好门面。

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E5%AE%98%E7%BD%91%E6%B1%87%E6%80%BB%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E8%AF%B4%E7%A9%BA%E7%98%B8%E8%B0%B0%E5%8F%8BGTTTA.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />

相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/7993748c38d8a99a432ce7ee1d51b811e640ee67

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E6%9D%83%E5%A8%81%E8%A7%A3%E6%9E%90%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E7%BD%91%E5%9D%80_%E6%83%BA%E9%99%85%E4%B8%80%E5%B1%B9%E4%BF%A3WWJJD.md

<img src="https://i.postimg.cc/c4vG6dZ5/lefu-00018.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/ead851f9814530e8d3af5940ca988ae475bf7710

<img src="https://i.postimg.cc/XJx6BJpR/lefu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
