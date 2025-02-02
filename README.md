# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm344新生报道管理系统+jsp

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1gn8XeNE2J?p=140)


# 系统概述
1.1 研究背景

如今互联网高速发展，网络遍布全球，通过互联网发布的消息能快而方便的传播到世界每个角落，并且互联网上能传播的信息也很广，比如文字、图片、声音、视频等。从而，这种种好处使得互联网成了信息传播的主要途径，社会上各种各样的信息都想尽办法通过互联网进行传播，互联网对社会产生的影响越来越大。

随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，所以信息的交换和信息流通显得特别重要。因此，使用计算机来管理高校新生入学报到的相关信息成为必然。开发合适的新生报道管理系统，可以方便管理人员对高校新生入学报到信息的管理，提高信息管理工作效率及查询效率，有利于更好的为人们服务。

1.2研究目的

随着互联网技术的快速发展，网络时代的到来，网络信息也将会改变当今社会。各行各业在日常企业经营管理等方面也在慢慢的向规范化和网络化趋势汇合。新生报道管理系统的信息化程度体现在将互联网与信息技术应用于经营与管理，以现代化工具代替传统手工作业。无疑，使用网络信息化管理使信息管理更先进、更高效、更科学，信息交流更迅速。

对于之前高校新生入学报到信息的管理，大部分都是使用传统的人工方式去管理，这样导致了管理效率低下、出错频率高。而且，时间一长的话，积累下来的数据信息不容易保存，对于查询、更新还有维护会带来不少问题。对于数据交接也存在很大的隐患。如果采用电子化的存储方式就会带来很大的改善，而且给用户的查询带来了很大便利，因此设计一个新生报道管理系统刻不容缓，能够提高信息的管理水平。
## 1.3系统设计思想
一个成功的网站应明确建设网站的目的，确定网站的功能，确定网站规模、投入费用，进行必要的市场分析等。只有详细的策划，才能避免在网站建设中出现的很多问题，使网站建设能顺利进行。同时，一个大型的计算机网站系统，必须有一个正确的设计指导思想，通过合理选择数据结构、网络结构、操作系统以及开发环境，构成一个完善的网络体系结构，才能充分发挥计算机信息管理的优势。根据现实生活中网民的实际需求，本系统的设计按照下述原则进行。

1. 有效性：实际上这里的有效性包括两个方面的意思：有用性和可用性。有用性是指站点潜在的能满足用户需求的功能，而可用性是指能够通过站点的操作实现特定的目标。可以看出一个站点如果不能恰当运行或设计得非常槽糕就不是一个好站点。可用站点的效益应该非常高，并易于学习，在实现用户目标时令人满意而不出错。
1. 高可靠性：一个实用的网站同时必须是可靠的，本设计通过合理而先进的网络设计以及软、硬件的优化选型，可保证网站的可靠性与容错性。
1. 高安全性：在设计中，将充分利用网络软、硬件提供的各种安全措施，既可以保证用户共享资源，充分考虑系统及数据资源的容灾、备份、恢复的要求。为系统提供强大的数据库备份工具。可以保证关键数据的安全性。操作权限级，设置不同的角色确保每一步的操作权限，可以由管理员进行设置。
1. 先进性：采用目前国际上最先进的开发技术，使用JSP开发技术，MySQL作为网站后台数据库。采用这些技术降低了以后的系统运营成本，提高了系统的稳定性和易维护性。
1. 采用标准技术：本网站的所有设计遵循国际上现行的标准进行，以提高系统的开放性。
1. 外观和技术平衡：系统采用Web风格的界面设计，界面友好、美观，使用方便，易学易用。网站设计的关键问题是外观和技术的平衡。外现不好的网站令人厌烦，站点可以运行很好，但却不能带动用户积极性，相反，如果外观非常有表现力，但技术有限，用户则会感到非常失望。在外观与技术之间需要确定一个清晰而连续的关系，即外观与站点的意图相关，对不同类型的网站处理方法不同。



# 2相关技术
## 2.1 SSM框架
SSM（Spring+SpringMVC+MyBatis）框架集由Spring、MyBatis两个开源框架整合而成（SpringMVC是Spring中的部分内容），常作为数据源较简单的web项目的框架。

Spring就像是整个项目中装配bean的大工厂，在配置文件中可以指定使用特定的参数去调用实体类的构造方法来实例化对象。也可以称之为项目中的粘合剂。

