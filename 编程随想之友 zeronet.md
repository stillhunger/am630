本站的全部文字在 cc-by-sa-3.0 之条款下提供。发言前请先查阅 How To Ask Questions The Smart Way(高效率提问/提问的智慧)

  
  
  
## 一、编程随想之友
欢迎你，编程随想之友！

### 愿景
* 在zeronet我们已经有了言论自由和建立网站的能力，那么我们下一步要干什么呢？在ISP封锁zeronet网络之后又要做什么？
* 建立组织。1.zeronet，目前网站的前端还不完善，需要网页编程才能制造出实用的网站。2.在明网建站，需要一些运维经验

### 组织结构（待修订）
* 我们所有的行为几乎都是透明公开的，所以加入的不是一个封闭的组织，而是一个几乎开放的组织。
* 就像匿名者那样，匿名者只是一个理念。同样，编程随想之友也是一个理念。
* 首先你要把编程随想的大部分贴子都看一遍，然后实践一下匿名技术。接着你可能需要阅读一下他博客里的评论，可以参考我整理的评论。
* 如果你不想匿名，那么就参与讨论吧，只要你能说服别人，别人就会听你的。比如你要做某一件事情，那么说出你的理由并尝试说服他人。
* 我们是学习型组织，我们先提高自己，然后帮助“弱小”，再来发展组织。

### 程序员

关于学东西这件事情，如果你是程序员，那么应该不用别人教你了。英文网站的信息质量一般都高于中文网站，随想的github里面已经有相关的网站推荐，开源项目推荐，书单推荐，能三年内看完都是大神级别的，我都是跳着看，找感兴趣的看。

### about 编程随想
请参阅他的博客。

### about am630

* 我刚刚通过自学脱离小白不久，脱离的契机是整理编程随想blog的评论。 我刚刚摆脱对英语的恐惧不久，摆脱的契机是使用 Linux 这款开源系统。 我刚刚………… 我不是程序员，编程经验还不丰富，还只能勉强改点代码，可以看我管理的wiki 我热爱哲学，我是偏文科的
* 我编程技术还只是本科一年级的新生水准。还不能开发重型软件，但是小型的网站和小脚本都是能做的。现在，gfw talk（主论坛里来了一位逼格挺高的程序员，他要开发zeronet原生的站点。）
* 我善于总结资源，比如我整理的PT博客评论，这些评论我是准备用来作为新教程集的基础的，我的确更擅长文而不是技术。
* 我接下来就是学习修改现有的zeronet网站来熟悉前端开发，接着写一些总结。然后是学js和相关的数据库json和那个coffee。会用js我就开始看html5+css3。



  
  
  

## 二、zeronet

* zeronet的软件，在离线状态下，相当于一个带数据库的服务器
* 随想对于0net还在观望。0net基于p2p bt 网络和比特币加密算法，UI使用网页，数据库和js都是无服务器端的状态。这几乎决定了0net的发展极限，我想要听听各位大神们的看法。各位可以帮我找地方问问吗？
* 0net里面的网站都是完全开源的，完全可克隆。那么不可克隆的网站就会有优势，具体实现可能是让服务端保持在线，让客户端可连接服务端，用zeronet网络来备份网站内容，网站内容可加密，这需要一个服务器和一个网络安全知识丰富且有能力管理网站的大神。
* zeronet的数据库好像有两种，一种是json文本（用python脚本来做文本处理可以解决大部分问题），一种是.db似乎要用数据库工具来读写（wiki里面有相关信息，愿意的话，先帮忙翻译和改进）
* @sysl zeronet一开始只有会程序的人来能玩得顺溜，接着一段时间后，就会出现比较完善的博客网站供普通用户克隆，还会出现一个好用的论坛。我不关心这些，我关心的是一个wiki百科全书，即使是小型的也无所谓，重要的是权限控制（随想最近不是发了一篇关于管理的博文吗？里面提到了权限的重要性。）zeronet是无法直接用来做大型网站的，一万用户的论坛都能够呛的，但是用来做p2p文件共享却很好，一开始是那些用眼光的人共享一些热门资源（现在还没有，“大批量的色情图片这种东西我还没看见”，视频太大，硬盘要够大，谁有这么高度奉献的精神呢？多半是共享几天就撒源），然后如果没有特别好的方法来克服这种断源危机，那么zeronet就不适合做文件共享（至少不适合做大文件共享）。BTsync更适合做文件共享，用zeronet来发布链接就很不错，还可以在一个论坛里讨论。

###  [零网教学 zh-wiki](http://127.0.0.1:43110/1NCezLP8aXjABVreBB1CKGPub2tKTtyhWU/)

