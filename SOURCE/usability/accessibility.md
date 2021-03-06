---
layout: page
title: 可达性
permalink: accessibility.html
---

#可达性#

##可达性##

一个产品,如果对于任何人（无论能力）而言，都是非常容易掌握、理解并可以用之来完成他们的目标的话，那么这个产品就是可达的。一个成功的产品对于任何可能的使用者来说都应该是可达的。  

这些设计准则对于想要了解可达性的设计师而言是一个很好的起点。设计完全可达的产品是一个复杂的课题，需要深入研究。欲了解更多信息，请访问谷歌的[可达性网站](<http://www.google.com/accessibility/building/>)。 

**如何使你的产品更好地服务于身有残疾的用户？** 

首先，让你的产品使用辅助技术与用户进行交互。想象一下，你的产品在以下情况下使用的场景：

- 没有声音
- 没有颜色
- 启用高对比度模式
- 使用屏幕放大功能
- 使用屏幕阅读器（屏幕不可见）
- 语音控制
- 或者综合以上情况

然后再考虑在以下在影响可达性的关键领域使用的场景：导航，可读性，指导与反馈。

###导航###

**帮助用户快速和有效的浏览信息**。给网页添加导航是非常快速有效的（例如，跳到重点区段或回到主导航栏）？
优先展示最重要的信息，稍微修改下页面，比如把一个“创建”按钮放到顶部，可以使导航快得多。

**确保可触摸的元素起码需要有48*48的像素大小**。48x48（px，dp）是推荐的屏幕上可触摸元素的最小像素。同时在手机设计的时候注意屏幕上两个元素之间的间距。在大多数情况下，它应该是8dp或更多。

**支持无鼠标操作与标准手势导航**。你在网络界面上设计的每一个部分、任何用户的任务和每个用例都是键盘可达的并且可以在移动设备上通过基础的手势交互就可达的吗？盲人用户不能使用鼠标来通过视觉方式去探索界面。为了在手机上导航或者浏览不同的界面元素，他们需要使用的是键盘而不是鼠标。确保鼠标悬停信息对于不适用鼠标的用户一样是可达的。确保键盘快捷键都与平台标准相一致。

**管理用户关注的焦点**。你确定你的用户和他们关注的焦点在弹出框、警告和其他各类屏幕的导航中都不会迷失吗？同时考虑用户如何将关闭一个弹出窗口后返回到屏幕上，确保他们能够正确的返回弹出框出现之前的那个界面。


###可读性###

**确保你的产品在使用大字体的情况下依旧可用**。当用户放大屏幕或者字体的时候，你的文字信息是否依然清晰？那些必要的元素是否依旧可见，可用并且不重叠？你可以通过一些内建的操作系统/浏览器/应用程序的字体放大工具来检查这些问题。

**确保关键的文本信息具有足够的对比度**。在大多数情况下，“足够的对比度”是指有4.5:1的对比度。背景和文本或者关键元素之间足够的对比度能让所有的尤其是视力有缺陷的用户更容易看到你的信息。较小的文本需要大的对比度，而大标题可以容忍更大范围的颜色和背景（较小的对比度）。

**不要仅仅只使用颜色来传达重要信息**。对所有的色盲用户而言这个尤为重要。如果设计中使用色彩来传达特定的信息（例如，可视化交通信息：红色=交通拥堵，绿色=交通空闲），那么为用户提供另外一种获取相同信息的方法是很有必要的。除了使用颜色之外，再添加其他元素，如形状，图案，纹理，或文本。


**提供关于空间关系的线索**。靠空间或者布局传递的信息是否同时能够传递给一个正在导航该元素的盲人用户？考虑到一些辅助技术并不会显示元素之间的距离，提供一些额外的关于相关联的元素之间的线索，比如让它们共享一个相同的标题。

**提供视觉和听觉相互可替换的技术**。如果有音频元素，你是否提供了字幕、文本或另外其他的视觉方面的替代方法？该指导方针也适用于系统的警报声音，任何出现发光或者闪烁的地方都需要有对应的声音替代方法，反之亦然。


###指导和反馈###

**确保用户交互和控制界面很清楚明了**。是否所有的用户交互控制界面都有对应的文字标签、提示或者说明其用途的符号？是否你的专业术语在整个应用程序中都保持一致？先提供这些技术的描述说明，然后当给元素命名的时候，确保它在你的应用程序中的术语保持一致。

**提供的图像和视频的替代文字描述**。是否你只是依靠图形元素来传达的信息而不提供相关的文字描述？是否标签能够为人们提供足够的语义上下文（例如，不只是“下载”，而是“下载晚餐菜单”）？为所有的图片和图标提供备用的文字描述，并避免在一个正常工作的小插件上使用图像文本。

**提供指导手册和帮助文档**。当用户不知道一个元素的意义的时候，她/他是否可以找快速的找到帮助文档？如果一个关键的元素超时了，用户有激活它的方法吗？需要包含清楚明了并且容易找到的帮助文档，提供明确的上下文帮助，这样用户就可以很清楚的知道某个快捷方式或者手势是否可用的并且如何使用它。

**给你的链接赋予意义**。是否每一个链接的目的都清晰易懂？通用的锚文本像“点击这里”并不能很好地说明一个链接的目的。把链接的目的设置成链接的文本内容即可，解决“点击这里”的办法就是是将其改为诸如“设备设置”的这种链接。一些辅助技术可以让用户只是扫描链接，忽略了其他的内容，这样也可以使导航更加有效。

> 原文：[Accessibility](http://www.google.com/design/spec/usability/accessibility.html) 翻译：[fortianwei](https://github.com/fortianwei) 校对：[K0ST](https://github.com/K0ST)

