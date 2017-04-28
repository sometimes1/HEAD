
以下是基本，极简主义网站的基本标签：

< meta  charset = “ utf-8 ” >
< meta  http-equiv = “ x-ua-compatible ”  content = “ ie = edge ” >
< meta  name = “ viewport ”  content = “ width = device-width，initial-scale = 1，shrink-to-fit = no ” >
 <！ -上述3个元标记*必须先在头部; 任何其他头部内容必须* * *标签之后- > 
< title >页面标题</ title >
元素

<！ -文件标题- > 
< title >页面标题</ title >

<！ -用于文档中包含的所有相关URL的基本URL - > 
< base  href = “ https://example.com/page.html ” >

<！ -外部CSS - > 
< link  rel = “ stylesheet ”  href = “ styles.css ” >

<！ -文档中的CSS - >
 < style > 
/ * ... * / </ style >  


<！ - JavaScript - > 
< script  src = “ script.js ” > </ script >
< noscript > <！ -没有JS替代- > </ noscript >
元

< meta-  charset = “ utf-8 ” > <！ -设置文档的字符编码- > 
< meta  http-equiv = “ x-ua-compatible ”  content = “ ie = edge ” >
< meta  name = “ viewport ”  content = “ width = device-width，initial-scale = 1，shrink-to-fit = no ” >
 <！ -上述3个元标记*必须先在头部; 任何其他头部内容必须*后*这些标签- >

<！ -允许控制资源的加载位置- > 
< meta  http-equiv = “ Content-Security-Policy ”  content = “ default- src'self ' ” >
 <！ -在文档中尽早放置可能- > 
<！ -仅适用于此标签下方的内容- >

<！ - Web应用程序的名称（仅当该网站用作应用程序时才应使用）- > 
< meta  name = “ application-name ”  content = “ Application Name ” >

<！ -页面的简短描述（限制为150个字符）- > 
<！ -在*某些*情况下，此描述用作搜索结果中显示的片段的一部分。- > 
< meta  name = “ description ”  content = “页面的描述” >

<！ -控制搜索引擎抓取和索引的行为- > 
< meta  name = “ robots ”  content = “ index，follow，noodp ” > <！ -所有搜索引擎- > 
< meta  name = “ googlebot ”  content = “ index，follow ” > <！ - Google Specific - >

<！ -告诉Google不要显示附加链接搜索框- > 
< meta  name = “ google ”  content = “ nositelinkssearchbox ” >

<！ -告诉谷歌不为这个网页提供翻译- > 
<元 名称 = “谷歌” 的内容 = “ notranslate ” >

<！ -验证Google Search Console的所有权- > 
< meta  name = “ google-site-verification ”  content = “ verification_token ” >

<！ -验证Yandex网站管理员的所有权- > 
< meta  name = “ yandex-verification ”  content = “ verification_token ” >

<！ -验证Bing网站管理员中心的所有权- > 
< meta  name = “ msvalidate.01 ”  content = “ verification_token ” >

<！ -验证Alexa控制台的所有权- > 
< meta  name = “ alexaVerifyID ”  content = “ verification_token ” >

<！ -验证Pinterest控制台的所有权- > 
< meta  name = “ p：domain_verify ”  content = “来自pinterest的代码” >

<！ -验证Norton Safe Web的所有权- > 
< meta  name = “ norton-safeweb-site-verification ”  content = “ norton code ” >

<！ -用于命名用于构建网站的软件（即 -  WordPress，Dreamweaver）- > 
< meta  name = “ generator ”  content = “ program ” >

<！ -您网站主题的简短描述- > 
< meta  name = “ subject ”  content = “您的网站的主题” >

<！ -根据网站内容提供一般年龄评估- > 
< meta  name = “ rating ”  content = “ General ” >

<！ -允许控制引荐来源网址信息的传递方式- > 
< meta  name = “ referrer ”  content = “ no-referrer ” >

<！ -禁用自动检测和格式化可能的电话号码- > 
< meta  name = “ format-detection ”  content = “ telephone = no ” >

<！ -通过设置为“关闭”完全退出DNS 预取- > 
< meta  http-equiv = “ x-dns-prefetch-control ”  content = “ off ” >

<！ -在客户端Web浏览器上存储cookie以进行客户端标识- > 
< meta  http-equiv = “ set-cookie ”  content = “ name = value; expires = date; path = url ” >

<！ -指定要在特定框架中显示的页面- > 
< meta  http-equiv = “ Window-Target ”  content = “ _value ” >

