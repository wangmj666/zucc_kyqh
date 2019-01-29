
###date:  1.29
###note:  
###前端技术构成
>1.结构：HTML（从语义的角度，描述页面结构）
>2.样式：CSS(从审美的角度，美化页面）
>3.行为：JavaScript(从交互的角度，提升用户体验）



很多 Web Framework 会自带一个简单的 Web Server，或者有些 Web Server 会自带一个简单的 Web
 Framework ，实际部署到服务器上开放使用的时候为了性能或者安全等多方面的考虑，可以把内置的 Web Server 换成其他的，比如 
Apache 或者 Nginx 。

早年常见的服务器端语言有：
开源的 PHPSun 公司的 JSP 中使用的 Java微软的 ASP 中使用的 VBScript

现在在这方面的应用热起来的语言有
 Python，对应常见的 Framework 包括知乎和Quora有用到的 Tornado（其实是自带 Framework 的 Web Server），社区很成熟的 Django （用户包括 Instagram、Pinterest）等Ruby，一般都用 Rails 这个 Framework，用户包括 Github、早期的 Twitter 等逆天的 JavaScript，有了 Node.js 这个平台，Web Server、服务器脚本和浏览器脚本全都可以用
 JavaScript 来写……Node.js上最常用的 Framework是Express微软家的则跟着 http://ASP.NET 转移到了C# 或者 Visual BasicErlang，擅长大规模的并发，不少游戏公司拿来写服务器，靠几十个工程师支撑几亿用户的WhatsApp也是用的这个~

几种常见的架构包括：
LAMP = Linux + Apache + MySQL + PHP（P还可能是Python或Perl。有时候L会改成W=Windows。），也就是服务器上的操作系统是 Linux，Web Server 用 Apache，数据库用 MySQL，服务器脚本用 PHP，这些都是开源技术，网站起步时用起来的成本会比较低，所以是普通网站里非常常见的架构（虽然对于发展得很大的网站会遇到很多瓶颈），Facebook就是这种，淘宝也曾经是。J2EE，Java 世界的架构，通常是企业用的（银行、大型公司,.etc），比较常见地还会搭配一种 UNIX 做操作系统，Apache 做 Web Server，Tomcat 转换 JSP 到 Java 给服务器程序用（其实它也自带 Web Server），Oracle 数据库等等。不一定拿来建站，常常用来提供企业里的各种需要用到网络的业务。我们学校教务系统就是用J2EE做的=。= 淘宝现在也是从LAMP转型到了这个。http://ASP.NET，微软家的架构，通常会搭配 Windows Server 操作系统，SQL Server 数据库，IIS 做 Web Server。StackOverflow和京东（曾经）就是这个架构。神奇的MEAN架构，MongoDB做数据库，Express做 Web Framework，Angular 做前端的 JavaScript 框架，Node.js 用于编写 Web Server。神奇之处在于这几个东西的语言都是 JavaScript （MongoDB的实现不是，但与外界沟通用的语言是）。因为是比较新的架构，还有待时间的考验，不过被很多人（尤其是靠 JavaScript 吃饭的前端程序猿们）热切关注。一般来说重点不在技术而且在乎成本的新网站比较喜欢用 LAMP，重视安全稳定和速度的企业和机构喜欢 J2EE，想省事的网站喜欢 http://ASP.NET，比较 Geek 的网站和创业公司喜欢折腾各种 Python、Ruby、Node.js世界的东西，Google 这样现成的技术都解决不了需求的超大型网站就自己折腾解决方案。

###完整作品
>http://2014.artsy.net/
https://codepen.io/Yakudoo/full/rJjOJx
https://codepen.io/pissang/full/geajpX
https://codepen.io/tsuhre/full/BYbjyg
https://wangyasai.github.io/Stars-Emmision/
https://pissang.github.io/papercut-box-art/
https://demo.marpi.pl/biomes/
https://pissang.github.io/voxelize-image/
http://echarts.baidu.com/examples/index.html#chart-type-globe
https://tympanus.net/Development/AudioVisualizers/（推荐戴耳机）

###第一天：为什么有那么多人要做前端？
>因为前端有许多模板可套，代码直观易上手。而且需求较大，做出来的内容可以很丰富。

###困惑：不会使用css,js.




	