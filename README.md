![](https://secure.gravatar.com/avatar/75021c22fa3eeeec2f5c9cd600b759c2?s=140&d=https://a248.e.akamai.net/assets.github.com%2Fimages%2Fgravatars%2Fgravatar-org-420.png)

# 开源城市计划

## 让互联网改变公共服务

互联网无时无刻不在制造信息，从微博，到微信，四面八方的信息涌入我们的生活，让我们在同胞遇难时得以伸出援助之手，在政府腐败时做一只看不见的上帝只眼，在面对强大的社会公器时能够挺起胸膛。在公共服务领域，这一变革或许才悄然开始。

开源城市计划（OSC.im）为这一目的的实现而努力，OSC将是一系列服务于公共服务的API集合，任何人可以在任何服务器托管这些API，并通过OSC项目的爬虫抓取并持久化这一公共数据库。

我们相信，互联网是人生而为人的自由实现。开源城市计划只是这一宏大叙事背后的点点星火，关注我们，或者加入我们。

## 如何实现

### 宏观实现

这一努力的基础是众多分类下的不同爬虫抓取网页信息并筛选后的结果。OSC有自己的数据库，并将接口与爬虫以分类的方式开源在OSC的Github的项目小组。

你可以依照自己感兴趣的类目查看这些爬虫的书写方式，或者Fork它，贡献自己的爬虫。


### 技术基础

目前，OSC的爬虫由Nodejs构建，Mongodb作为数据库解决方案，由Express包装API。在Pull Request时，可以参照案例中的已实现爬虫作为基础，把不同爬虫作为单独的模块提交到主干代码中。

如果你不是Node开发者，我们也欢迎你提交爬虫。