<！ -地理标签- > 
< meta  name = “ ICBM ”  content = “纬度，经度” >
< meta  name = “ geo.position ”  content = “纬度;经度” >
< meta  name = “ geo.region ”  content = “ country [-state] ” > <！ -国家代码（ISO 3166-1）：强制性，状态码（ISO 3166-2）：可选; 例如。内容= “US”/内容= “US-NY” - > 
< 元 名称 = “ geo.placename ” 内容 = “市/县” > <！ -例如。content =“纽约市” - >
Google了解的元标记
WHATWG维基：MetaExtensions
维基百科ICBM
地理标记在维基百科上
链接

<！ -指向CSS样式表- > 
< link  rel = “ stylesheet ”  href = “ https://example.com/styles.css ” >

<！ -帮助防止重复的内容问题- > 
< link  rel = “ canonical ”  href = “ https://example.com/2010/06/9-things-to-do-before-entering-social-media。 html “ >

<！ -用于包含在图标链接之前，但已被弃用，不再使用- > 
< link  rel = “ shortlink ”  href = “ https://example.com/?p=42 ” >

<！ -与当前文档的AMP HTML版本的链接 - > 
< link rel = “ amphtml ”  href = “ https://example.com/path/to/amp-version.html ” >

<！ -指向JSON文件的链接，指定Web应用程序的“安装”凭据- > 
< link  rel = “ manifest ”  href = “ manifest.json ” >

<！ -链接到文档的作者- > 
< link  rel = “ author ”  href = “ humans.txt ” >

<！ -是指适用于链接上下文的版权声明- > 
< link  rel = “ copyright ”  href = “ copyright.html ” >

<！ -提供文档中可能使用其他语言的位置的引用- > 
< link  rel = “ alternate ”  href = “ https://es.example.com/ ”  hreflang = “ es ” >

<！ -提供有关作者或其他人的信息- > 
< link  rel = “ me ”  href = “ https://google.com/profiles/thenextweb ”  type = “ text / html ” >
< link  rel = “ me ”  href = “ mailto：name@example.com ” >
< link  rel = “ me ”  href = “ sms：+15035550125 ” >

<！ -链接到描述历史感兴趣的记录，文档或其他材料的集合的文档。- > 
< link  rel = “ archives ”  href = “ https://example.com/archives/ ” >

<！ -分层结构中顶级资源的链接 - > 
< link rel = “ index ”  href = “ https://example.com/ ” >

<！ -提供自我参考 - 当文档有多个可能的引用时有用- > 
< link  rel = “ self ”  type = “ application / atom + xml ”  href = “ https://example.com/atomFeed.php ？page = 3 “ >

<！ -分别是一系列文件中的第一个，下一个，上一个和最后一个文档- > 
< link  rel = “ first ”  href = “ https://example.com/atomFeed.php ” >
< link  rel = “ next ”  href = “ https://example.com/atomFeed.php?page=4 ” >
< link  rel = “ prev ”  href = “ https://example.com/atomFeed.php?page=2 ” >
< link  rel = “ last ”  href = “ https://example.com/atomFeed.php?page=147 ” >

<！ -使用第三方服务来维护博客- > 
< link  rel = “ EditURI ”  href = “ https://example.com/xmlrpc.php?rsd ”  type = “ application / rsd + xml “  title = ” RSD “ >

<！ -当另一个WordPress博客链接到您的WordPress博客或发布时，形成自动注释- > 
< link  rel = “ pingback ”  href = “ https://example.com/xmlrpc.php ” >

<！ -在您的网站上链接到URL时通知网址- > 
< link  rel = “ webmention ”  href = “ https://example.com/webmention ” >

<！ -将外部HTML文件加载到当前的HTML文件中- > 
< link  rel = “ import ”  href = “/ path/to/component.html ” >

<！ -打开搜索- > 
< link  rel = “ search ”  href = “  /open- search.xml ” type = “ application / opensearchdescription + xml ”  title = “ Search Title ” >

<！ - Feeds >> 
< link  rel = “ alternate ”  href = “ https://feeds.feedburner.com/example ”  type = “ application / rss + xml ”  title = “ RSS ” >
< link  rel = “ alternate ”  href = “ https://example.com/feed.atom ”  type = “ application / atom + xml ”  title = “ Atom 0.3 ” >

