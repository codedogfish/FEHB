# 前端开发者常用的 Web 技术
# Web technologies employed by front-end developers

![](../images/web-tech-employed.jpg "http://www.2n2media.com/compare-front-end-development-and-back-end-development")

<cite> image source: <a href="http://www.2n2media.com/compare-front-end-development-and-back-end-development">http://www.2n2media.com/compare-front-end-development-and-back-end-development</a> </cite>

以下是前端开发者需要用到的 web 技术
The following web technologies are employed by front-end developers:

* 超文本标记语言（HTML）
* Hyper Text Markup Language (aka HTML)
* 层叠样式表（CSS）
* Cascading Style Sheets (aka CSS)
* 文档对象模型（DOM）
* Document Object Model (aka DOM)
* JavaScript 编程语言（ECMAScript 6，ES6，JavaScript 2015）
* JavaScript Programming Language (aka: ECMAScript 6, ES6, JavaScript 2015)
* Web API
* Web API's (aka HTML5 and friends or Browser API's)
* 超文本传输协议
* Hypertext Transfer Protocol (aka HTTP)
* 统一资源定位器（URL）
* Uniform Resource Locator's (aka URL)
* JavaScript 对象符号（JSON）
* JavaScript Object Notation (aka JSON)
* Web 内容访问性（WCAG） 和可访问的富因特网应用（ARIA）
* Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA)