Spring的核心思想是IoC（控制反转），即不再需要[程序员](https://baike.baidu.com/item/%E7%A8%8B%E5%BA%8F%E5%91%98/62748)去显式地`new`一个对象，而是让Spring框架帮你来完成这一切。

SpringMVC在项目中拦截用户请求，它的核心Servlet即DispatcherServlet承担中介或是前台这样的职责，将用户请求通过HandlerMapping去匹配Controller，Controller就是具体对应请求所执行的操作。SpringMVC相当于SSH框架中struts。

mybatis是对jdbc的封装，它让数据库底层操作变的透明。mybatis的操作都是围绕一个sqlSessionFactory实例展开的。mybatis通过配置文件关联到各实体类的Mapper文件，Mapper文件中配置了每个类对数据库所需进行的sql语句映射。在每次与数据库交互时，通过sqlSessionFactory拿到一个sqlSession，再执行sql命令。

页面发送请求给控制器，控制器调用业务层处理逻辑，逻辑层向持久层发送请求，持久层与数据库交互，后将结果返回给业务层，业务层将处理逻辑发送给控制器，控制器再调用视图展现数据。 
## 2.2 MySQL数据库
MySQL是一个[关系型数据库管理系统](https://baike.baidu.com/item/%E5%85%B3%E7%B3%BB%E5%9E%8B%E6%95%B0%E6%8D%AE%E5%BA%93%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F/696511)，由瑞典[MySQL AB](https://baike.baidu.com/item/MySQL AB/2620844) 公司开发，属于 [Oracle](https://baike.baidu.com/item/Oracle) 旗下产品。MySQL 是最流行的[关系型数据库管理系统](https://baike.baidu.com/item/%E5%85%B3%E7%B3%BB%E5%9E%8B%E6%95%B0%E6%8D%AE%E5%BA%93%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F/696511)之一，在 [WEB](https://baike.baidu.com/item/WEB/150564) 应用方面，MySQL是最好的 [RDBMS](https://baike.baidu.com/item/RDBMS/1048260) (Relational Database Management System，关系数据库管理系统) 应用软件之一。MySQL是一种关系型数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。MySQL所使用的 SQL 语言是用于访问[数据库](https://baike.baidu.com/item/%E6%95%B0%E6%8D%AE%E5%BA%93/103728)的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和[商业版](https://baike.baidu.com/item/%E5%95%86%E4%B8%9A%E7%89%88/1817444)，由于其体积小、速度快、总体拥有成本低，尤其是[开放源码](https://baike.baidu.com/item/%E5%BC%80%E6%94%BE%E6%BA%90%E7%A0%81/7176422)这一特点，一般中小型和大型网站的开发都选择 MySQL 作为[网站数据库](https://baike.baidu.com/item/%E7%BD%91%E7%AB%99%E6%95%B0%E6%8D%AE%E5%BA%93/6399264)。

## 2.3 B/S结构
B/S架构是一种基于互联网系统的软件系统开发架构，是现如今在软件系统开发中采用非常大量的一种软件系统结构。现如今B/S架构已经被大量使用，打破了C/S结构的结构，给基于网络结构的软件系统提供了良好的支持。B/S架构伴随着计算机网络技术发展而逐步的发展和更新。伴随着互联网的进一步发展，就要求大多数的管理系统要求不仅仅可以在一台电脑上使用，同时可以在接入互联网的其他电脑也可以使用对系统进行操作和使用。在这样的背景下基于B/S架构的软件系统设计方法得到了越来越大量的使用，基础部分也在不断的更新。

B/S架构是利用操作系统中的浏览器来进行使用的，不是一种窗体软件系统，不需要在使用系统的电脑上进行安装。B/S架构的运行方式是在远程的服务器上把开发的软件系统部署在远程的服务器上，在部署好软件系统之后就可以实现在任何接入互联网的电脑上访问部署好的软件系统。B/S架构给使用管理系统的用户带来极大的便利。

在三层体系结构的B/S（Browser/Server，浏览器/服务器结构）系统中，用户可以通过浏览器向分布在网络上的众多服务器发出请求。B/S系统极大地简化了客户机的工作量，客户机上只需要安装、配置少量的客户端运行软件即可，服务器将担负大量的工作，对数据库的访问以及应用程序的执行都将由服务器来完成。

B/S架构的不断成熟，主要使用WWW浏览器技术，结合多种浏览器脚本语言，用通用浏览器需要实现原本复杂的专有软件来实现的强大功能，并节约了开发成本，是一种新的软件架构。B/S系统包括：表示逻辑层，控制逻辑层，数据展现层，三层是相对独立又相互关联。
## 2.4 系统开发工具
本系统的设计主要运用了idea和Tomcat后台服务器技术，设计中采用了JSP技术完成了页面设计过程，接下来我们主要对idea和Tomcat进行说明。

idea的功能十分强大，几乎涵盖了各种设计功能，可以设计各种平台，比如Java平台，PHP平台等，有各种平台的专用版本可以使用，极大的提高生产力。

Tomcat是一种是一个免费的开放源代码的Web 应用服务器。在访问客户比较少的情况下被经常采纳，在设计JSP 程序时成为最好的选择。换句话说，将Tomcat服务器安装到一台电脑上时，可通过它对HTML页面的访问请求进行配合。事实上，Tomcat可以看成Apache 服务器基础上的延伸，但它工作时相对比较独立，因此当tomcat工作时，事实上它是看成一个与Apache 服务器相对独立的进程运行的。

# 3系统分析
## 3.1可行性分析
通过对本新生报道管理系统实行的目的初步调查和分析，提出可行性方案并对其一一进行论证。我们在这里主要从技术可行性、经济可行性、操作可行性等方面进行分析。
### 3.1.1技术可行性
本新生报道管理系统采用JSP技术，JAVA作为开发语言，是基于WEB平台的B/S架构系统。

（1）Java提供了稳定的性能、优秀的升级性、更快速的开发、更简便的管理、全新的语言以及服务。整个系统帮用户做了大部分不重要的琐碎的工作。

（2）基于B/S模式的系统的开发已发展日趋成熟。

（3）众所周知，Java是面向对象的开发语言。程序开发员可以在idea平台上面方便的使用一些已知的解决方案。    

因此，新生报道管理系统在开发技术上具有很高可行性，且开发人员掌握了一定的开发技术，所以此系统的开发技术具有可行性。
### 3.1.2经济可行性
本新生报道管理系统采用的软件都是开源的，这样能够削减很多的精力和资源，降低开发成本。同时对计算机的配置要求也极低，即使是网吧淘汰下来的计算机也能够满足需要，因此，本系统在经济上是完全具有可行性的，所以在经济上是十分可行的。
### 3.1.3操作可行性
本新生报道管理系统的界面简单易操作，用户只要平时有在用过电脑，都能进行访问和操作。本系统具有易操作、易管理、交互性好的特点，在操作上是非常简单的，因此在操作上具有很高的可行性。

综上所述，此系统开发目标已明确，在技术、经济和操作方面都具有很高的可行性，并且投入少、功能完善、管理方便，因此系统的开发是完全可行的。
## 3.2系统性能分析
### 3.2.1 系统安全性
此新生报道管理系统要严格控制管理权限，具体要求如下：

（1）要想对新生报道管理系统进行管理，首先要依靠用户名和密码在系统中登陆，无权限的用户不可以通过任何方式登录系统和对系统的任何信息和数据进行查看，这样可以保证系统的安全可靠性和准确性。

（2）在具体实现中对不同的权限进行设定，不同权限的用户在系统中登陆后，不可以越级操作。
### 3.2.2 数据完整性
（1）所有记录信息要保持全面，信息记录内容不可以是空。

（2）各种数据间相互联系要保持正确。

（3）相同数据在不同记录中要保持一致。

3.3系统界面分析

目前，界面设计已经成为对软件质量进行评价的一条关键指标，一个好的用户界面可以使用户使用系统的信心和兴趣增加，从而使工作效率提高，JSP技术是将JAVA语言作为脚本语言的，JSP网页给整个服务器端的JAVA库单元提供了一个接口用来服务HTTP的应用程序。创建动态页面比较方便。客户界面是指软件系统与用户交互的接口，往往涵盖输出、输入、人机对话的界面格式等。

1.输出设计

输出是由电脑对输入的基本信息进行解决，生成高质量的有效信息，并使之具有一定的格式，提供给管理者使用，这是输出设计的主要责任和目标。

系统开发的过程与实施过程相反，并不是从输入设计到输出设计，而是从输出设计到输入设计。这是由于输出表格与使用者直接相联系，设计的目的应当是确保使用者可以很方便的使用输出表格，并且可以将各部门的有用信息及时的反映出来。输出设计的准绳是既要整体琢磨不同管理层的所有需要，又要简洁，不要提供给用户不需要的信息。

2.输入设计

输入数据的收集和录入是比较麻烦的，需要非常多的人力和一定设备，而且经常出错。一旦输入系统的数据不正确，那么处理后的输出就会扩大这些错误，因此输入的数据的准确性对整个系统的性能起着决定性意义。

输入设计有以下几点原则：

1）输入量应尽量保持在能够满足处理要求的最低限度。输入量越少，错误率就会越少，数据的准备时间也越少。

2）应尽可能的使输入的准备以及输入的过程进行时比较方便，这样使错误的发生率降低。

3）应尽量早检查输入数据（尽量接近原数据发生点）,以便使错误更正比较及时。

4）输入数据尽早地记录成其处理所需的形式，以防止数据由一种介质转移到另一种介质时需要转录而可能发生的错误。
## 3.3系统流程和逻辑
![](/md/blog.001.png)

图3-3登录流程图

![](/md/blog.002.png)

图3-4修改密码流程图

# 4系统概要设计
## 4.1概述
本系统采用B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式，是一个适用于Internet环境下的模型结构。只要用户能连上Internet,便可以在任何时间、任何地点使用。系统工作原理图如图4-1所示：

![](/md/blog.003.png)

图4-1系统工作原理图
## 4.2系统结构
本系统是基于B/S架构的网站系统，设计的系统功能结构图如下图所示：

![](/md/blog.004.png)

图4-2系统功能结构图



## 4.3.数据库设计
### 4.3.1数据库实体
概念设计的目标是设计出反映某个组织部门信息需求的数据库系统概念模式，数据库系统的概念模式独立于数据库系统的逻辑结构、独立于数据库管理系统（DBMS）、独立于计算机系统。

概念模式的设计方法是在需求分析的基础上，用概念数据模型（例如E-R模型）表示数据及数据之间的相互联系，设计出反映用户信息需求和处理需求的数据库系统概念模式。概念设计的目标是准确描述应用领域的信息模式，支持用户的各种应用，这样既容易转换为数据库系统逻辑模式，又容易为用户理解。数据库系统概念模式是面向现实世界的数据模型，不能直接用于数据库系统的实现。在此阶段，用户可以参与和评价数据库系统的设计，从而有利于保证数据库系统的设计与用户的需求相吻合。在概念模式的设计中，E-R模型法是最常见的设计方法。本系统的E-R图如下图所示：

（1）下图是用户实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\用户.jpg](/md/blog.005.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\用户.jpg")
用户实体属性图

（2）下图是公告实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\公告.jpg](/md/blog.006.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\公告.jpg")
公告实体属性图

（3）下图是管理员表实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\管理员表.jpg](/md/blog.007.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\管理员表.jpg")
管理员表实体属性图

（4）下图是负责人实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\负责人.jpg](/md/blog.008.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\负责人.jpg")
负责人实体属性图

（5）下图是字典表实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\字典表.jpg](/md/blog.009.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\字典表.jpg")
字典表实体属性图

（6）下图是缴费实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\缴费.jpg](/md/blog.010.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\缴费.jpg")
缴费实体属性图

（7）下图是宿舍信息实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\宿舍信息.jpg](/md/blog.011.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\宿舍信息.jpg")
宿舍信息实体属性图

（8）下图是人员与宿舍关系实体和其具备的属性。

![D:\111sheji\新生报道管理系统\xinshengbaodao\\img\人员与宿舍关系.jpg](/md/blog.012.jpeg "D:\111sheji\新生报道管理系统\xinshengbaodao\\img\人员与宿舍关系.jpg")
人员与宿舍关系实体属性图
### 4.3.2数据库设计表
新生报道管理系统需要后台数据库，下面介绍数据库中的各个表的详细信息：


表4.1配置文件表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|name|String|配置参数名称|是|
|3|value|String|配置参数值|是|
表4.2字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|create\_time|Date|创建时间|是|
表4.3负责人表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|账户|是|
|3|password|String|密码|是|
|4|fuzeren\_name|String|负责人姓名|是|
|5|fuzeren\_phone|String|负责人手机号|是|
|6|fuzeren\_id\_number|String|负责人身份证号|是|
|7|fuzeren\_photo|String|照片|是|
|8|sex\_types|Integer|性别|是|
|9|create\_time|Date|创建时间|是|
表4.4公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_types|Integer|公告类型|是|
|4|insert\_time|Date|公告时间|是|
|5|gonggao\_content|String|公告详情|是|
|6|create\_time|Date|创建时间|是|
表4.5缴费表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|学生|是|
|3|jiaofei\_name|String|缴费名目|是|
|4|jiaofei\_types|Integer|缴费类型|是|
|5|insert\_time|Date|发布时间|是|
|6|jiaofei\_yingjiao\_money|BigDecimal|应缴金额|是|
|7|jiaofei\_shishou\_money|BigDecimal|实收金额|是|
|8|jiaofei\_content|String|备注|是|
|9|create\_time|Date|创建时间|是|
表4.6宿舍信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|building|String|楼栋|是|
|3|unit|String|单元|是|
|4|room|String|房间号|是|
|5|sushe\_number|Integer|已住人员|是|
|6|create\_time|Date|创建时间|是|
表4.7人员与宿舍关系表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户id|是|
|3|sushe\_id|Integer|宿舍id|是|
|4|create\_time|Date|创建时间|是|
表4.8token表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|userid|Integer|用户id|是|
|3|username|String|用户名|是|
|4|tablename|String|表名|是|
|5|role|String|角色|是|
|6|token|String|密码|是|
|7|addtime|Date|新增时间|是|
|8|expiratedtime|Date|过期时间|是|
表4.9管理员表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|
表4.10用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|账户|是|
|3|password|String|密码|是|
|4|yonghu\_number|String|学号|是|
|5|yonghu\_name|String|学生姓名|是|
|6|yonghu\_phone|String|学生手机号|是|
|7|yonghu\_id\_number|String|学生身份证号|是|
|8|yonghu\_photo|String|学生照片|是|
|9|sex\_types|Integer|性别|是|
|10|xueyuan\_types|Integer|学院|是|
|11|zhuanye\_types|Integer|专业|是|
|12|banji\_types|Integer|班级|是|
|13|fudaoyuan\_types|Integer|辅导员|是|
|14|yonghu\_yesno\_types|Integer|是否报道|是|
|15|create\_time|Date|创建时间|是|



# 5系统详细实现
## 5.1 登录模块的实现
本次开发的新生报道管理系统在登录界面上需要用户输入用户名密码，并且需要选择对应的权限，只有三个都正确了才能访问新生报道管理系统。系统登录界面展示如图5.1所示。

![](/md/blog.013.png)

图5.1  登录界面
## 5.2 管理员模块的实现
### 5.2.1 负责人管理
管理员可以对负责人信息进行添加，修改或者是删除处理。负责人管理界面如图所示。

![](/md/blog.014.png)

图5-2负责人管理界面
### 5.2.2 公告管理
管理员能够管理公告信息，公告界面如图5-3所示。

![](/md/blog.015.png)

图5-3公告管理界面
### 5.2.3 学生管理
管理员可以对学生信息进行管理，学生管理界面展示如图所示。

![](/md/blog.016.png)

图5-4 学生管理界面
## 5.3负责人模块实现
### 5.3.1 宿舍信息管理 
负责人可以对宿舍信息进行管理，可以在相关宿舍里面添加学生。宿舍信息管理界面展示如图所示。

![](/md/blog.017.png)

图5-5宿舍信息管理界面
### 5.3.2 人员与宿舍关系列表管理 
负责人可以查看，删除，查询学生人员信息与宿舍信息直接的关系。人员与宿舍关系列表管理界面展示如图所示。

![](/md/blog.018.png)

图5-6人员与宿舍关系列表管理界面

### 5.3.2 缴费列表管理
负责人可以添加，查询，删除，修改学生的缴费列表信息，缴费列表管理界面如下：

![](/md/blog.019.png)

图5-7缴费列表管理界面
## 5.4学生模块实现
### 5.4.1 宿舍信息管理 
学生可以登录后，在宿舍信息管理里面查看自己的宿舍信息。宿舍信息管理界面展示如图所示。

![](/md/blog.020.png)

图5-8宿舍信息管理界面
### 5.4.2 缴费列表管理
学生可以在缴费列表管理里面查看自己的缴费列表信息，缴费列表界面如下：

![](/md/blog.021.png)

图5-9缴费列表界面
### 5.4.3 公告管理
学生可以在公告管理里面查看公告信息，公告管理界面如下：

![](/md/blog.022.png)

图5-10公告管理界面