<！ -预取，预加载，预先浏览- > 
< link  rel = “ dns-prefetch ”  href = “ //example.com/ ” >
< link  rel = “ preconnect ”  href = “ https://www.example.com/ ” >
< link  rel = “ prefetch ”  href = “ https://www.example.com/ ” >
< link  rel = “ prerender ”  href = “ https://example.com/ ” >
< link  rel = “ preload ”  href = “ image.png ”  as = “ image ” >
 <！ -更多信息：https://css-tricks.com/prefetching-preloading-prebrowsing/ - >
Favicons

<！ -对于IE 10及以下- > 
<！ -将favicon.ico放在根目录中 - 无需标签- >

<！ -对于IE 11，Chrome，Firefox，Safari，Opera - > 
< link  rel = “ icon ”  type = “ image / png ”  sizes = “ 16x16 ”  href = “/ path/to/favicon-16x16.png “ >
< link  rel = “ icon ”  type = “ image / png ”  sizes = “ 32x32 ”  href = “/ path/to/favicon-32x32.png ” >
< link  rel = “ icon ”  type = “ image / png ”  sizes = “ 96x96 ”  href = “/ path/to/favicon-96x96.png ” >
所有关于Favicons（和触摸图标）
Favicon作弊表
社会

Facebook打开图

< meta  property = “ fb：app_id ”  content = “ 123456789 ” >
< meta  property = “ og：url ”  content = “ https://example.com/page.html ” >
< meta  property = “ og：type ”  content = “ website ” >
< meta  property = “ og：title ”  content = “ Content Title ” >
< meta  property = “ og：image ”  content = “ https://example.com/image.jpg ” >
< meta  property = “ og：description ”  content = “ Description Here ” >
< meta  property = “ og：site_name ”  content = “ Site Name ” >
< meta  property = “ og：locale ”  content = “ en_US ” >
< meta  property = “ article：author ”  content = “ ” >
Facebook打开图形标记
Open Graph协议
Facebook即时文章

< meta  charset = “ utf-8 ” >
< meta  property = “ op：markup_version ”  content = “ v1.0 ” >

<！ -您的文章的网页版本的URL - > 
< link  rel = “ canonical ”  href = “ http://example.com/article.html ” >

<！ -用于这篇文章的风格- > 
< meta  property = “ fb：article_style ”  content = “ myarticlestyle ” >
Facebook即时文章：创建文章
即时文章：格式参考
Twitter卡

< meta  name = “ twitter：card ”  content = “ summary ” >
< meta  name = “ twitter：site ”  content = “ @site_account ” >
< meta  name = “ twitter：creator ”  content = “ @individual_account ” >
< meta  name = “ twitter：url ”  content = “ https://example.com/page.html ” >
< meta  name = “ twitter：title ”  content = “内容标题” >
< meta  name = “ twitter：description ”  content = “内容描述少于200个字符” >
< meta  name = “ twitter：image ”  content = “ https://example.com/image.jpg ” >
Twitter卡：入门指南
Twitter卡验证器
Google+ / Schema.org

< link  href = “ https://plus.google.com/+YourPage ”  rel = “ publisher ” >
< meta  itemprop = “ name ”  content = “ Content Title ” >
< meta  itemprop = “ description ”  content = “内容描述少于200个字符” >
< meta  itemprop = “ image ”  content = “ https://example.com/image.jpg ” >
Pinterest

根据他们的帮助中心，Pinterest允许您阻止人们从您的网站存储东西。这description是可选的。

< meta  name = “ pinterest ”  content = “ nopin ”  description = “对不起，你不能从我的网站保存！” >
签名

< link  rel = “ alternate ”  type = “ application / json + oembed ”
   href = “ http://example.com/services/oembed?url=http%3A%2F%2Fexample.com%2Ffoo%2F＆amp ; format = json “
   title = ” oEmbed Profile：JSON “ >
< link  rel = “ alternate ”  type = “ text / xml + oembed ”
   href = “ http://example.com/services/oembed?url=http%3A%2F%2Fexample.com%2Ffoo%2F＆amp ; format = xml “
   title = ” oEmbed Profile：XML “ >
oEmbed格式
浏览器/平台

苹果iOS

<！ -智能应用横幅- > 
< meta  name = “ apple-itunes-app ”  content = “ app-id = APP_ID，affiliate-data = AFFILIATE_ID，app-argument = SOME_TEXT ” >

<！ -禁用自动检测和格式化可能的电话号码- > 
< meta  name = “ format-detection ”  content = “ telephone = no ” >

<！ -添加到主屏幕- > 
< meta  name = “ apple-mobile-web-app-capable ”  content = “ yes ” >
< meta  name = “ apple-mobile-web-app-status-bar-style ”  content = “ black ” >
< meta  name = “ apple-mobile-web-app-title ”  content = “ App Title ” >