这些技术的定义可以在下面的相关的文档和规格说明书中找到。想要一览所有 web 相关的规格说明可以访问[platform.html5.org](https://platform.html5.org/)。  
These technologies are defined below with the relevant documentation and specifications. For a comprehensive list of all web related specifications have a look at [platform.html5.org](https://platform.html5.org/).

##### 超文本标记语言（HTML）
##### Hyper Text Markup Language (aka HTML)

> 超文本标记语言，通常被简称为 HTML，是一种用于创建网页的标准标记语言。Web 浏览器可以读取 HTML 文件然后讲他们渲染成可视的或可听的网页。HTML 是根据想要呈现的内容来语义化的表述了网站的结构，这使得它是一个标记语言而不是一个编程语言。- wikipedia.org
> HyperText Markup Language, commonly referred to as HTML, is the standard markup language used to create web pages. Web browsers can read HTML files and render them into visible or audible web pages. HTML describes the structure of a website semantically along with cues for presentation, making it a markup language, rather than a programming language. - wikipedia.org

相关规格说明/文档
Most relevant specifications / documentation:

* [HTML5 from W3C](http://www.w3.org/TR/html5/) : 5th major revision of the core language of the World Wide Web
* [The elements of HTML from the Living Standard](https://html.spec.whatwg.org/multipage/semantics.html#semantics)
* [The HTML Syntax](https://html.spec.whatwg.org/multipage/syntax.html#syntax) from the Living Standard
* [All W3C HTML Spec](http://www.w3.org/standards/techs/html#w3c_all)
* [HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [HTML attribute reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
* [Global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

##### 层叠样式表（CSS）
##### Cascading Style Sheets (aka CSS)

> 层叠样式表（CSS）是一个样式表语言用于描述标记语言生成的文档的外观和格式。虽然一般都用它来改变基于 HTML 和 XHTML 的网页和用户界面样式，但是它也可以应用于其他类 XML 文档，包括 普通 XML, SVG 和 XUL。也就是说，HTML，JavaScript 和 CSS 做一个基石被用于构建大部分网站的可视化网页，web 应用的用户界面和许多手机应用的用户界面。- wikipedia.org
> Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document written in a markup language. Although most often used to change the style of web pages and user interfaces written in HTML and XHTML, the language can be applied to any kind of XML document, including plain XML, SVG and XUL. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications. - wikipedia.org

相关规格说明/文档
Most relevant specifications / documentation:

* [Cascading Style Sheets Level 2 Revision 2 (CSS 2.2) Specification](https://drafts.csswg.org/css2/)
* [Selectors Level 3](http://www.w3.org/TR/css3-selectors/)
* [All W3C CSS Specifications](http://www.w3.org/Style/CSS/current-work#roadmap)
* [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

##### 文档对象模型（DOM）
##### Document Object Model (aka DOM)

> 文档对象模型（DOM）是一个跨平台和非语言相关的表现和交互协议，它表现为 HTML，XHTML 和 XML 文档对象。每个文档节点被组织为一个树形结构，被称为 DOM 树。DOM 树中的对象可以通过对象上的方法来定位和维护。DOM 的公共接口被定义在它自己应用编程接口（API）中。- wikipedia.org
> The Document Object Model (DOM) is a cross-platform and language-independent convention for representing and interacting with objects in HTML, XHTML, and XML documents. The nodes of every document are organized in a tree structure, called the DOM tree. Objects in the DOM tree may be addressed and manipulated by using methods on the objects. The public interface of a DOM is specified in its application programming interface (API). - wikipedia.org

相关规格说明/文档
Most relevant specifications / documentation:

* [W3C DOM4](http://www.w3.org/TR/2014/WD-dom-20140204/)
* [DOM Living Standard](https://dom.spec.whatwg.org/)
* [Document Object Model (DOM) Level 3 Events Specification](http://www.w3.org/TR/2013/WD-DOM-Level-3-Events-20131105/)

##### JavaScript 编程语言（ECMAScript 6，ES6，JavaScript 2015）
##### JavaScript Programming Language (aka: ECMAScript 6, ES6, JavaScript 2015)

> JavaScript 是一个高级动态弱类型编程语言。它在 ECMAScript 语言规格文档中被标准化。与 HTML 和 CSS 一起，它是万维网至关重要的三个技术之一。大部分网站会使用它，它也被所有现代浏览器以非插件形式直接支持。JavaScript 的方法是基于原型并且属于一等公民，这使得它是一个多范式语言，支持面向对象，面向命令和面向过程等编程模式。它的 API 可以处理文本、数组、日期和正则表达式，但不包括 IO，例如网络、存储、图形等，当然这也取决于它的宿主环境。- wikipedia.org
> JavaScript is a high level, dynamic, untyped, and interpreted programming language. It has been standardized in the ECMAScript language specification. Alongside HTML and CSS, it is one of the three essential technologies of World Wide Web content production; the majority of websites employ it and it is supported by all modern web browsers without plug-ins. JavaScript is prototype-based with first-class functions, making it a multi-paradigm language, supporting object-oriented, imperative, and functional programming styles. It has an API for working with text, arrays, dates and regular expressions, but does not include any I/O, such as networking, storage or graphics facilities, relying for these upon the host environment in which it is embedded. - wikipedia.org

相关规格说明/文档
Most relevant specifications / documentation:

* [ECMAScript® 2015 Language Specification](http://www.ecma-international.org/ecma-262/6.0/)

##### Web API's
##### Web API's (aka HTML5 and friends)

> 当使用 JavaScript 为 web 编写代码时，你会发现它有许许多多的 API。以下是一个所有接口的列表，你可以用来开发你的 web 应用或站点。- Mozilla
> When writing code for the Web using JavaScript, there are a great many APIs available. Below is a list of all the interfaces (that is, types of objects) that you may be able to use while developing your Web app or site. - Mozilla

相关规格说明/文档
Most relevant documentation:

* [Web API Interfaces](https://developer.mozilla.org/en-US/docs/Web/API)

##### 超文本传输协议
##### Hypertext Transfer Protocol (aka HTTP)

> 超文本传输协议是一个应用协议用于分发、协作、超媒体信息系统。HTTP 是一个万维网上用于数据传输的基础。- wikipedia.org
> The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web. - wikipedia.org

相关规格说明
Most relevant specifications:

* [Hypertext Transfer Protocol -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
* [Hypertext Transfer Protocol version 2 draft-ietf-httpbis-http2-16](https://tools.ietf.org/html/draft-ietf-httpbis-http2-16)

##### 统一资源定位器（URL）
##### Uniform Resource Locator's (aka URL)

> 一个统一资源定位器（URL）(也叫网络地址）是一个资源的引用来规定资源在一个计算机网络中的位置和检索它的机制。一个 URL 是统一资源定位符（URI）,[3]的一种特殊形式，虽然很多人把这两个给搞反了。一个 URL 表示了访问一个资源的意义，并不是每一个 URL 都是真正的 URI。[4][5] URL 通常用于引用网页（http），但也会用于文件传输（ftp）,电子邮件（mailto），数据库访问（JDBC）还有其他应用。- wikipedia.org
> A uniform resource locator (URL) (also called a web address) is a reference to a resource that specifies the location of the resource on a computer network and a mechanism for retrieving it. A URL is a specific type of uniform resource identifier (URI),[3] although many people use the two terms interchangeably. A URL implies the means to access an indicated resource, which is not true of every URI.[4][5] URLs occur most commonly to reference web pages (http), but are also used for file transfer (ftp), email (mailto), database access (JDBC), and many other applications. - wikipedia.org

相关规格说明
Most relevant specifications:

* [Uniform Resource Locators (URL)](http://www.w3.org/Addressing/URL/url-spec.txt)
* [URL Living Standard](https://url.spec.whatwg.org/)

##### JavaScript 对象符号（JSON）
##### JavaScript Object Notation (aka JSON)

> JSON, 有时候 JavaScript 对象符号， 是一种用于表示可读的、键值对形式的数据传输对象的开放数据标准。它是异步浏览器/服务器数据交换的首选数据格式，用于替代 XML （用于 AJAX）。虽然在 JavaScript 脚本语言中被原生支持，但 JSON 是一个非语言相关的数据格式。在各种编程语言都有用于转换和生成 JSON 数据的代码。JSON 格式原来是 Douglas Crockford 定义的。现在在互相竞争的 RFC 7159 和 ECMA-404 中被描述。ECMA 标准是最简化的，指规定了允许的语法格式，相应的，RFC 中则提供了一些语意和安全方面的考虑。 JSON 的 官方因特网媒体类型是 application/json。JSON 文件的扩展名是 .json。 - wikipedia.org
> JSON, sometimes JavaScript Object Notation, is an open standard format that uses human-readable text to transmit data objects consisting of attribute–value pairs. It is the primary data format used for asynchronous browser/server communication (AJAJ), largely replacing XML (used by AJAX). Although originally derived from the JavaScript scripting language, JSON is a language-independent data format. Code for parsing and generating JSON data is readily available in many programming languages. The JSON format was originally specified by Douglas Crockford. It is currently described by two competing standards, RFC 7159 and ECMA-404. The ECMA standard is minimal, describing only the allowed grammar syntax, whereas the RFC also provides some semantic and security considerations. The official Internet media type for JSON is application/json. The JSON filename extension is .json. - wikipedia.org

相关规格说明
Most relevant specifications:

* [Introducing JSON](http://json.org/)
* [The JSON Data Interchange Format](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)
* [JSON API](http://jsonapi.org/)

##### Web 内容可访问性指南（WCAG）和 可访问的富因特网应用（ARIA） 
##### Web Content Accessibility Guidelines (aka WCAG) & Accessible Rich Internet Applications (aka ARIA)

> 可访问性是指针对有缺陷用户的产品、设备、服务或环境的设计。可访问性设计的概念确保“直接访问”（无辅助）和“非直接访问”意味着兼容辅助技术（比如：计算机屏幕阅读器）。- wikipedia.org
> Accessibility refers to the design of products, devices, services, or environments for people with disabilities. The concept of accessible design ensures both “direct access” (i.e. unassisted) and "indirect access" meaning compatibility with a person's assistive technology (for example, computer screen readers). - wikipedia.org

* [Web Accessibility Initiative (WAI)](http://www.w3.org/WAI/)
* [Web Content Accessibility Guidelines (WCAG) Current Status](http://www.w3.org/standards/techs/wcag#w3c_all)
* [Accessible Rich Internet Applications (WAI-ARIA) Current Status](http://www.w3.org/standards/techs/aria#w3c_all)


