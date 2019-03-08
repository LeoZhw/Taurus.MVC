# Taurus.MVC
Taurus.mvc is a simple mvc or webapi framework for asp.net or asp.net core（适合场景：对性能和并发有较高要求的电商、站点、WebAPI等系统，支持.Net Core）,created by Aster（路过秋天）<hr />

QQ交流群：6033006<br />

Website：http://taurus.cyqdata.com/ 
<hr />
Demo：https://github.com/cyq1162/Taurus.MVC.Demo <br />

<hr />
<h1>为什么要创造Taurus.MVC：</h1>
<p>记得被上一家公司忽悠去负责公司电商平台的时候，情况是这样的：</p>
<p>项目原版是外包给第三方的，使用：WebForm+NHibernate，代码不堪入目，Bug无限，经常点着点着就挂了。</p>
<p>一开始招了几个实习的大学生在那玩，搞不定了，终于忽悠的我了，哈哈。。。</p>
<p>当时进去的第一感觉是重做，不过呵呵，老板的心思你不猜不行。</p>
<p>然后第一阶段就是在旧项目改造维稳了，只要不是需要挂上百台服务器才能解决的问题，都能弱弱地处理的不要不要的，毕竟没有三两三，也不好上梁坑。</p>
<p>到了第二阶段，自然就是思考重做了：</p>
<p><strong>电商后台已有开源的：<a href="https://github.com/cyq1162/Aries" target="_blank">ASP.NET Aries</a> 框架（已支持.NET Core），刷刷刷的不用担心太多；</strong></p>
<h2><span style="color: #ff0000;"><strong>电商前台选什么框架呢？</strong></span></h2>
<p>1：WebForm 太保守；</p>
<p>2：.NET Core 1.1 太激进 (现在Taurus.MVC 已支持.NET Core)；</p>
<p>3：QBlog（秋色园） 门槛高；</p>
<p>4：重新写一套，事务繁忙，没空静下心思考，而且时间有限，已向BOSS提交了计划。</p>
<p><strong>最后只有无奈地选择：ASP.NET MVC 了。</strong></p>
<p>仔细想想.NET环境，市面上流行的开发框架，都是微软自家的（说好的百花齐放呢？）</p>
<p>我也知道，有些上点年纪的，也造框架，不过都是造给自己或自己公司用的（和造给用户用的思考的角度和涉及的广度是不一样的）。</p>
<p>也有一些免费造给人民群众的，不过宣传三两下就没声音了；</p>
<p>园子里也从来不会主动帮助第三方的开源框架做推广，光靠博主自己的激情和情怀，能支持多久都是是个未知数，毕竟搞框架是没收入的。</p>
<p>笔风一转：</p>
<p>后来，老板倒下了.....(泪奔~~~)。</p>
<p>然后，就有时间静下心来好好用情怀造框架了！</p>
<p>终于，Taurus.MVC 就出来了，而且一出来就开源了！！！开源！！开！三遍。</p>
<h1>关于框架取名：Taurus</h1>
<p>十年前造CYQ.Data的时候，名字取的不好（怪我咯），导致推广阻力大。</p>
<p>于是现在造新的框架，都必须得好好想个名字，毕竟得取个像：齐得龙，齐东强，齐得龙东强 这样的才够响亮而彻底。</p>
<p>前一小阵子发布的：ASP.NET Aries 业务开发框架：取名：Aries（白羊座，温柔中带点骄情）。</p>
<p>于是思考，是该延续白羊系列叫：Aries.MVC 呢？</p>
<p>还是。。。打造黄金十二宫呢？</p>
<p>然后把十三星座，八大行星的英文单词查了个遍，发现都没怎么满意，跳跃式取名有阻碍，那就顺序取名吧。</p>
<p>Taurus（金牛座），其实最后决定的原因是这个单词的发音：脱了（很有看大片的感觉，而且充满想象力，爆力中带点色咪咪的感觉）。</p>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805023118559-795702157.jpg" alt="" /></p>
<h1>关于框架的适用场景：</h1>
<p>选择框架，对高手来说，是一门学问；对新手来说，只是一种选择。</p>
<p>在我年轻的时候，被迫只能选择微软造的框架，现在，我成了创造者：</p>
<p>CYQ.Data+Aries+Taurus，几乎能适应所有的业务场景。</p>
<p>已经可以不用ASP.NET WebForm、ASP.NET MVC了。</p>
<p>但，仍然依旧离不开ASP.NET平台。</p>
<p>如上所说：</p>
<p>1：ASP.NET Aries 适用业务系统和后台快速开发。</p>
<p>2：Taurus.MVC 适用于对性能要求较高的电商等前端系统和WebAPI。</p>
<h1>关于框架的优势：</h1>
<p>通常讲框架的优势，就是开始扯蛋吹B的时候，只要市场口号喊的响亮，产品只要不是弱的一B就不是什么问题。</p>
<p>框架有啥优势？常人都先问这个，你要吹的我心动，吹的我心开，才回你一声哦，然后默默把源码下载存硬盘里。</p>
<p>由于市面基本微软一家统一天下，所以比较都是找微软家的MVC了。</p>
<p>其实吧，和.NET MVC 比起来，只能说：一个天上，一个地下。</p>
<p>MVC4安装完：800M（没搞明白究竟是要装什么东西这么大）；</p>
<p>Taurus.MVC安装完：400K（Taurus.Core.dll+CYQ.Data）。</p>
<p>很明显：微软这些年一直做加法，没想做减法，一直做创新，没想做兼容，很多产品都大粗大叶，让人纠心。</p>
<p>扯远了，说说优势，让我想想，让我和静静一起想想...</p>
<p>先用几个被用滥的词：轻量级？高性能？高效率？</p>
<p><strong>不行，得与众不同，有点别人没做到的才叫优势：</strong></p>
<p><strong>噢，对，得用图表示，这样才能显的专业，对，这样这样，那样那样，好，整完了，上图：</strong></p>
<p><strong><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805014733122-66381202.jpg" alt="" /></strong></p>
<h1>Taurus.MVC 源码：</h1>
<p>1：源代码SVN：<a href="https://github.com/cyq1162/Taurus.MVC">https://github.com/cyq1162/Taurus.MVC</a></p>
<p>2：Demo演示站：<a href="http://taurus.cyqdata.com/">http://taurus.cyqdata.com</a></p>
<p>Demo截图是这样的（新版本现在多了个WebAPI Demo）：</p>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805023918043-2063699248.jpg" alt="" /></p>
<h1>Taurus.MVC 框架引入方式：</h1>
<p>1：在Nuget上搜：Taurus.MVC，引用即可（会引入：Taurus.Core和CYQ.Data）</p>
<p>然后出来一个Readme.txt，按提示配置一下URL拦截和指定Controller地方的dll即可。</p>
<p><strong>.NET Core 版本搜：Taurus.MVC.Core</strong></p>
<p>2：直接用源码项目（源码项目里会有Demo）。</p>
<p>.NET版本运行：Taurus.MVC.sln</p>
<p>.NET Core 版本运行：Taurus.MVC_Core_VS2017.sln</p>
<h1>Taurus.MVC 框架介绍：</h1>
<h2>1：源码下载后：解决方案图：</h2>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805005840497-1095313333.jpg" alt="" /></p>
<h2>2：解决方案说明：</h2>
<p>1：CYQ.Data：主要XHtmlAction当模板引擎，另外当数据层可以提供Model或提供自动绑定语法。</p>
<p>2：Taurus.Core：主要实现了路由重写、Controller调用、ViewEngine等核心方法。</p>
<p>3：Taurus.Controllers 方法入口，写代码的地方。</p>
<p>4：Taurus.View 只存放html和css和js</p>
<h2>3：补充说明：</h2>
<p>1：通常MVC的Controller，Modle，View文件都放在一个项目里，这里就分拆到两个项目了。</p>
<p>2：为了项目层级清晰，你可以建Model项目（放实体）和Logic项目（写业务逻辑代码）还有Utility（放工具类）。</p>
<p>3：框架提供的Demo，就马马虎虎全放Controllers项目里了。</p>
<p><strong>下面按MVC的套路来简单说说基础的原理及使用方式：</strong></p>
<h1>1：Taurus.MVC的路由：</h1>
<h2>1：隐匿路由：</h2>
<p>在.NET MVC里，路由是一块很重要，但麻烦的功能。</p>
<p>要简化MVC，第一步，就是要思考如何隐式地消灭路由。</p>
<p>最后内部默认定了3个路由：</p>
<p>0：{Action}/{Para}</p>
<p>1：{Controller}/{Action}/{Para}</p>
<p>2：{Module}/{Controller}/{Action}/{Para}</p>
<p>默认是1。</p>
<h2>2：扩展路由：</h2>
<p>当部署为子应用程序，或第一个为用户名时，会多出一个前缀目录。</p>
<p>这时可以能过AppSetting配置RouteMode值为2，轻松过度。</p>
<p>上下文会提供三个参数让你获取信息：ControllerType，Action，Para。</p>
<p><span style="color: #ff0000;"><strong>好了，路由讲完了，想自定义路由？在Para上做点创新就可以了~~~~</strong></span></p>
<h1>2：Taurus.Controllers</h1>
<h2>1：寻找Controller：</h2>
<p>规则已经定好了，剩下的事就是按规则找Controller了。</p>
<p>1：收集所有的Controller。</p>
<p>2：指定去哪收集：默认是去Taurus.Controllers找继承自基类：Taurus.Core.Controller。</p>
<p>3：自定义存放Controllers：AppSetting配置Taurus.Controllers的值，假设为：Taurus.View</p>
<p>4：找不到Controller时，都找DefaultController，如果这个都木有（Demo里是有的），就抛异常了。</p>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805025506872-16659224.jpg" alt="" /></p>
<h2>2：调用Controller的Action：</h2>
<p>1：方法名都是public void，可以有参数（重载多个参数，默认只收集第一个）。</p>
<p>2：有输入的，用Write方法。</p>
<p>3：找不到Action时，会找Default方法（这个基类里有，所以一定会有，有需要就重写它）。</p>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805025353559-490764850.jpg" alt="" /></p>
<h1>3：Taurus.View</h1>
<p>1：模板：html（严格的说应该是xhtml）</p>
<p>2：模板加载方式：和URL对应的寻址路径：就是Views/{Controller}/{Action}.html ，通过配置可以改变约定的路径。</p>
<p>3：母版页的引用方式：itemref="页面.节点名称"。（<strong>itemref是div的属性，没人用，就借它来引用节点替换</strong>。）</p>
<p>4：加载替换语法：</p>
<p>A：对于input标签，可以使用CYQ.Data.MDataRow.SetToAll批量赋值。</p>
<p>B：对于${name}，可以使用View.LoadData(数据,"前缀")，会自动格式化。</p>
<p>C：对于列表循环标签：可以使用CYQ.Data.MDataTable.Bind方法绑定。</p>
<p><img src="http://images2015.cnblogs.com/blog/17408/201608/17408-20160805025919762-770843444.jpg" alt="" /></p>
<h1>总结：</h1>
<p>1：本文并没详细讲解使用方法，对于使用方式，会在下一篇文章介绍：</p>
<p>嗯，一篇介绍就够了，因为实在没啥可讲的了，不需要写一本书。</p>
<p>2：Demo里提供增删改查列表分页功能，能力好点或有MVC基础的，扫下源码就会使用。</p>
<p>3：今天的重点是开源。。。开源。。。开源。。。重要的事情说123。</p>
<p>最后说一声：</p>
<p>此框架的开源，给了.NET的人民群众多了一种选择。</p>