<！ -触摸图标- > 
<！ -在大多数情况下，头部的一个180×180px触摸图标就足够了- > 
< link  rel = “ apple-touch-icon ”  href = “ / path / to / apple-touch-icon.png “ >
 <！ -注意：iOS 7上的Safari不会对图标添加效果。- > 
<！ -旧版本的Safari不会添加以-precomposed.png后缀命名的图标文件的效果。 - >

<！ -启动图像（已弃用）- > 
< link  rel = “ apple-touch-startup-image ”  href = “/ path/to/startup.png ” >

<！ - iOS应用深层链接- > 
< meta  name = “ apple-itunes-app ”  content = “ app-id = APP-ID，app-argument = http / url-sample.com ” >
< link  rel = “ alternate ”  href = “ ios-app://APP-ID/http/url-sample.com ” >
苹果元标签
苹果Safari

<！ -固定网站- > 
< link  rel = “ mask-icon ”  href = “/ path/to/icon.svg ”  color = “ red ” >
Google Android

< meta  name = “ theme-color ”  content = “＃E64545 ” >

<！ -添加到主屏幕- > 
< meta  name = “ mobile-web-app-capable ”  content = “ yes ” >
 <！ -更多信息：https://developer.chrome.com/multidevice/android / installtohomescreen - >

<！ - Android应用深度链接- > 
< meta  name = “ google-play-app ”  content = “ app-id = package-name ” >
< link  rel = “ alternate ”  href = “ android-app://package-name/http/url-sample.com ” >
谷歌浏览器

< link  rel = “ chrome-webstore-item ”  href = “ https://chrome.google.com/webstore/detail/APP_ID ” >

<！ -禁用翻译提示- > 
< meta  name = “ google ”  value = “ notranslate ” >
Google Chrome Mobile（仅限Android）

自从Chrome 31以来，您可以将网络应用设置为“应用模式”，如Safari。

<！ -链接到清单并定义清单元数据。- > 
<！ - manifest.json的示例可以在下面的链接中找到。- > 
< link  rel = “ manifest ”  href = “ manifest.json ” >

<！ -将您的网页定义为网络应用程序- > 
< meta  name = “ mobile-web-app-capable ”  content = “ yes ” >

<！ -主屏幕图标   - > 
< link  rel = “ icon ”  sizes = “ 192x192 ”  href = “ highres-icon.png ” >
Google开发人员
Microsoft Internet Explorer

< meta  http-equiv = “ x-ua-compatible ”  content = “ ie = edge ” >
< meta  name = “ skype_toolbar ”  content = “ skype_toolbar_parser_compatible ” >

<！ - IE10：禁用链接突出于龙头（https://blogs.windows.com/buildingapps/2012/11/15/adapting-your-webkit-optimized-site-for-internet-explorer-10/）- - > 
< meta  name = “ msapplication-tap-highlight ”  content = “否” >

<！ -固定网站（https://msdn.microsoft.com/en-us/library/dn255024(v=vs.85).aspx）- > 
< meta  name = “ application-name ”  content = “示例标题“ >
< meta  name = “ msapplication-tooltip ”  content = “对这个网站的描述。” >
< meta  name = “ msapplication-starturl ”  content = “ http://example.com/index.html?pinned=true ” >
< meta  name = “ msapplication-navbutton-color ”  content = “＃FF3300 ” >
< meta  name = “ msapplication-window ”  content = “ width = 800; height = 600 ” >
< meta  name = “ msapplication-task ”  content = “ name = Task 1; action-uri = http：//host/Page1.html; icon-uri = http：//host/icon1.ico ” >
< meta  name = “ msapplication-task ”  content = “ name = Task 2; action-uri = http：//microsoft.com/Page2.html; icon-uri = http：//host/icon2.ico ” >
< meta  name = “ msapplication-badge ”  value = “ frequency = NUM​​BER_IN_MINUTES; polling-uri = http：//example.com/path/to/file.xml ” >
< meta  name = “ msapplication-TileColor ”  content = “＃FF3300 ” >
< meta  name = “ msapplication-TileImage ”  content = “/ path/to/tileimage.jpg ” >

< meta  name = “ msapplication-config ”  content = “ http://example.com/browserconfig.xml ” >
< meta  name = “ msapplication-notification ”  content = “ frequency = 60; polling-uri = http：//example.com/livetile; polling-uri2 = http：//example.com/livetile2 ” >
< meta  name = “ msapplication-task-separator ”  content = “ 1 ” >
应用链接