* zeronet的教学整理，以及汉化促进。完善wiki里的dev开发部分，包括翻译和总结。
* wiki站点是人人可编辑的，所以尝试去完善他，特别是导航的部分，如果你不会编辑，那么你发个贴子，把地址贴到这里来，我暂时可以帮你更新。最好是自己学会。 
*  管理员：am630

### zeronet网站 愿望清单

内容为王，小东西在zeronet非常有生长力

* 做一个游戏！做游戏可以很快提高能力的。比如推箱子，贪吃蛇，棋牌。用html5+css3可以胜任flash。真心不错。
* 将维基百科搬到zeronet
* 有机会找人把比较权威的编程书集中在一起，share到0net，方便下载，但是需要一个储存文件的节点，最好不要使用tor，最好有台湾或香港的程序员帮忙。
* 还有，草榴知道吧？他们的论坛很简陋，我觉得开发一个适用的论坛会吸引更多的流量
* 我想要的网站是一个完善的小型wiki站点，可以先要一个分类系统完善的blog，用来替代zeroblog给小白用户使用。
* 一个像blogger(WP)这样的blog管理网站就很适合给新手小白们用，这样就不需要建那么多新站点了。
* 还有IRC升级版，传统的IRC似乎到了被淘汰的时候了，升级一下，加点加密机制是最好的
* wiki，这东西弄出来，其他网站都可以不要了（至少我可以不要）。 
* 一个办法（从xiaolan博客上看到的），利用zeronet的文件储存，不使用zeronet现有的任何api，外建网站（具体如何实现，我不清楚。）
* 如果你有能力做网站，那就简单了。我建议你先写一个用来调试功能的站点，方便开发。
* 做公共网盘，文件多了还要分类，可以分类储存也可以仅仅是分类显示。@fucksociety 你编程技术强不强，不强的话可能需要帮助，强的话你应该可以自己搞定，我会帮你挂友链接过来。
* 文件共享如果是小文件共享就可以开放限制，用来做公共网盘。如果是大文件就麻烦，大文件最好是自己搭建网站自己共享。
* 自定义首页
* 编程随想之友留言板
* 听音乐 -/-
### zeronet外部工具
* 数据搜索查询工具，（查询json数据库），直观显示
* 批量删除留言。




## 三、重构计算机教育体系

随想说要写linux相关的贴子，我想【重构计算机教育体系】，采取分级（“技术水平分级”）教学的手段。

教学体系的基本结构：

* 方法
 * 对于最普通的学生，使用手把手教学模式
 * 有计算机经验的学生，使用视频+教材+讨论+wiki的MOOC模式
 * 对于非常有经验的学生，发掘他们的geek折腾精神
* 做法
 * 手把手教学要开发一个手把手教学软件（玩过流行网游的同学应该知道，手把手教学是必不可少的一部分），软件之后还要有具体的资源，这依据课程大纲来确认
 * 对于有经验的学生，扩充他们的视野，给他们搭建一个平台（可以暂时在zeronet里做，做好了权限管理就可以做出来了）
 * 对于geek学生，他们有能力自学，我们只需要引导他们，甚至让他们自己写教材
* 除此之外，还需要一个问答型网站用来给低年级学生提问，高年级学生回答低年级学生的问题。

我们是开发者，也是计算机方面的准专家（or专家），由我们来写教程大纲再适合不过了。当我发现我连快捷键都用不顺溜的时候，我想到了这个教学计划，这需要挺多人参与进来，在0net有了基本发展之后，我会在github公布这个项目，这个项目不能直接在墙内存在，因为会被red化。感谢收听本台【谈革命IRC文字电台】我是【自任编辑】我们下期再会，观众朋友们晚安。

按住Shift可以输入大写字母。打字时，左手按住左Ctrl控制键，右手按方向键。同上一条换成左shift键。ctrl+backspace是删除输入法的全部候选字母，page up/down是输入候选换页。事实证明，am630的计算机基础有待加强。

  
  
## 其他

###  我想要的东西

* 一个谷歌搜索框（可以选语言，最好可以选搜索引擎，最好加上搜索代理）
* 匿名建站，建站需要花时间，因为主要资料都是英文的，需要考虑好再学。zeronet的教学先在【零网中文教学】写起来。然后zeronet的翻译计划要咨询一下其他【编程随想之友】。可以用免费主机架设网站（需要时间学习网络安全，如果xiaolan直接写帖子分享经验就省力气了，但是基本不太可能），也可以直接在github里，需要写一个github简易教学（推荐这种方法）。
* zeronet与github同步
* openshift可以免费建（暂时没时间去折腾），域名可以不要，站点用来折腾，批量下载整个网站什么的，用tor下网站太慢，用服务器下载就好一些。

### 问题

* 你能帮助我吗？你需要编程能力，思想能力，批判能力……各种能力，我们可不是玩过家家，但也请不要太拘谨，我也不是一个完美无瑕的大神，我正在从猿猴进化。
