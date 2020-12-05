---
typora-root-url: ./
typora-copy-images-to: ./images
title: 博客搭建方案
tags: 
  - 博客
  - hexo
categories: '博客'
---
​    

# 搭建方案

## hexo

[文档 | Hexo](https://hexo.io/zh-cn/docs/index.html)



## 搭建

[零基础搭建博客 (juejin.cn)](https://juejin.cn/post/6844904034860531720)



### 主题

[Themes | Hexo](https://hexo.io/themes/)

Next

[iissnan/hexo-theme-next: Elegant theme for Hexo. (github.com)](https://github.com/iissnan/hexo-theme-next)

[IIssNan's Notes](https://notes.iissnan.com/)

[开始使用 - NexT 使用文档 (iissnan.com)](https://theme-next.iissnan.com/getting-started.html)

[主题配置 - NexT 使用文档 (iissnan.com)](http://theme-next.iissnan.com/theme-settings.html#fonts-customization)



Next社区版本

[theme-next/hexo-theme-next: Elegant and powerful theme for Hexo. (github.com)](https://github.com/theme-next/hexo-theme-next)

[Hexo博客搭建全攻略(二)：NexT主题配置 - 简书 (jianshu.com)](https://www.jianshu.com/p/d95cff938277)

<!-- more -->

[theme-next/awesome-next: 主题/插件](https://github.com/theme-next/awesome-next#live-preview)

[NexT - Theme for Hexo (theme-next.js.org)](https://theme-next.js.org/)



simpleblock

[王子亭的博客 (jysperm.me)](https://jysperm.me/)

[jysperm/hexo-theme-simpleblock: Hexo theme of jysperm's blog. (github.com)](https://github.com/jysperm/hexo-theme-simpleblock)



[tufu9441/maupassant-hexo: A simple Hexo theme forked from icylogic. (github.com)](https://github.com/tufu9441/maupassant-hexo)

[大道至简——Hexo简洁主题推荐 | 屠城 (haomwei.com)](https://www.haomwei.com/technology/maupassant-hexo.html)



[Molunerfinn/hexo-theme-melody: A simple & beautiful & fast theme for Hexo. (github.com)](https://github.com/Molunerfinn/hexo-theme-melody)

[Do what you love,Love what you do | MARKSZのBlog (molunerfinn.com)](https://molunerfinn.com/)





[sabrinaluo/hexo-theme-replica: Github style replication for hexo theme](https://github.com/sabrinaluo/hexo-theme-replica)

[小白妹妹写代码 (hiitea.io)](https://hiitea.io/tech/)

## vue-press

### 主题

[vuepress-theme-reco (recoluan.com)](https://vuepress-theme-reco.recoluan.com/)

[xugaoyi/vuepress-theme-vdoing: 🚀一款简洁高效的VuePress 知识管理&博客(blog) 主题 (github.com)](https://github.com/xugaoyi/vuepress-theme-vdoing)

[有哪些好看的vuepress主题？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/366270141)



## 掘金



```yml
---
# 主题列表：juejin, github, smartblue, cyanosis, channing-cyan, fancy, hydrogen, condensed-night-purple, greenwillow, v-green, vue-pro
# 贡献主题：https://github.com/xitu/juejin-markdown-themes
theme: juejin
highlight: juejin
---

```



```jsx
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;

```



# 多平台发布方案

一键多发: 

[写博客多平台发布简书、掘金、CSDN | 码农家园 (codenong.com)](https://www.codenong.com/cs107105909/)

> markdown 通过PicGo图片上传到Github
>
> 公共jsdelivr访问Gtihub图片: https://cdn.jsdelivr.net/gh/用户名/仓库名@分支/路径 | gitee也可以
>
> 掘金复制markdown后会解析图片上传到掘金自己的CDN(但是外网的图片)

[onblog/BlogHelper: 帮助国内用户写作的托盘助手，一键发布本地文章到主流博客平台（知乎、简书、博客园、CSDN、SegmentFault、掘金、开源中国），剪贴板图片一键上传至图床（新浪、Github、图壳、腾讯云、阿里云、又拍云、七牛云）](https://github.com/onblog/BlogHelper)







公共CDN图片分发方案: **掘金会自动解析生成图片CDN**

 [写博客多平台发布简书、掘金、CSDN | 码农家园 (codenong.com)](https://www.codenong.com/cs107105909/)

[Typora+PicGo实现自己的图片自动上传教程 (juejin.cn)](https://juejin.cn/post/6844904088862212103)

[Typora+Vue主题+Gitee图床轻松写文章 (juejin.cn)](https://juejin.cn/post/6901525872156065806#heading-17)

[Github+jsDelivr+PicGo 打造稳定快速、高效免费图床 - 知乎 · 语雀 (yuque.com)](https://www.yuque.com/xiaodongxier/docs/49917e45-c126-4db6-936a-040237e39c92?language=zh-cn)

[Github Actions自动部署Hexo博客 | 唐瑞平 (tangruiping.com)](https://www.tangruiping.com/post/github-actions-hexo.html#密钥生成)

[jsdelivr 出现 Failed to fetch version info for 原因分析 | 唐瑞平 (tangruiping.com)](https://www.tangruiping.com/post/jsdelivr-failed-to-fetch-version-info-for.html)

[免费CDN：jsDelivr + Github | TRHX'S BLOG (itrhx.com)](https://www.itrhx.com/2019/02/10/A18-free-cdn/)

后缀必须改个名称: **https://cdn.jsdelivr.net/gh/qingshan-dev/blog@main/images/20201203234813.png**

> 否则提示fetch @latest 失败, 网上说需要发布, release后的tag也是分支





Markdown分发工具: 

[让排版变 Nice (mdnice.com)](https://www.mdnice.com/)	

[文章排版经验及工具 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/148160386)