<！ - iOS - > 
< meta  property = “ al：ios：url ”  content = “ applinks：// docs ” >
< meta  property = “ al：ios：app_store_id ”  content = “ 12345 ” >
< meta  property = “ al：ios：app_name ”  content = “ App Links ” >
 <！ - Android - > 
< meta  property = “ al：android：url ”  content = “ applinks：// docs ” >
< meta  property = “ al：android：app_name ”  content = “ App Links ” >
< meta  property = “ al：android：package ”  content = “ org.applinks ” >
 <！ - Web Fallback - > 
< meta  property = “ al：web：url ”  content = “ http://applinks.org/文档“ >
 <！ -更多信息：http://applinks.org/documentation/ - >
应用链接文档
浏览器（中文）

360浏览器

<！ -依次选择渲染引擎- > 
< meta  name = “ renderer ”  content = “ webkit | ie-comp | ie-stand ” >
QQ手机浏览器

<！ -将屏幕锁定到指定的方向- > 
< meta  name = “ x5-orientation ”  content = “ landscape / portrait ” >
 <！ -以全屏显示此页面- > 
< meta  name = “ x5-全屏“  content = ” true “ >
 <！ -页面将显示在”应用程序模式“（全屏等）中- > 
< meta  name = ”x5-page-mode “  content = ” app “ >
UC Mobile Browser

<！ -将屏幕锁定到指定的方向- > 
< meta  name = “ screen-orientation ”  content = “ landscape / portrait ” >
 <！ -以全屏显示此页面- > 
< meta  name = “ full-屏幕“  content = ” yes “ >
 <！ - UC浏览器将显示图像，即使在”文本模式“ - > 
< meta  name = ”imagemode “  content = ” force “ >
 <！ -页面将显示在”应用程序模式“（全屏，禁止手势等）- > 
< meta  name = ” browsermode “  content = ” application “ >
 <！ -禁用UC浏览器在此页面的“夜间模式” - > 
< meta  name = “ nightmode ”  content = “ disable ” >
<！ -简化页面以减少数据传输- > 
< meta  name = “ layoutmode ”  content = “ fitscreen ” > <！ -禁用UC浏览器的功能“在此页面有多个单词时缩放字体” - > 
< meta  name = “ wap-font-scale ”  content = “ no ” >meta name = “ layoutmode ” content = “ fitscreen ” > <！ -禁用UC浏览器的功能“在此页面有多个单词时缩放字体” - > < meta name = “ wap-font-scale ”内容 = “否” >meta name = “ layoutmode ” content = “ fitscreen ” >
 <！ -禁用UC浏览器的功能“在此页面有多个单词时缩放字体” - > < meta name = “ wap-font-scale ”内容 = “否” >在这个页面中有很多单词时缩放字体“ - > < meta name = ” wap-font-scale “ content = ” no “ >在这个页面中有很多单词时缩放字体“ - > < meta name = ” wap-font-scale “ content = ” no “ >
UC浏览器文档
笔记

性能

移动href时，GZIP启用，因为属性的元素年初提高了压缩href属性被用于a，base和link标签。

例：

< link  href = “ https://fonts.googleapis.com/css?family=Open+Sans:400,700 ”  rel = “ stylesheet ” >
其他资源

HTML5 Boilerplate文档：HTML
HTML5 Boilerplate文档：扩展和自定义
相关项目

Atom HTML Head Snippets - 用于HEAD代码片段的Atom包
Sublime Text HTML Head Snippets - Sublime Text package for HEADsnippets
head-it - 用于HEAD代码片段的CLI界面
vue-head - 操作Vue.js HEAD标签的元信息
其他格式

PDF
翻译

巴西葡萄牙语
简体中文）
意大利语
日本
俄语/Русский
土耳其语/Türkçe
贡献

打开问题或提出请求来建议更改或添加。

指南

该HEAD库由两个分支组成：

1。 master

该分支包含README.md自动反映在<head> Cheat Sheet网站上的文件。所有对作弊表内容的更改都应针对此文件。

请按照以下步骤进行拉取：

一次只修改一个标签或一组相关标签
在属性上使用双引号
在自动关闭元素中不要包含尾部斜杠 - HTML5规范说它们是可选的
考虑包括支持您更改的文档的链接
2。 gh-pages

该分行负责<head> Cheat Sheet网站。我们使用JekyllREADME.md通过GitHub Pages部署Markdown文件。所有网站相关的修改必须在这里。

您可能需要通过Jekyll文档，并了解Jekyll在此分支上工作之前的工作。
