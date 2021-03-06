# Bookmarklet
收集一些有用的Bookmarklet。欢迎大家提供共享。

 下面的内容来自维基百科。
 
小书签（bookmarklet），又叫书签小程序，是一种小型的程序（Applet），以网址（URL）的形式被存为浏览器中的书签，也可以是网页上的一个链接。小书签的英文名，Bookmarklet是由Bookmark和Applet组合而来。无论小书签如何以什么形式储存，它们都是用来对浏览器或是网页添加一些特定功能的。点击时，小书签会执行这些操作，包括执行搜索，导出数据等等。小书签一般是JavaScript应用程序。

Bookmarklet一般来说适用于所有浏览器，但是也有个别只对于某些浏览器有效。

*用途*

小书签的存储与使用和普通书签一致。如同它们的名字，小书签是一种十分易用的工具。例如：

 - 修改网页的外观（修改字体大小，背景颜色等）
 - 从网页中提取某些数据（链接，图片，文本等）
 - 将当前页面提交到博客平台（例如Posterous、Tumblr），社会化网站（例如Facebook、Twitter），缩短链接服务（bit.ly、su.pr等）或是书签服务（Delicious）
 - 快速调用搜索引擎搜索当前页面选中的文字
 - 将网页提交到链接检测服务，或是在线翻译服务
 - 设置某些页面本身不能修改的功能

*安装*

小书签一般是通过创建一个新书签并将代码粘贴入URL栏而实现的。现代浏览器中也可把链接形式的小书签直接拖拽到书签栏中，此后小书签就可以像打开普通书签一样正常运作了。

***注意***

有些服务被屏蔽，需要代理。Github不能直接显示代码，请查看该文件的RAW。


----------
**Readability**

