关于 AcFun Wiki 的一些个人愚见
===

我想很多人都很怀念 AcFun Wiki 在的那一段时间吧。很遗憾，AcWiki 由于神秘力量常年无法上线。那么，如果动态的 AcFun Wiki 因为这种原因无法上线的话，不如干脆把 Wiki 弄成静态的好了 … 放上 GitHub 什么的。这样什么力量大概都不怕了吧。

越来越多的 Blog 使用 Jekyll 作为网页生成器。和后起(?)的 Hexo 相比，Markdown 文件都是写好在源码后再生成的，而不是生成 HTML 后才能上 Github Pages，相对会可行一些。

项目地址：<https://github.com/acfunwiki/acfunwiki.github.io>

以上想法受[`xuanxue/xuanxue.github.io`](https://github.com/xuanxue/xuanxue.github.io)的启发。

一些会有些麻烦的地方
---
 1. 新的编辑者将必须拥有 Github 账号，懂得 `git` 使用的方法（或者学会使用 Github `Push Request`），还要懂 `Markdown` 语法，才能给 AcWiki 贡献内容了… 换言之，新用户又有了学习新东西的时间成本。这一点大概可以试着基于 `git` 写一个独立的客户端 — 不过大概会是个大工程吧。
 2. `Push Request` 以后就需要有人通过然后 `Merge` 入主线才行了 — 换言之就出现了审核的环节 — 对于长期参与修改的用户可以用个 bot 直接通过，但是新用户参与 Wiki 编辑就很遗憾需要专人审核了。
 3. Wiki 的模板系统应该怎么办呢… 暂时想不到。

请在该讨论串参与讨论：<http://hacfun.tv/t/6342065>
