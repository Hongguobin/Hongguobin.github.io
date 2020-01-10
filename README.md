---
layout: page
title: 关于
permalink: /about
---

## 开始

1. Fork [wu-kan/wu-kan.github.io](https://github.com/wu-kan/wu-kan.github.io/fork)到你的仓库，并在设置里开启 gh-pages
2. 修改`_config.yml`为你自己的信息
3. 删除`_post/`下的博文和`public/image/`文件夹下的图片，开始写你自己的文章
4. 详细配置可以参见[这篇博文](https://wu-kan.github.io/posts/博客搭建/基于Jekyll搭建个人博客)
5. 欢迎<a class="github-button" aria-label="Star wu-kan/wu-kan.github.io on GitHub" href="https://github.com/wu-kan/wu-kan.github.io" data-icon="octicon-star" data-show-count="true">Star</a><a class="github-button" aria-label="Fork wu-kan/wu-kan.github.io on GitHub" href="https://github.com/wu-kan/wu-kan.github.io/fork" data-icon="octicon-repo-forked" data-show-count="true">Fork</a><a class="github-button" aria-label="Issue wu-kan/wu-kan.github.io on GitHub" href="https://github.com/wu-kan/wu-kan.github.io/issues" data-icon="octicon-issue-opened" data-show-count="true">Issue</a>

## 声明

除特别声明或转载外，所有博文采用[署名-相同方式共享 4.0 国际](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)协议进行许可。

博客基于[MIT License](https://github.com/wu-kan/wu-kan.github.io/blob/master/LICENSE)开源于[GitHub](https://github.com/wu-kan/wu-kan.github.io)。

## 致谢

## Feature/Todo

从[这个页面](https://magical-girl.site/)得到的灵感，目标是博客上除了文章和作为导航的 Live2D 之外尽量不出现其他的模块。

- [x] 完成博客文章标签页
- [ ] 完成博客文章分类页（分类暂时和标签没区别）
- [ ] 重写博客首页，做一个有意思的封面
- [x] 加入评论系统，暂时考虑用 valine+leancloud 实现
  - [x] 基于 valine 的阅读量统计
- [x] 不蒜子统计
- [x] [<i class="fab fa-font-awesome"></i>fontawesome-free](https://fontawesome.com/)
- [x] 全站搜索
- [x] [ribbon 动态背景](https://github.com/hustcc/ribbon.js)
- [x] 调整代码块风格，并加上代码选中按钮
- [x] 加入可以自动展开、标号的目录
  - [x] 目录标号
  - [ ] 自动展开
- [x] mermaid
  - [x] Markdown 代码扩展
- [x] $\KaTeX$
- [x] Live2D
  - [x] 加上切换 Live2D 显示/关闭的按钮
  - [ ] 使用自己搭建的 Live2D 后端 API
    - [ ] 收集一些 Live2D Model

## 初心

我曾做什么？

我正做什么？

我想做什么？

我该做什么？

> 章北海感到父亲的灵魂从冥冥中降落到飞船上，与他融为一体，他按动了操作界面上那个最后的按钮，心中默念出那个他用尽一生的努力所追求的指令：
>
> > “‘自然选择’，前进四！”

## 历程

### 正在进行 v2.4.1

- [ ] 所有插件完全使用 autoloader 加载，参数通过函数传给 js
- [ ] katex 行间公式（目前行间公式可通过 MathJax 实现，但是渲染性能不高）
- [x] 没有背景感觉好单调，Ribbon 默认开启回归（花 里 胡 哨
- [x] 赞赏按钮样式更新
- [x] 使用<https://loli.net>加速 gravatar 和 google 字体 css，感谢~
- [x] 网站字体更换为等宽字体+微软正黑体
- [x] 更换爱酱壁纸，pixiv id=71932901

### 2019.11.11 v2.4.0

- 修复`sidebar-overlay`失效的 Bug
- 修复赞助按钮点两次才出现的 Bug
- 修复 mermaid 不显示的 Bug
- 去掉正文部分的白色半透明背景
- 动态背景增加 nest 粒子动画（花里胡哨，默认关闭
- Ribbon 动态背景默认关闭，可在配置文件中去掉注释打开（花 里 胡 哨
- 博文显示信息增加 tag
- 变迁页面增加 tag、categories 图标及对应分类文章数量
- 页面显示适应宽屏显示器
- layout 增加
  - index
  - tag
  - page404

### 2019-08-30 v2.3.0

- 更换 cdn 为[jsDelivr](https://www.jsdelivr.com/)
- 升级 fontaswsomev4.7.0 至 fontawesome-freev5.10.2，支持的图标数量由 675 增加至 1535
- 所有脚本和插件 JSLoader 化，增加移植性和访问速度
- 界面调整
  - 正文部分增加背景，从而减少动态 ribbon 背景影响的阅读体验
  - sidebar 微调
- layout 删除 document 页

### 2019-07-06 v2.2.1

- prismjs 使用[UNPKG](https://unpkg.com)加速
- 删去 layout 中的 404 页（因为只需要引入 js 脚本）

### 2019-06-28 v2.2.0

- 博客结构微调
- 将大部分博客用到的 jscdn 换成 unpkg.com，感谢其提供的加速服务~
- 留言板加入友链

### 2019-05-03 v2.1.4

- valine 更新
  - 现在支持记录访问者 IP
  - 每次重新拉取评论者头像

### 2019-04-29 v2.1.3

- 页面样式微调，将 masthead 调矮，将标题字号改小

### 2019-03-20 v2.1.2

- 修复 sidebar 展开时回到顶部的问题

### 2019-03-18 v2.1.1

- 一些界面上的小调整

### 2019-03-01 v2.1.0

- 调整某些插件
- layout 新增 document 页，一个只开启$\KaTeX$而不引入任何其他样式的页面，主要是方便自己生成可打印的 ICPC 模板和一些课程报告
- layout 新增 404 页，可选择开启腾讯公益
- mermaid 支持 markdown 扩展了

### 2019-02-24 v2.0.1

- sidebar 的触发按钮样式换成了 bars，原来的样式更像是菜单
- 一点页面上的小调整

### 2019-02-23 v2.0.0

- 重构完成
- 正式开源

### 2019-02-19

- 模块化·初步
- 博客搜索实现

### 2019-02-01

- [署名-相同方式共享 4.0 国际](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)。
- 社会主义核心价值观点击特效，感谢[dujin](https://www.dujin.org/9088.html)。
- 打赏。

### 2019-01-31

- mathjax 换 katex
- post 访问量统计

### 2019-01-24

- 代码高亮
- 选中代码按钮
- 代码语言按钮

### 2019-01-23

- 加入文章目录到 SideBar

### 2019-01-22

- 加入 Ribbon 动态背景

### 2019-01-21

- 加入 valine 评论系统，留言页实现

### 2019-01-20

- 加入归档页

### 2019-01-19

- 加入标签页

### 2019-01-18

- 开始用 Jekyll 重构整个博客

折腾吧，折腾是才最好玩的。

### 2019-01-13

- 更换 Next.Muse 主题模板
- 少量修改页面自定义样式布局，主要是 sidebar
- 将网易云音乐 iframe 移动到 description，感觉挺有意思的

### 2019-01-12

- 将 NexT 版本更新至 v6.7.0

### 2018-12-23

- 页面字体修改
- 网易云音乐 iframe 加入 SideBar

### 2018-12-16

- 引入 mermaid 支持
- 修复部分 Latex 渲染的 Bug

### 2018-11-24

- 将 NexT 版本更新至 v6.5.0
- 用 Valine 更换失效的 Gitment 评论系统
- 加入 Leancloud 和 busuanzi 页面统计

### 2018-11-20

- 谷歌，百度搜索页面提交

### 2018-11-18

- 全局透明化
- 动态背景
- 页面加载动画
- Latex 支持

### 2018-11-16

- 主题由默认的 Landspace 换至 NexT v5.1.4
- 使用 Next.Pisces 主题模板
- 开始对网页进行自定义样式布局
- 尝试加入 Gitment，但初始化总是不成功

### 2018-11-15

- 在 Github 上成功部署博客
- 成功迁移[原 CSDN 博客](https://blog.csdn.net/w_weilan)上的所有文章
- live2d
