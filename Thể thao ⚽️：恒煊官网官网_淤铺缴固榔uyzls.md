恒煊官网官网【Q-——333307——】恒煊官网官网【 辋芷《888yx●vip》 】
恒煊官网官网【Q-——333307——】恒煊官网官网【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hugo 保姆级教程

> 想拥有一个免费、高效、可定制的个人博客？别再纠结服务器和域名了，用 GitHub Pages 加 Hugo 框架，十分钟就能上线你的第一个站点。本教程将带你完整走一遍流程，从环境配置到成功部署，小白也能轻松上手。

 为什么选择 GitHub Pages 和 Hugo？

- 零成本：完全免费，无需购买服务器和数据库。
- 构建极快：Hugo 是目前公认的构建速度最快的静态站点生成器，数千篇文章也能秒级生成。
- 版本管理：基于 Git 的天然优势，文章更新有迹可循，写错了随时回滚。
- 专注写作：告别复杂的后台管理，只用 Markdown 语法就能记录技术点滴。

 部署前的准备工作

在开始之前，请确认你的电脑上已经安装了以下工具：

1. Git：用于代码提交和版本管理。
2. Hugo：在终端执行 `brew install hugo`（Mac）或去官网下载对应安装包（Windows）。
3. GitHub 账号：没有的话先去官网注册一个。

 从零搭建：四步搞定个人站点

 第一步：创建一个 Hugo 站点

打开终端，执行以下命令：

```bash
hugo new site my-blog
cd my-blog
```

这个命令会在当前目录下创建一个名为 `my-blog` 的文件夹，并初始化好基本的站点结构。

 第二步：选择一个漂亮的主题

Hugo 官网有大量开源主题供你选择。这里推荐进入主题市场，找到心仪的样式后，在站点根目录执行：

```bash
git init
git submodule add https://github.com/作者/主题名.git themes/你的主题
```

然后在 `config.toml` 配置文件中，将 `theme` 参数改为你添加的主题名称。

 第三步：编写并生成你的第一篇文章

在站点根目录执行：

```bash
hugo new posts/hello-world.md
```

用任意文本编辑器打开 `content/posts/hello-world.md`，删掉默认的草稿配置（`draft: true` 改为 `false`），写下一段属于你的文字，保存后执行：

```bash
hugo -D
```

该命令会生成静态文件到 `public` 文件夹。

 第四步：推送到 GitHub 并开启 Pages

1. 在 GitHub 上新建一个仓库，命名为 `用户名.github.io`（注意：必须与你的用户名一致）。
2. 在本地执行命令将 `public` 文件夹推送到该仓库：

```bash
cd public
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/用户名/用户名.github.io.git
git push -u origin main
```

推送成功后，等待一分钟左右，访问 `https://用户名.github.io`，你的个人博客就正式上线了。

 日常写作与更新流程

后续每次想要发布新文章，只需重复以下三条命令：

```bash
hugo new posts/新文章.md
 写入内容后...
hugo -D
git add . && git commit -m "更新内容"
git push
```

整个过程不需要碰服务器，也不需要数据库，极其干净利落。

 进阶优化：自定义域名

如果你嫌默认域名不够个性，可以在仓库的 `Settings` -> `Pages` 中填入你的自定义域名，并在域名服务商处添加一条 CNAME 解析记录指向 `用户名.github.io`，部署自动开启 HTTPS，安全性和品牌感都能一步到位。

 写在最后

GitHub Pages 加 Hugo 的组合，对技术博主和轻量级写作场景非常友好，不但省下了服务器运维的精力，还能帮你沉淀写作习惯。如果你在部署过程中遇到了问题，欢迎在评论区留言，或者去 GitHub 社区搜索相关资料。

希望这篇教程能帮你顺利搭好第一间数字小屋，期待在互联网的某个角落与你相遇。

相关推荐：

https://github.com/gutierrezjessica05/nukelg/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%B2%90%E9%B8%A3%E5%9C%B0%E5%9D%80%E6%B3%A8%E5%86%8C_%E6%97%A2%E9%83%A8%E7%83%AB%E5%B1%AF%E8%B1%AAuneye.md

<img src="https://i.postimg.cc/wv0Xd4pr/hengxuan-00008.png" />

相关推荐：

https://github.com/gutierrezjessica05/nukelg/commit/cc6db468d8539e8e0e4509d200c22e311f406f16

<img src="https://i.postimg.cc/FRDyQC4n/hengxuan-00007.png" />
相关推荐：

https://github.com/parkergloria9526/anwwee/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%B2%90%E9%B8%A3%E5%9C%B0%E5%9D%80%E5%BC%80%E6%88%B7_%E6%8E%A8%E9%81%A3%E6%B6%AF%E7%A2%8C%E5%8F%B7tyyyy.md

<img src="https://i.postimg.cc/Qt0QrY32/hengxuan-00010.png" />
相关推荐：

https://github.com/parkergloria9526/anwwee/commit/c89d120b10671b5ebe03f0acd662aa56f2db2856

<img src="https://i.postimg.cc/RFX7zpBQ/hengxuan-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