[打开当前页面的阅读模式](javascript:%28%0A%28function%28%29%7Bwindow.baseUrl=%27//www.readability.com%27;window.readabilityToken=%27%27;var%20s=document.createElement%28%27script%27%29;s.setAttribute%28%27type%27,%27text/javascript%27%29;s.setAttribute%28%27charset%27,%27UTF-8%27%29;s.setAttribute%28%27src%27,baseUrl+%27/bookmarklet/read.js%27%29;document.documentElement.appendChild%28s%29;%7D%29%28%29%29)

[发送内容到Kindle](javascript:%28%0A%28function%28%29%7Bwindow.baseUrl=%27//www.readability.com%27;window.readabilityToken=%27%27;var%20s=document.createElement%28%27script%27%29;s.setAttribute%28%27type%27,%27text/javascript%27%29;s.setAttribute%28%27charset%27,%27UTF-8%27%29;s.setAttribute%28%27src%27,baseUrl+%27/bookmarklet/send-to-kindle.js%27%29;document.documentElement.appendChild%28s%29;%7D%29%28%29%29)

[稍后阅读](javascript:%28%0A%28function%28%29%7Bwindow.baseUrl=%27//www.readability.com%27;window.readabilityToken=%273bYZkM5QwJNJ5CFXvaBKsjZUmkUuhrQ3Ly5t562x%27;var%20s=document.createElement%28%27script%27%29;s.setAttribute%28%27type%27,%27text/javascript%27%29;s.setAttribute%28%27charset%27,%27UTF-8%27%29;s.setAttribute%28%27src%27,baseUrl+%27/bookmarklet/save.js%27%29;document.documentElement.appendChild%28s%29;%7D%29%28%29%29)

**Evernote**

[收藏到Evernote](javascript:%28function%28%29%7BEN_CLIP_HOST=%27http://www.evernote.com%27;try%7Bvar%20x=document.createElement%28%27SCRIPT%27%29;x.type=%27text/javascript%27;x.src=EN_CLIP_HOST+%27/public/bookmarkClipper.js?%27%2b%28new%20Date%28%29.getTime%28%29/100000%29;document.getElementsByTagName%28%27head%27%29%5B0%5D.appendChild%28x%29;%7Dcatch%28e%29%7Blocation.href=EN_CLIP_HOST%2b%27/clip.action?url=%27%2bencodeURIComponent%28location.href%29%2b%27&title=%27%2bencodeURIComponent%28document.title%29;%7D%7D%29%28%29;)

**Print Friendly**

[按需打印](javascript:%28function%28%29%7Bif%28window%5B%27priFri%27%5D%29%7Bwindow.print%28%29%7Delse%7Bvar%20pfurl=%27%27;pfstyle=%27nbk%27;pfBkVersion=%271%27;if%28window.location.href.match%28/https/%29%29%7Bpfurl=%27https://pf-cdn.printfriendly.com/ssl/main.js%27%7Delse%7Bpfurl=%27http://cdn.printfriendly.com/printfriendly.js%27%7D_pnicer_script=document.createElement%28%27SCRIPT%27%29;_pnicer_script.type=%27text/javascript%27;_pnicer_script.src=pfurl%20+%20%27?x=%27%20%28Math.random%28%29%29;document.getElementsByTagName%28%27head%27%29%5B0%5D.appendChild%28_pnicer_script%29;%7D%7D%29%28%29;)

**PrintWhatYouLike**

[按需打印](javascript:%28function%28%29%7Bif%28window%5B%27ppw%27%5D&&ppw%5B%27bookmarklet%27%5D%29%7Bppw.bookmarklet.toggle%28%29;%7Delse%7Bwindow._pwyl_home=%27//www.printwhatyoulike.com/%27;window._pwyl_pro_id=null;window._pwyl_bmkl=document.createElement%28%27script%27%29;window._pwyl_bmkl.setAttribute%28%27type%27,%27text/javascript%27%29;window._pwyl_bmkl.setAttribute%28%27src%27,window._pwyl_home+%27static/compressed/pwyl_bookmarklet_10.js%27%29;window._pwyl_bmkl.setAttribute%28%27pwyl%27,%27true%27%29;document.getElementsByTagName%28%27head%27%29%5B0%5D.appendChild%28window._pwyl_bmkl%29;%7D%7D%29%28%29;)

**YSlow**

[在线版YSlow](javascript:%28function%28y,p,o%29%7Bp=y.body.appendChild%28y.createElement%28%27iframe%27%29%29;p.id=%27YSLOW-bookmarklet%27;p.style.cssText=%27display:none%27;o=p.contentWindow.document;o.open%28%29.write%28%27%3Chead%3E%3Cbody%20onload=%22YUI_config=%7Bwin:window.parent,doc:window.parent.document%7D;var%20d=document;d.getElementsByTagName%28%5C%27head%5C%27%29%5B0%5D.appendChild%28d.createElement%28%5C%27script%5C%27%29%29.src=%5C%27http://yslow.org/yslow-bookmarklet.js%5C%27%22%3E%27%29;o.close%28%29%7D%28document%29%29)

**OneNote**

[收藏到OneNote](javascript:%28function%28%29%7Bif%28typeof%20OneNoteBookmarklet===%27undefined%27%29%7Bwindow.clipperId=%27ON-3978ff6e-ea1a-4d3e-b492-9f902780985b%27;var%20jsCode=document.createElement%28%27script%27%29;jsCode.setAttribute%28%27src%27,%27https://www.onenote.com/Clipper/Root?NoAuth=1%27%29;jsCode.setAttribute%28%27id%27,%27oneNoteCaptureRootScript%27%29;jsCode.setAttribute%28%27type%27,%27text/javascript%27%29;document.body.appendChild%28jsCode%29;%7D%7D%29%28%29)

**StumbleUpon**

[添加到StumbleUpon列表](javascript:void%28%28function%28d%29%7Bvar%20e=d.createElement%28%27script%27%29;e.setAttribute%28%27type%27,%27text/javascript%27%29;e.setAttribute%28%27charset%27,%27UTF-8%27%29;e.setAttribute%28%27src%27,%27https://www.stumbleupon.com/bookmarkletclient/bookmarklet.js?r=%27%2bMath.random%28%29%29;d.body.appendChild%28e%29%7D%29%28document%29%29;)

**Bootswatch**

[切换Bootstrap主题](javascript:%28function%28e,a,g,h,f,c,b,d%29%7Bif%28!%28f=e.jQuery%29%7C%7Cg%3Ef.fn.jquery%7C%7Ch%28f%29%29%7Bc=a.createElement%28%22script%22%29;c.type=%22text/javascript%22;c.src=%22http://ajax.googleapis.com/ajax/libs/jquery/%22+g+%22/jquery.min.js%22;c.onload=c.onreadystatechange=function%28%29%7Bif%28!b&&%28!%28d=this.readyState%29%7C%7Cd==%22loaded%22%7C%7Cd==%22complete%22%29%29%7Bh%28%28f=e.jQuery%29.noConflict%281%29,b=1%29;f%28c%29.remove%28%29%7D%7D;a.documentElement.childNodes%5B0%5D.appendChild%28c%29%7D%7D%29%28window,document,%221.3.2%22,function%28$,L%29%7Bif%28$%28%22.bootswatcher%22%29%5B0%5D%29%7B$%28%22.bootswatcher%22%29.remove%28%29%7Delse%7Bvar%20$e=$%28%27%3Cselect%20class=%22bootswatcher%22%3E%3Coption%3ECerulean%3C/option%3E%3Coption%3ECosmo%3C/option%3E%3Coption%3ECyborg%3C/option%3E%3Coption%3EDarkly%3C/option%3E%3Coption%3EFlatly%3C/option%3E%3Coption%3EJournal%3C/option%3E%3Coption%3ELumen%3C/option%3E%3Coption%3EPaper%3C/option%3E%3Coption%3EReadable%3C/option%3E%3Coption%3ESandstone%3C/option%3E%3Coption%3ESimplex%3C/option%3E%3Coption%3ESlate%3C/option%3E%3Coption%3ESpacelab%3C/option%3E%3Coption%3ESuperhero%3C/option%3E%3Coption%3EUnited%3C/option%3E%3Coption%3EYeti%3C/option%3E%3C/select%3E%27%29;var%20l=1+Math.floor%28Math.random%28%29*$e.children%28%29.length%29;$e.css%28%7B%22z-index%22:%2299999%22,position:%22fixed%22,top:%225px%22,right:%225px%22,opacity:%220.5%22,color:%22#000%22%7D%29.hover%28function%28%29%7B$%28this%29.css%28%22opacity%22,%221%22%29%7D,function%28%29%7B$%28this%29.css%28%22opacity%22,%220.5%22%29%7D%29.change%28function%28%29%7Bif%28!$%28%22link.bootswatcher%22%29%5B0%5D%29%7B$%28%22head%22%29.append%28%27%3Clink%20rel=%22stylesheet%22%20class=%22bootswatcher%22%3E%27%29%7D$%28%22link.bootswatcher%22%29.attr%28%22href%22,%22http://bootswatch.com/%22+$%28this%29.find%28%22:selected%22%29.text%28%29.toLowerCase%28%29+%22/bootstrap.min.css%22%29%7D%29.find%28%22option:nth-child%28%22+l+%22%29%22%29.attr%28%22selected%22,%22selected%22%29.end%28%29.trigger%28%22change%22%29;$%28%22body%22%29.append%28$e%29%7D;%7D%29;)

**markdownify**

[将当前网页显示为Markdown格式](javascript:%28function%28%29%7Bfunction%20callback%28%29%7B%28function%28$%29%7Bvar%20jQuery=$;$%28%27link%5Brel=stylesheet%5D%27%29.add%28%27style%27%29.remove%28%29;$%28%27%5Bstyle%5D%27%29.attr%28%27style%27,%20%27%27%29;$%28%27head%27%29.append%28%27%3Clink%20rel=%22stylesheet%22%20href=%22http://mrcoles.com/media/test/markdown-css/markdown.css%22%20type=%22text/css%22%20/%3E%27%29;$%28%27body%27%29.addClass%28%27markdown%27%29.css%28%7Bwidth:%20%27600px%27,%20margin:%20%272em%20auto%27,%20%27word-wrap%27:%20%27break-word%27%7D%29;$%28%27a%20img%27%29.css%28%7B%27max-height%27:%20%271em%27,%20%27max-width%27:%20%271em%27%7D%29%7D%29%28jQuery.noConflict%28true%29%29%7Dvar%20s=document.createElement%28%22script%22%29;s.src=%22https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js%22;if%28s.addEventListener%29%7Bs.addEventListener%28%22load%22,callback,false%29%7Delse%20if%28s.readyState%29%7Bs.onreadystatechange=callback%7Ddocument.body.appendChild%28s%29;%7D%29%28%29)

**List Email Links**

[列出当前页面所有邮件地址](javascript:eMlA=%27%27;for%28iB2M=0;iB2M%3Cdocument.links.length;iB2M++%29%7Bif%28document.links%5BiB2M%5D.protocol==%27mailto:%27%29%7BJu59=document.links%5BiB2M%5D.toString%28%29;eMlA+=Ju59.substring%287,Ju59.length%29+%27%5Cn%27%7D%7D;if%28eMlA!=%27%27%29%7Balert%28eMlA%29%7Delse%7Balert%28%27No%20mailto%20links%20on%20page!%27%29%7D)

**在线输入法**

[百度在线输入法](javascript:%28function%28%29%7Bvar%20a=document.createElement%28%27script%27%29;a.src=%27http://www.baidu.com/olime/bdime_open.js%27;document.body.appendChild%28a%29%7D%29%28%29;)
