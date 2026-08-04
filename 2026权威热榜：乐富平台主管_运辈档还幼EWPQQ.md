乐富平台主管【Q-——333307——】乐富平台主管【 辋芷《888yx●vip》 】
乐富平台主管【Q-——333307——】乐富平台主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

> 作为一名开发者，拥有一个属于自己的技术博客，不仅是记录成长的方式，更是展示专业能力的绝佳窗口。今天手把手教你利用 GitHub Pages 和 Hexo，零成本搭建一个高速、免费的个人博客。

 为什么选择 Hexo + GitHub Pages？

- 完全免费：托管在 GitHub 服务器，无需购买云主机
- 极速访问：静态页面加载速度极快
- Markdown 友好：专注写作，无需关心排版
- SEO 友好：纯静态 HTML 结构，利于搜索引擎收录

 前期准备

在开始之前，请确保你的电脑已经安装了：
1. Node.js（版本需 ≥ 12.0）
2. Git（版本管理工具）

准备好后，打开命令行工具，我们开始。

 第一步：安装 Hexo 并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 第二步：本地预览博客

执行下面命令，浏览器访问 `http://localhost:4000` 即可看到默认博客界面：

```bash
hexo server
```

 第三步：创建 GitHub 仓库

1. 登录 GitHub，点击 New repository
2. 仓库名格式必须为：`你的用户名.github.io`
3. 选择 Public（公开），点击创建

 第四步：部署到 GitHub Pages

安装自动部署工具：

```bash
npm install hexo-deployer-git --save
```

修改根目录下的 `_config.yml` 文件，在文件末尾添加：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后执行一键部署：

```bash
hexo clean && hexo generate && hexo deploy
```

等待几十秒，访问 `https://你的用户名.github.io`，你的博客就已经上线了！

 常用指令速查

| 指令 | 作用 |
|------|------|
| `hexo new "文章标题"` | 创建新文章 |
| `hexo clean` | 清理缓存 |
| `hexo g` | 生成静态文件 |
| `hexo d` | 部署到远程仓库 |

---

💡 互动时间：你在搭建过程中遇到什么问题？或者有更好的博客主题推荐？欢迎在评论区留言交流！如果这篇文章对你有帮助，别忘了点个 Star 支持一下哦～

关注我，获取更多开发实战技巧与效率工具分享！

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E7%AC%AC%E4%B8%80%E7%83%AD%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90_%E6%80%9D%E7%A5%A8%E6%9E%97%E5%BA%95%E5%AD%9CEERJX.md

<img src="https://i.postimg.cc/tJTQ3j6x/lefu-00013.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/161d0215405d21a37bc601405ac2558f36accd41

<img src="https://i.postimg.cc/xTBDzB1n/lefu-00020.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/%E7%A1%AC%E6%A0%B8%E5%85%A8%E9%98%B6%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B5%8B%E9%80%9F_%E5%8F%B5%E6%8E%80%E6%8B%B7%E4%BB%AC%E7%87%8EGFGHJ.md

<img src="https://i.postimg.cc/xTBDzB1n/lefu-00020.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/commit/0345f50e56ece20b54dcac00fbe887a9d3a14694

<img src="https://i.postimg.cc/XJx6BJpR/lefu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
