# js-base
javascript 基本概念理解

###javascript 概述
> 如果从浏览器的范畴去理解“JavaScript”这个术语，它包含了截然不同的两个方面。一个是JavaScript的核心语言（[ECMAScript][0]），另一个是[DOM][1]（文档对象模型）。  

###HTML DOM
> * [HTML][2]是一种网页标记语言，它在DOM核心抽象概念之上，还定义了元素的含义，比如元素的className属性以及 document.body对象等。
* HTML规范同时还约束了元素之间的关系，例如无序列表ul元素中，只能以li元素作为子元素来表达列表项。还有就是禁止使用标准中未定义的元素和属性。

想了解更多关于[Document对象][4]、[Window对象][4]以及其他DOM元素的信息？请访问[Gecko DOM文档][5]。

###其他值得关注的API
* HTML标准中Window接口首次对setTimeout和setInterval函数进行定义。
* [XMLHttpRequest][6]. 用来发起异步HTTP请求的API。
* [CSS][7] 对象模型 用于将CSS规则抽象成对象。
* [WebWorkers][8]. 是用来并行计算的API。
* [WebSockets][9]. 是用来实现双向Socket通信的API。
* [Canvas 2D Context][9]. canvas元素的绘图API。

[0]: /lm-JS/js-base/blob/master/ECMAScript.md
[1]: /lm-JS/js-base/blob/master/DOM.md
[2]: http://www.whatwg.org/html
[3]: https://developer.mozilla.org/zh-CN/docs/Web/API/document
[4]: https://developer.mozilla.org/zh-CN/docs/Web/API/Window
[5]: https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model
[6]: https://dvcs.w3.org/hg/xhr/raw-file/tip/Overview.html
[7]: http://dev.w3.org/csswg/cssom/
[8]: http://www.whatwg.org/specs/web-workers/current-work/
[9]: https://html.spec.whatwg.org/multipage//comms.html#network
[10]: https://html.spec.whatwg.org/multipage/scripting.html#2dcontext
