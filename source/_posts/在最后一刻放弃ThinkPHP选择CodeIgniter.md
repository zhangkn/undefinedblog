---
title: 在最后一刻放弃ThinkPHP选择CodeIgniter
tags: 

  - php框架
permalink: choose-code-igniter-instead-of-thinkphp
id: 125
updated: '2012-12-27 21:05:03'
date: 2012-12-27 21:05:03
---

<p>最近需要给一家公司开发一个小型的商业网站，包括简单的会员管理、文章发布和商品信息更新等功能，其实这些东西直接用 PHP 写问题也不大，但是一来自己一直没有使用过 PHP 框架，二来这个项目可能会长期更新或者扩展，使用 PHP 框架开发可能会更具性价比。</p>
<p>关于哪个 PHP 框架好就不再赘述了，经过各种考虑之后我觉得使用 ThinkPHP（注意后面的剧情变化），主要出于两个方面的考虑：1、比 Zend 等框架更轻量 2、文档丰富，国人开发的框架，社区环境好</p>
<p>但是当我真的开始决定使用 ThinkPHP 时，却发现半天都摸不着门路。ThinkPHP 的文档的确丰富，但是却看不明白个所以然来。然而最直接促使我放弃 ThinkPHP 的原因，是我下载了一套 LAMP兄弟连 的 ThinkPHP 入门视频教程（真的很想接一句&ldquo;尼玛从此就踏上了不归路啊有木有啊有木有&rdquo;）。视频里的老湿从容的打开一个记事本，然后开始在键盘上啪啪啪，边用不标准的普通话说边打字，边用各种光怪陆离（抱歉我找不到合适的词语来形容）的发音来摧残我的大脑。</p>
<p>坚持看了一集之后，实在是受不了，完全没弄明白ThinkPHP究竟是怎么工作的，目录结构是怎样的。心想要不看看其他的框架。再对比了 YII 和 CodeIgniter 之后，果断选择了 CodeIgniter，因为它同样轻量，文档同样丰富（似乎比 ThinkPHP 差点，但是比其他的框架好多了）。</p>
<p>让我下定决心使用 CodeIgniter 开发的，是一个简单的介绍 CodeIgniter 的 DEMO：</p>
<p>http://codeigniter.org.cn/tutorials/watch/intro</p>
<p>同样是视频教程，差距咋就那么大呢！！！看完这个 DEMO，我对 CodeIgniter 怎么工作已经了解了大概，而 ThinkPHP 的那个教程，第一集40多分钟，愣是啥也没讲明白。</p>
<h2>题外话</h2>
<p>从大学接触第一本外国人写的技术书（C Primer Plus）之后，基本就再也没有看过国人写的技术书了。且不论翻译水平如何（现在已经基本看英文的原著了），就国内这些技术书的书名，就让你蛋疼半天。我曾经在知乎吐槽过：21天精通XXX，深入浅出XXX，XXX快速上手。典型的急功近利不知所云。尤其是大二学PHP的时候，翻了翻一本国产技术书（貌似是所谓明日科技出版社），妹的 PHP 输出 8进制数，截图清清楚楚的给你印着&ldquo;687&rdquo;&hellip;&hellip;这是侮辱我们智商呢咋地？</p>
<p>后来要学习新技术需要买书的时候，就只认 Apress、O'reilly 之类的了。</p>
<p>相信 CodeIgniter 不会让我失望。</p>