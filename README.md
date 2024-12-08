# 2024年翻墙软件大全，几款中国还能用的VPN推荐

写本篇文章的初衷是基于我购买VPN被骗的经历，于是想写一篇翻墙软件扫盲的帖子，**避免新手小白在翻墙的时候上当受骗**。另外，我也基于目前网上目前最新的信息，汇总一些目前最流行的科学上网技术🪜️。

在我最开始尝试翻墙的时候，也是浏览了很多VPN测评网站。当时发现**❌很多博主都在推荐诸如PureVPN或者NordVPN之类的VPN**。表面上分析的头头是道，但实际上完全经不起推敲。在购买了一年的NordVPN包年会员之后，发现根本就连不上。什么换节点、高级协议之类的不过都是销售话术，请大家擦亮眼睛。

后来才知道，之所以**被坑就是因为很多人故意把VPN概念混淆**了。现在99%的国外VPN都是用来加密的，由于国外不存在防火长城，所以很少有公司愿意开发翻墙功能。早期的时候简单的VPN协议或许还能用，但**现在墙早就开发出强有力的识别模式了**。那时候本地改个Host，或者电脑上装个免费蓝灯、赛风就能轻松翻墙上外网，这种日子已经一去不复返了。

而目前最稳定的方式还是使用具有代理协议的VPN梯子。原理就是**把请求伪装成访问国外正规网站**（不在黑名单之内的，比如[本篇文章Github页面](https://github.com/vpnfast/vpnfast.github.io)就没有被墙），然后防火长城就会以为，你访问外网是为了翻墙出去学习科学技术，强国兴邦的。所以就叫做代理，理解起来其实非常简单。

最开始开发这种技术的是Shaowdowsocks的作者，不过由于翻墙效果太好，用的人太多。该作者已经被请喝茶，Github上的原始项目已被删除。不过这事儿开了个好头，从那之后，与防火长城斗智斗勇的历史开启了。后续有源源不断地热心网友贡献了翻墙协议的开发，比如大家耳熟能详的SSR、[V2ray](https://www.v2ray.com/chapter_00/install.html)、[Xray](https://github.com/XTLS/Xray-core)、[Trojan](https://github.com/trojan-gfw/trojan)和[Hysteria](https://v2.hysteria.network/zh/)等。

## 翻墙和防火长城是什么？

![翻墙](https://overwallvpn.com/wp-content/uploads/2024/08/the-great-firewall-of-china.jpg)

这一切都要从防火长城说起，[防火长城是从Great Firewall](https://zh.wikipedia.org/wiki/%E9%98%B2%E7%81%AB%E9%95%BF%E5%9F%8E)翻译过来的，是国外对中国网络防火墙的称呼，**也被称做”GFW”，中国网民更喜欢称它为”墙”**。

那么什么是科学上网呢？科学上网的意思是，通过科学技术的方法绕过防火长城的封锁，也被称做”翻墙”。而根据不同的技术，不同的科学上网工具又被称做**翻墙VPN、翻墙梯子**。

曾几何时，翻墙并没有那么难。你可以通过翻墙、VPN等词汇在百度、知乎甚至安卓、苹果应用商店找到翻墙VPN。不过自从相关法律法规颁布以来，事情就变得困难了，所有这些词汇都遭到屏蔽，已经变成了敏感词，所以你几乎很难从国内的网络平台找到有关的内容。

之所以有**科学上网、翻墙、自由上网、梯子、机场、VPN软件**这些称呼，都是为了**绕过敏感词检测**找到一款好用的翻墙软件，为了突破大陆网络限制不得已而为之。然而随着时间的推移，这些擦边球的词汇最后也变成了敏感词。因此这些词汇虽然无法在国内搜索引擎找到，但是在国外内容平台却保留了下来。

## 翻墙方法有哪些？

虽然网上各种翻墙软件成千上万，能够叫出名字的有**蓝灯、赛风、翻墙加速器、翻墙VPN、机场梯子、VPN梯子、SSR、V2Ray、WireGuard、软路由**这些称呼。其中有些是需要付费购买的VPN服务，有些则是需要自己搭建的开源代理翻墙协议。不过殊途同归，其原理都是利用国外的远程服务器，通过加密数据来绕过防火长城以达到科学上网的需求。

翻墙方法多种多样，为了避免大家被这些专业术语搞蒙，**本文汇总了市面上常用的翻墙方法和软件，以及自己搭建翻墙软件的教程**。为了榜大家理清除这些科学上网方法的区别，以下是详细内容：

## （一）、具备代理协议的国外翻墙VPN（推荐，使用简单不容易跑路）

![全球VPN Logo](https://overwallvpn.com/wp-content/uploads/2024/08/best-vpn-service.jpg)

VPN一开始是为企业提供安全数据加密的，后面被中国网友用来翻墙，这是利用了VPN软件的安全性和隐私性。当然并不是所有翻墙VPN都能用于科学上网，并且可以说**安卓Google Play、苹果App Store中的大部分VPN都是垃圾**。

因为仅仅依靠加密是不能绕过防火长城GFW封杀干扰的，因为墙有最先进的深包检测技术，可以识别到VPN的流量特征。因此翻墙VPN必须要能够伪装流量才行。这也是为什么你的翻墙软件总是连接之后几分钟就断开，平时在中国翻墙也非常不稳定的原因，毕竟传**统VPN协议在防火长城面前基本等于裸奔**。

但**国外VPN服务商的优势在于不受中国大陆政策影响**，少数国外翻墙VPN一直都在积极与防火长城对抗，他们使用升级过后的OpenVPN、WireGuard 、IKev2、L2TP/IPsec等协议，利用混淆流量的方式绕过墙的检测。

当然这里并不是说全部的国外翻墙VPN都值得推荐，相反大部分国外付费VPN都不值得你去下载使用。因为大多数国外翻墙VPN都没有重视中国市场，还是使用的传统VPN协议，没有研发专用的翻墙模式。而**免费VPN由于背景不明确，存在诸多安全隐患**，很可能靠收集用户信息或者植入木马病毒来盈利，因此一概不推荐免费翻墙VPN，本文后半部分会详细介绍。

**🚀🚀🚀🚀以下翻墙软件经过我的测试，在中国的稳定性、速度都不错，有些是翻墙VPN软件**，有些是安全的机场/梯子，可以根据自己需求选择合适的科学上网工具。在本篇在[中国VPN推荐](https://vpnfast.github.io/)指南中，我将详细测评每款科学上网软件的使用情况。

### 1.[StrongVPN](https://overwallvpn.com/go/strongvpn) - 目前唯一支持支付宝的VPN

StrongVPN能够有效绕过防火长城等网络审查，访问被封锁的网站如 Google、YouTube、Facebook 等。

![StrongVPN官网](https://overwallvpn.com/wp-content/uploads/2024/11/strong-homepage.jpg)

它提供全球 30 多个国家的 950+ 台高速服务器，支持 OpenVPN、WireGuard 等协议，连接稳定且速度快，非常适合流媒体播放、在线游戏或大文件下载。此外，StrongVPN 支持多设备同时连接（最多 12 台），兼容 Windows、macOS、iOS、Android 等多平台，甚至可以配置在路由器上，翻墙体验更灵活。对于需要翻墙的用户来说，StrongVPN 的混淆技术和不限流量的特点非常实用，同时提供 24/7 客服支持和 30 天退款保障，翻墙效果和性价比都相当出色。如果你正在寻找稳定、安全、好用的 VPN 来翻墙，StrongVPN 是一个值得尝试的选择。

### 2.[PrivateVPN](https://overwallvpn.com/go/privatevpn) - 具备隐形VPN协议的翻墙软件

从2009年创立以来，PrivateVPN始终坚守本心，将用户的使用体验放在第一位，它们承诺不记录任何用户个人信息，同时也拒绝为政府及其他机构提供用户的真实IP。

![PrivateVPN连接成功](https://overwallvpn.com/wp-content/uploads/2024/08/privatevpn-windows-simple-connected-hongkong.jpg)

> 大部分IP地址都可以绕过ChatGPT的检测，在中国大陆和香港注册和平时使用ChatGPT的时候，主要不要频繁切换IP地址。尽量使用美国IP地址，避免账号被封。

在中国需要翻墙时，首先**你得确保已经打开隐形VPN模式(StealthVPN模式)**。该模式相当于混淆功能，能够隐藏你的VPN流量，足以避免被互联网服务提供商(ISP)和其他第三方识别。 这也是PrivateVPN能绕过中国防火长城和解锁VPN封禁的关键。这是一种相当有效的代理翻墙协议，当你打开APP的时候，会出现小飞机的图标。这表明PrivateVPN应用了国产的翻墙技术，并将其内置到了VPN软件之中。**在首次连接VPN时，它会询问你是否位于中国境内**，你的需求是翻墙软件还是要绕过奈飞Netflix的地理位置封锁。当然选择在中国之后，PrivateVPN就会自动开启TCP+443端口的VPN梯子模式。

![privatevpn Windows客户端软件](https://overwallvpn.com/wp-content/uploads/2024/08/privatevpn-windows-protocol.jpg)

一般来说，用户需要的翻墙软件都是便于操作的。就这一点而言，我十分推荐新手使用PrivateVPN，因为它的苹果、安卓、Linux等系统的APP使用方式都很傻瓜，在选择好服务器后便能一键连接。

因为PrivateVPN能同时连接6台不同的设备，这样看来其性价比也是挺高的。你每月只用支付$2就能享受稳定隐秘的翻墙服务。倘若在使用过程中有什么不理解的可以直接滴滴实时客服，你需要知道的是，不管购买什么套餐你都能在30天内免费退款。

尽管PrivateVPN的服务器规模较小，每台服务器都具备[绕过中国审查制度的混淆协议](https://privatevpn.com/blog/vpn-service/686/obfuscated-servers-and-how-privatevpn-can-help-you-do-that)。其合理的分布于全球的各个角落，这样既可以有效避免用户过度导致服务器拥堵，又能保障世界各国用户在连接到远程或附近服务器时能体验优秀的速度。

### 3.[ExpressVPN](https://overwallvpn.com/go/expressvpn) - 自主研发的高速翻墙技术

ExpressVPN的大名想必已经无人不知无人不晓了。既然能在中国市场屹立十多年不到，它自然是有两把刷子的。**不过对于其口碑实际上两极分化**。有些人认为ExpressVPN在国内翻墙并不怎么样。而有些人则觉得虽然ExpressVPN贵有贵的道理。

经过个人对ExpressVPN常年使用之后的体验来说，ExpressVPN性价比中规中矩。至于连接稳定性来说，其实算是**国外VPN里面很好用的了，但有些朋友可能没有配置正确**。

不过使用的时候要记得设置一下，也就是到VPN协议里面切换到Lightway模式。这是ExpressVPN公司**针对中国地区翻墙困难而研发的高速协议**，这种方式具备隐蔽性好的优点，同样也是利用的代理方式转发流量。

![ExpressVPN 连接到香港IP地址](https://overwallvpn.com/wp-content/uploads/2024/08/expressvpn-windows-connected-hk.jpg)

香港IP节点不算多，目前只有两个选择，不过这并不代表只有两台。而美国VPN服务器要多得多，这应该是全球用户都钟爱的节点。VPN软件本身设计的很好用，在电脑、手机或其他任何平台，**都是只需要点击最大那个按钮就可连接VPN**。当然Linux命令行和路由器配置要复杂很多，那是给高级玩家预留了。

隐私方面我觉得完全不用担忧，ExpressVPN由于总部在英属维京群岛，不可能泄露数据给中国，也就不用担心使用ExpressVPN因为违法被抓的问题。虽然在中国个人使用VPN很可能会违法，但是**只要使用安全的VPN把IP隐藏好，基本不会查水表到你身上**。何况ExpressVPN的TrustedServers无磁盘服务根本不会记录你的个人信息，你大可放一万个心，它的无日志记录政策在国外是[经过普华永道安全认证](https://www.expressvpn.com/blog/pwc-audits-expressvpn-servers-to-confirm-essential-privacy-protections/)的。

然而，市面上的翻墙软件种类繁多，质量良莠不齐。在这里，我将介绍一些**❌❌❌❌不推荐在中国使用的VPN**，帮助大家避免购买低质量的VPN浪费时间和金钱。

### 4.PandaVPN(已跑路)

> 熊猫VPN在2018年成立，曾经表现出色但后来跑路了，类似的还有光年VPN。因此购买国内VPN需谨慎，尽量选择海外知名大品牌的翻墙VPN。

Panda VPN(也被称作熊猫VPN)比较特殊，可以说是翻墙VPN和机场的结合，并且技术团队都在国外，不管是安全性，还是翻墙软件本身的连接速度、稳定性都非常不错。

设备支持方面算不上多，为Mac、Windows、Linux、iOS、Android以安卓电视提供VPN软件。Panda VPN内置的代理协议类似于SSR、V2ray，在电脑端会自动代理浏览器实现科学上网，如果要全局翻墙可以切换为OpenVPN协议或者模式。

一个账号允许3台不同设备同时连接。为了解决大陆地区Apple Store无法访问的问题，Panda VPN提供了iOS测试包，可以配合TestFlight苹果官方测试平台使用，另外也可以通过修改Apple 账号地区解决，Panda VPN官网下载页面提供了相应iOS翻墙教程。

![PandaVPN 电脑端连接到香港](https://overwallvpn.com/wp-content/uploads/2024/08/pandavpn-connected-to-hongkong.jpg)

Panda VPN在全球80个国家/地区拥有超过3000台服务器，VPN软件提供的香港、日本、美国节点很多，也是中国用户科学上网经常用到的IP节点。根据不同的使用场景，Panda VPN将线路分为了解锁Netflix、Hulu、HBO、AbemaTV、Disney+的流媒体节点。

用于解决特殊时期防火长城封杀IP严重而准备的备用节点。游戏节点可以提供低延迟的体验，大多集中在日本地区。P2P种子下载速度也不错。

如果选择12个月套餐，Panda VPN价格还算便宜，每月不到$3。当然如果你想试用以下，也可以选择1个月、3个月、6个月的短时长套餐，所有套餐都提供7天退款保证，虽然相比其他全球知名VPN来说提供的退款时间不算长，但你完全可以在这期间充分试用。

虽然Panda VPN属于翻墙机场，但是却具备翻墙VPN的安全性。通过ECC安全加密技术，可以保护用户的访问数据。无日志记录策略，确保了用户的隐私安全。

而且由于服务器和团队都不在中国大陆境内，因此不用担心法律法规问题。在注册账号的时候，甚至可以不用邮箱，而使用服务器生成数字账户，还可以通过比特币支付，进一步提升隐私性。

### 5.[Astrill VPN](https://overwallvpn.com/go/astrill)

Astrill VPN是中国用户中比较流行的VPN服务提供商之一。尽管Astrill VPN 提供的美国、香港等线路，也具备伪装流量的功能，可以绕过GFW的封锁检测，但它在中国使用的速度并不理想，通常无法满足用户的需求。


![Astrill VPN电脑端连接到美国IP地址](https://overwallvpn.com/wp-content/uploads/2024/08/astrill-vpn-server-list.png)

此外，该应用程序VPN软件的界面设计简陋、反应迟钝，可能存在数据泄露问题或潜在的bug，而且价格贵得离谱，如果以月付方式，每个月需要支付30美元，如果是购买包年套餐，则需一次性支付180美元，远高于其他VPN服务提供商的价格。


### 6.[VyprVPN](https://overwallvpn.com/go/vyprvpn)

VyprVPN是一款在国外市场比较受欢迎的VPN，它的变色龙协议可以对抗中国、俄罗斯、土耳其等国家的互联网审查，但VyprVPN连接速度比较慢，VPN软件的服务器列表中显示的延迟也很高。

![VyprVPN 手机端连接到澳门](https://overwallvpn.com/wp-content/uploads/2024/08/vyprvpn-windows-.jpg)

翻墙VPN在Windows电脑端登录时可能会出现故障，苹果手机只能使用传统的OpenVPN、IKev2、L2TP/IPsec等未经技术升级的VPN协议，变色龙协议无法使用。虽然VyprVPN官网的中文支持比较好，但是最近几年中国VPN用户普遍反映VyprVPN连接不上。

#### 7.[NordVPN](https://overwallvpn.com/go/nordvpn)

NordVPN曾经是比较火的中国VPN之一，因安全技术先进，已经成为国内外很多用户的首选VPN。但是在中国大陆，由于更新VPN节点不及时，且提供的混淆服务器不多，经过我的测试后发现在中国无法连接。其次NordVPN的价格已经不算便宜了，购买方式也相对不方便，因此也不推荐在中国使用。

![NordVPN 电脑VPN软件连接到台湾](https://overwallvpn.com/wp-content/uploads/2024/08/nordvpn-windows-connected-taiwan.jpg)

### 7.[Lantern（蓝灯VPN）](https://lantern.io/zh)

Lantern是一个免费VPN软件，多年来一直备受用户欢迎，但现在已经失效并停止了维护。如果你尝试连接这个VPN，可能会遇到无法连接的问题，从Github的开源页面可以看到，这些VPN甚至早已停止了维护。另外官网也存在被钓鱼网站替换的风险，可能会收集个人数据，使用需谨慎。

得益于知名付费翻墙VPN简单易用，并且在中国长期稳定可用，以下是推荐翻墙VPN的原因：

> -   国外VPN软件服务商提供翻墙服务，**背景雄厚无跑路风险**。我们推荐的翻墙VPN大多数都稳定运营了十多年，常年与防火长城切磋，熟知中国翻墙用户的需求。
> -   全球知名的VPN软件，可以提供快速、稳定的翻墙软件，并且支持Windows、Mac、Linux、iOS、Android这些**电脑、手机、路由器等多种设备**，使用起来也更加简单，无需配置一键连接。
> -   线路丰富，除了中国大陆近距离服务器比如**香港、台湾、新加坡等VPN节点**，还有美国、英国、加拿大、澳大利亚、新西兰备用IP节点。
> -   高强的AES-256加密，以及**安全的协议，避免数据泄露**。翻墙VPN软件内置多种安全功能包括终止开关、拆分隧道、IP/DNS泄漏保护，防火长城无法破解你的上网内容，不用担心翻墙违法被抓。
> -   位于隐私保护良好的国家，不受中国大陆法律监管，也不在5眼/9眼/14眼监视联盟国范围内。**严格遵守无日志记录，没有人知道你浏览过什么内容**，隐私安全一流。
> -   **知名品牌VPN信用良好，提供30天退款保证**，如果发现在中国翻墙不好用，可以随时联系24/7在线客服申请全额退款。VPN官网还提供最新的帮助文档，可以通过工单、邮件、在线聊天获得帮助。

不能用的翻墙工具非常多，罗列它们并非本文重点，以后慢慢补充吧。

## （二）、国内机场梯子(推荐，但有风险)

![翻墙机场](https://overwallvpn.com/wp-content/uploads/2024/08/bypass-tizi.jpg)

机场又被称作代理、梯子，一般是国内个人用户自己通过SSR、V2Ray和Trojan等开源协议搭建的翻墙工具，在程序开发技术圈子比较流行。**翻墙原理是通过把流量加密伪装成普通的https流量**，让防火长城以为你正在访问国外的安全网站。虽然也能用来科学上网，但是相比较于国外翻墙VPN而言，安全性要差一些，在使用过程中可能会泄露真实IP地址和浏览数据。

优点是连接速度比较快，提供的节点更贴合中国用户的翻墙需求，亚洲IP节点要多一些，代理软件在启动连接的时候速度更快。

当然缺点也很明显，**个人用户说跑路就跑路，而且很容易被查封**，风险太大。机场大多由个人用户运维，可能价格更便宜，甚至可以微信支付宝转账支付，但是也正因为这样很容易被查水表。开源客户端软件虽然支持常见的操作系统，但是配置麻烦。

由于机场梯子存在的诸多问题，以及不安全因素，因此不推荐作为长期使用的翻墙软件：

> -   在中国大陆出售和开发翻墙软件都是违法行为，因此机场梯子这类国内**翻墙工具大多无法长期经营**，类似光年VPN、熊猫VPN这些知名国内梯子都已经跑路了，小一点的个人机场更是无法坚持超过1年。
> -   财力不足运营不善，一些**机场主大多以便宜低价来吸引新用户注册**，一旦无法维持收支平衡直接会关站了事，并且不会给你退款的。
> -   有些机场主的技术不过关，遇到服务器宕机、IP被墙、黑客攻击等翻墙软件连接问题无法及时解决，这段时间将无法翻墙，**也不要指望及时的客服支持**。
> -   机场梯子的客户端软件都是网上热心网友免费提供的，因此**客户端VPN软件使用体验非常不佳**，需要按照安装文档配置很多参数，对于新手用户很不友好。
> -   国内翻墙梯子很可能会记录你的浏览数据，甚至是你的账号密码信息。当你在科学上网的时候，**你的所有日志都会被就下来**。当然在登陆银行、购物网站的时候就很危险了。

总的来说，如果你想长期稳定地在中国使用VPN翻墙软件，**那么你最好让身边的朋友给你推荐好用的翻墙软件**，而不是网上搜索。因为都多网站都是推广文章，你很难分辨真假。而如果你只是平时偶尔Google查资料，那么机场/梯子或许也是个办法，建议购买月付套餐就行了，以免跑路。

___

### （三）、自建翻墙梯子(需要技术经验)

![翻墙梯子搭建](https://overwallvpn.com/wp-content/uploads/2024/08/Linux-Command-Line-Interface.jpg)

很多朋友可能想知道如何自己搭建翻墙梯子，**对于有程序开发经验的人来说，这并不是太难的事**。自建梯子需要使用和机场梯子一样的代理协议、租用国外VPS服务器、配置客户端翻墙工具。

虽然听起来不复杂，但是**毕竟隔行如隔山，对于新手用户或者没有IT经验的人来说**，即便参考网上的翻墙软件搭建教程，也是无法成功的。因为国外虚拟服务器(VPS)并不是Windows系统，而是没有图形化界面的linux系统，因此你还需要掌握基本的操作指令，这个学习成本非常高。

> -   况且，即便是**有技术的程序员也很少自己搭建梯子**，因为网上的梯子搭建教程很多都不是最新的甚至充斥着很多错误，那么在安装程序的时候就会遇到未知问题，非常浪费时间。
> -   而自建梯子并不是免费的，甚至要比购买付费翻墙VPN贵很多。因为你必须租用国外VPS主机，然后在服务器上安装SSR、V2ray、Trojan这些代理协议，这样代理服务器才能加密你的访问网站请求，而速度良好的线路和**香港、新加坡价格都超过100元每月**。
> -   一台VPS主机如果只用来运营翻墙梯子其实很浪费的，大部分时间带宽、CPU、内存以及磁盘都处于空闲状态。付费翻墙VPN之所以价格便宜，就是因为人家一台服务器可以分配给多个用户使用，只要做好负载均衡，可以充分利用资源降低成本。
> -   实际上**配置代理客户端软件也是很麻烦的**，不同的翻墙协议需要搭配不同的软件，而客户端软件在电脑、手机、平板、路由器上也有不同的版本兼容性。只要一个参数没有配置正确，都无法让翻墙服务器和客户端连接成功。

## 翻墙VPN软件可以干什么？

因为VPN软件的加密和伪装特性，它可以且隐藏真实IP地址，是绕过防火长城翻墙访问国外网站的最佳选择，因此成为了中国必备的翻墙VPN。平时解锁国外流媒体追剧、玩外服游戏、刷油管都是VPN软件的功劳。海外华人留学生也需要回国VPN，来加速访问国内视频音乐平台。

所以翻墙并不是VPN唯一的用途，它可以解锁地理位置封锁，加速国外网络连接，还能保护你的隐私安全，以下是利用翻墙软件科学上网的一些用途：

### 1.翻墙访问被墙的网站

众所周知，国外知名的网站诸如Google、Facebook、Twitter、Instagram、YouTube、Wikipedia都位于防火长城黑名单之内，因此你无法在中国大陆直接访问这些被墙网站，而是提示无法连接到服务器的错误。

翻墙软件会提供全球VPN服务器节点，利用常用的香港、新加坡、美国VPN服务器转发用户请求，在配合伪装良好的翻墙模式，就能绕过防火长城的检测。另外一个好处是，利用中国大陆附近的VPN节点，可以加速访问网站降低延迟，看视频更流畅，知名品牌的付费VPN都提供无流量限制。

### 2.解锁国外流媒体

要观看国外视频流媒体网站Netflix、Disney+、BBC iPlayer、Hulu、Amazon Prime Video，也需要科学上网。因为这些网站要么被墙了，要么限制中国大陆地区访问。很多翻墙VPN软件还允许P2P下载，也可以通过种子下载获得你要想要的视频。

由于版权商想赚更多的钱，因此要求流媒体平台根据不同国家提供不同视频内容，因此即便你订阅了美国Netflix套餐，也无法观看Netflix英国内容库。流媒体平台也是根据你当前的IP地址来确定你所在国家/地区。因此连接到翻墙VPN，也就可以解锁流媒体平台的地理位置限制了。

但和防火长城一样流媒体平台也在努力封杀VPN，本文推荐的翻墙软件都经过我的严格速度测试，可以解锁多个国外视频网站。最高支持1080P~4K高清视频观看，不限制每月使用流量。看电影追剧以及P2P种子下载都不在话下。

### 3.加速游戏减低延迟

国外有很多优秀的网络游戏英雄联盟、Dota 2(刀塔)、PUBG绝地求生/吃鸡、GTA5，不过由于距离太远以及游戏服务器限制中国大陆地区访问，必须借助翻墙VPN才能访问，这里VPN也可以称为游戏VPN或者游戏加速器。即便是从Steam上下载单机游戏，动则上几个G的大小不借助科学上网工具也非常吃力。

当然国内也有合法的游戏VPN加速器比如迅游、网易，不过这些游戏加速器会审查所有的网络请求，因此游戏加速器是不能用来翻墙的，只能用来加速和解锁指定的国外网游。因此推荐使用国外翻墙VPN作为加速器，这样可以做到科学上网和玩游戏两不误。连接到香港、日本、韩国这些中国大陆周边低延迟服务器，可以降低延迟加速请求。

### 4.海外华人翻墙回国

中国大陆用户需要VPN软件科学上网访问国外网站来翻墙出国，殊不知就像围城一样。海外华人留学生想要访问国内视频音乐网站平台腾讯视频、爱奇艺、优酷视频、芒果TV、抖音、B站、网易云音乐、酷狗音乐、QQ音乐也是不用容易的，因为全球流媒体的通病就是版权和地理位置限制，部分视频访问会受限并提示”抱歉，因为版本原因，你无法观看本内容”。

要解决这个问题也比较简单，只需要获得中国国内IP地址，连接到中国VPN服务器就能绕过国内平台的封锁，这种行为因此也被形象地称为翻墙回国。回国VPN加速器只需绕过平台的IP检测，相对来说要比翻墙出国简单的多。

### 5.安全加密保护隐私

良好的安全性是VPN软件必须具备的基本特性，军用级别的AES-256加密技术可以确保数据无法被破解。现如今中国普通民众的隐私安全正遭受严重的侵害，每天骚扰电话不停，就是因为数据遭到了泄露。因此在公共Wifi、4G/5G等任何网络情况下科学上网都最好连上翻墙VPN。

而且大多数国外[VPN软件](https://itkumao.com/best-vpn-china/)都提供了免费的安全功能，比如终止开关、拆分隧道、IP/DNS泄漏都可以有效防止数据意外泄露，并且隐藏你的真实IP地址，在翻墙的时候保持匿名状态。当你不小心连接访问到危险的钓鱼网站的时候，VPN软件还会发出警告，并且过滤弹窗广告。

知名品牌的翻墙软件大多注册在国外隐私良好的国家，具有严格的零日志策略，不会记录用户的浏览日志，也不用担心会收集你的敏感数据。首先由于语言文化不同，中国VPN软件用户的数据对他们来说价值不大，既不能广告推销也不能用来诈骗。并且作为运营十多年的大品牌VPN，也不会自砸招牌，因此打开放心本文推荐的这些翻墙VPN。

### 6.其他多种用途

对于外贸人士来说必须使用Gmail、WhatsApp、Skype、Telegram来与客户联系，Google、Facebook、Twitter、Instagram也是开发新客户的社交引流平台。如果你要炒美股、港股，也需要指定的IP才能开户。使用翻墙软件交易比特币也更安全。总之翻墙VPN可以为你的工作学习带来很多便利，在海淘购物的时候，还能获得当地IP独有的优惠折扣。

## 免费翻墙软件靠谱吗？

我目前没有见过任何一款可以在中国使用的[免费VPN](https://qiangup.com/free-vpn/)翻墙软件，大家耳熟能详的蓝扽(Lantern)、赛风早已成为了历史，根本连不上了。还有很多人推荐的Hide.me、Tunnelbear、ProtonVPN、 Windscribe、VPN Gate一开始就无法在中国使用，他们本身没有提供任何绕过防火长城的功能。

任何产品都是需要盈利的，免费翻墙软件也是一样，对于任何免费的东西都需要谨慎。良心一点的免费VPN软件商家会通过这种手段引流，在APP软件中限制服务器节点、速度以及带宽和流量，从而诱导用户购买付费套餐。

有些免费VPN则通过内置广告、弹窗广告赚钱，如果你一不小心点击了他们的链接，可能会跳转到一些危险的钓鱼网站。并且也会极大影响日常使用电脑。

最糟糕的情况是伪装成免费VPN的病毒软件，网上很多关于下载”破解VPN”、”VPN共享账号”的内容，当你下载软件安装之后，这些流氓软件要么在背后收集你的账号信息，要么每天开机就弹出广告，甚至是遇到勒索病毒，要求你支付比特币赎金。

**小贴士**：以上我们推荐的翻墙软件都提供30天退款保证，你可以充分免费试用，如果不满意可以联系客服退款。请远离这些危险的免费VPN。

## 翻墙工具连不上怎么办？

随着网络安全监管政策的加强，使用VPN翻墙成为了越来越多中国互联网用户的选择。但是，多种因素可能导致VPN连接不成功，例如某些节点 IP 被墙、VPN 协议遭到封锁等等。当你遇到VPN连不上的困境时，可以尝试以下解决方案。

### 1. 重启VPN软件和设备

这是最简单有效的方法之一。重启可以解决许多玄学问题。重启翻墙VPN后，还可以清除浏览器 Cookies 和 DNS 缓存，以及设备本身的缓存，从而进一步提高连接成功率。

### 2. 切换VPN服务器

如果单个节点不能连接，你可以尝试连接其他服务器，比如香港、新加坡、台湾、日本、韩国等，这些服务器通常比较稳定。如果周边节点 IP 都被封锁，你可以选择跨洋连接美国、加拿大、澳大利亚、印度、泰国等服务器。这些节点通常不太常用，所以可以规避封锁风险。另外，如果你需要留学或商务需求，意大利、西班牙、荷兰、丹麦、瑞典、瑞士、挪威、乌克兰等节点可能会更符合你的需求。

### 3. 切换VPN协议

防火长城可能会对某些协议进行封杀，如果你遇到翻墙软件连接不成功的问题，可以尝试切换到其他协议。一些知名品牌的VPN提供了自主研发的VPN协议，例如 ExpressVPN 的 Lightway、Surfshark 的 Camouflage/NoBorders、PureVPN 的 自由上网、隐形 VPN、OpenWeb 功能、变色龙协议、混淆服务器等。这些协议可以增强VPN伪装流量的特性，帮助VPN连接更稳定更顺畅。

### 4. 及时升级最新翻墙VPN

VPN 服务商为了对抗防火长城的屏蔽，会不断发布安全升级及新版本。但是，这些升级不会自动安装，你需要手动安装升级版的VPN软件，以确保你能够获得最好的体验。在升级之前，你可以进行一些简单的数据备份，以防误操作。

### 5. 联系技术支持

如果以上尝试无果，你还可以联系VPN服务商的客服和技术支持，咨询具体解决方法。他们可能会提供详细的指导，并为你解决问题。

总之，VPN 连不上的问题很常见，但是并非绝对难以解决。以上几种方法可以帮助你找到较为可靠的连接方式。在连接之前，我们建议你选择一线品牌、付费的VPN服务，以获得更高品质的连接体验。

## 科学上网要注意什么？

-   1.不要发言政治言论

如果翻墙之后去浏览有关政治的内容，并且在国内微信、微博、QQ、抖音等平台发表政治言论，这样翻墙就是违法的，轻则封号处理重则喜提新闻头条。虽然说浏览P站也属于违法行为，但是真正被处罚的案例还是不多，当然也有很倒霉的，具体原因未知。

-   2.使用国外知名VPN

目前中国市面上充斥这很多个人运营的梯子，由于缺乏安全性，会泄露真实IP地址。并且由于国内对私自搭建销售翻墙软件查的很严，很容易交了会员费就无法使用了。而国外VPN不存在这种风险，他们提供了更安全的VPN协议、电脑和手机VPN多端支持、众多备用服务器节点，30天退款保证也能确保不会踩坑。

-   3.远离国产杀毒软件

国内很少有良心的杀毒软件，腾讯电脑管家、360杀毒等名义上是杀毒，还不如说是广告客户端。安装这些软件之后，他们会在后台收集你的数据，然后时不时给你推送弹窗广告，反倒是对真正的病毒没有什么作用。其实类似的国内流氓软件还很多，可以通过科学上网下载更加纯净的国外软件。

## 翻墙软件使用技巧

-   1.选择中国大陆近距离服务器

虽说大多数翻墙软件都有一键连接和智能推荐节点，但是你也可以在服务器列表中自行选择。一般来说香港、澳门、台湾、日本、新加坡、韩国、美国都是好用的科学上网节点。

香港节点延迟是最低的，平时浏览网页、看视频、玩游戏速度都非常快。澳门节点虽然距离大陆也很近，但是VPN服务器实在不多，平时很少看到。

日本节点用来解锁国外网游是个不错的选择，很多日本用户也需要使用VPN翻墙回国观看AbemaTV、TVer、Netflix、Amazon Prime、U-Next等流媒体。

可以说美国服务器节点是万能的，毕竟很多网站服务器都在美国，如果你不知道如何选择节点，那么连接美国节点一般就不会错。翻墙访问国外网站？可。解锁视频流媒体、玩游戏、看视频、种子下载？亦可。

-   2.保持最新版本

国外VPN翻墙软件都长期有专业技术人员维护，如果有用户反应节点被墙，或者他们升级了协议，他们都会及时解决并发布新版本。如果遇到VPN连不上话，最好先升级软件。新版本的客户端不管是服务器速度，还是体验肯定都要比老版好。

-   3.启用翻墙模式

很多用户反应下载翻墙软件之后不能用，其实大多数是不会用。由于国外VPN需要先满足国外用户的安全隐私需求，因此默认情况下关闭了翻墙模式。不同的翻墙VPN对此有不同的称呼，比如变色龙(Chameleon)协议、混淆(Obfuscated)服务器、Camouflage/NoBorders模式等。遇到特殊时期，可以切换VPN协议IKEv2/IPSec、OpenVPN、IPSec、SSTP来临时解决被墙的问题。

-   4.在线客服和退款保证

遇到无法解决的问题，可以联系他们的24/7在线客服，或通过邮件联系他们，如果英语不好可以用谷歌翻译、DeepL翻译。本文推荐的翻墙VPN服务商都提供30天退款保证，如果你觉得不好用，可以随时申请全额退款，不仅不会造成损失还可以顺带免费试用VPN。

## 如何自建翻墙梯子？

自由访问互联网是我们日常生活中必不可少的一部分，但是中国由于受到网络审查限制，有些网络内容无法访问。为了绕过这些限制，中国大陆用户通常会通过翻墙软件实现科学上网。接下来我将介绍如何自建翻墙梯子。

首先，你需要一台位于海外的服务器，这台服务器一般被称为VPS（Virtual Private Server），可以通过各大云服务商(vultr、搬瓦工)购买。购买时需要选择服务器所在的国家和地区，建议选择香港、美西的服务器。

其次，你需要在这台服务器上安装翻墙软件的服务器端应用程序。目前主流的翻墙协议有Trojan、V2Ray和SSR，它们各有优缺点，需要根据自己的需求和情况选择。这里简要介绍一下这三种协议：

-   **Trojan：**绕过防火长城的方式是将流量伪装成普通的HTTPS协议，使用TLS加密确保数据安全，在不容易被墙检测到的情况下实现稳定的翻墙。
-   **V2Ray：**可以集成多种协议，包括 Socks、HTTP、Shadowsocks、VMess等，可以根据自己的需求自定义路由，提高网络性能，但配置相对较为复杂。
-   **SSR：**对原版Shadowsocks进行了改进，在混淆方面有所提高，生态完善，可以在多种操作系统上使用，但由于机场和用户较多，已经被墙针对，翻墙效果不如以前了。

选择好翻墙协议后，需要在服务器上安装相应的服务器端应用程序，具体的安装方法可以在GitHub等网站上找到相应的教程。

最后，你需要在自己的电脑、手机等设备上安装相应的客户端进行连接。大多数翻墙协议都提供了官方客户端软件，安装配置都较为简单，具体使用方式可以参考相应的官方文档。

需要注意的是，自建翻墙梯子需要一定的技术能力和经验，不建议新手尝试。此外，由于国家对出售翻墙软件的打击力度很强，自建翻墙梯子也存在一定的风险。如果你需要长期使用翻墙服务，建议选择付费翻墙VPN服务，它们的服务器稳定、速度快，而且相对安全可靠。

## 翻墙软件常见问题解答

### VPN是什么？

VPN即虚拟专用网络（Virtual Private Network）的缩写，最开始的应用是为了解决企业直接加密通讯的问题。VPN通过加密算法将用户在互联网上传输的数据加密后传输至目的地，有效地提高了数据加密的安全性，并避免了敏感数据在公共网络中被窃取和破解的风险。

另外，VPN不仅可以用于企业专网，也可以用于解决网络信息监管、突破网络封锁等问题，例如翻墙访问许多熟知的流行网站，如谷歌(Google)、Facebook、YouTube等。在这种情况下，为了能够访问被屏蔽的网站，用户可以使用VPN进行访问。由于VPN服务提供商的服务器通常设在海外，并且连接到VPN服务器后可以伪装成海外IP地址，中国用户就可以绕过封锁。

除了VPN协议之外，还有代理机场。与VPN不同的是，代理机场通过修改用户的真实IP地址，并隐藏他们的真实位置，从而达到匿名访问网站的目的。代理机场比VPN的加密程度要低，安全性也不够高，在使用上也会存在一定的风险，比如用户隐私方面的问题。近年来热心网友开发了一些可靠的代理翻墙协议，如SSR、V2ray、Trojan，这些代理加密协议有一定的翻墙能力。

总而言之，VPN通过加密算法保证了用户数据传输的安全性，可以在一定程度上保护用户的网络安全，并帮助用户突破防火长城的限制和封锁的问题。在使用上需要注意选择和安装合适的翻墙软件，在保证个人隐私和安全的基础上，充分发挥其在提高网络安全方面的优势。

### 翻墙违法吗？

关于翻墙是否违法其实早有定论，每年都有因为使用翻墙软件被抓的新闻。但其实就我观察，大部分对此都不以为然，只要你不要利用科学上网工具做违法的行为，一般不会有事。

要知道国内很多外贸人士需要在Google、Facebook、Twitter上推广自己的产品，海外留学生需要和国外朋友联系，科研人群、技术开发人群需要查资料。可以说翻墙就是他们工作和生活的一部分，也不存在违法的风险。

如果你懂技术，也最好不要私自搭建翻墙梯子，也不要将机场梯子分享给他人，更本不要在网络上售卖VPN。中国大陆网络平台都有严格的敏感词检测，并且支付宝收款本身就是证据，因此请喝茶只是时间问题。

在微信、QQ和朋友聊天的时候，也最好避免发送翻墙、科学上网、机场、梯子等敏感词，说不定哪天号就没了。

### 香港、台湾用户如何选择VPN软件？

对于香港、台湾用户来说，选择一款安全、可靠的VPN软件非常重要。在选择过程中，应该注意以下几个方面：

-   1. 加密安全性：选择支持AES256加密的VPN软件，这是认可的最高级别的加密标准之一。
-   2. 无日志政策：选择拥有严格的无日志政策的VPN，这可以确保你的在线活动不会被记录或监控。
-   3. 所在国家与资本背景：尽量选择不位于中国或有中国背景的VPN公司，以确保该公司不会受到中国法律法规的影响。
-   4. 流媒体解锁：如果你需要使用VPN来解锁国外的流媒体服务，应该选择拥有强大解锁功能的VPN，此时可以通过连接到土耳其、阿根廷等国家的VPN服务器得到更便宜的订阅价格。

如果你在前往中国大陆之前，希望能够继续使用Twitter、Instagram、Facebook、Gmail、WhatApp等服务，那么提前下载安装VPN软件将非常重要。

## VPN 如何工作的？

VPN 通过加密你的互联网流量来隐藏你的在线活动。也就是说，你的电脑、手机或其他联网设备与你的 ISP 运行的互联网服务器之间有一条隧道，你在网上所做的任何事情——访问网站、搜索内容、观看视频等都会在这条隧道里，被 ISP 或黑客看到，不仅可以看到你在网上做什么，还可以截获你通过隧道发送给 ISP 的密码和其他信息。

而 VPN 就会通过加密这条隧道，确保你的隐私得到一定的保障。你的互联网的各种欣慰首先将其发送到 VPN 的服务器，然后再通过**安全隧道**将你的互联网行为发送到你的 ISP 的服务器，在这个 VPN**安全隧道里，**伪装成来自 VPN 的 IP 地址之一的流量，这样 ISP 的服务器就无法获得你的真实 IP 地址。

## 翻墙后全球软件、网站推荐

全世界用什么软件看电影、刷视频、听音乐、交友？下面这些网站快快收藏保存！

<table><tbody><tr><td>社交网站</td><td><a href="https://www.facebook.com/" target="_blank" rel="noreferrer noopener">Facebook</a>，<a href="https://twitter.com/" target="_blank" rel="noreferrer noopener">Twitter</a>, <a href="https://www.instagram.com/" target="_blank" rel="noreferrer noopener">Instagram</a>, <a href="https://www.tumblr.com/" target="_blank" rel="noreferrer noopener">Tumblr</a>, <a href="https://www.snapchat.com/" target="_blank" rel="noreferrer noopener">Snapchat</a>, <a href="https://www.reddit.com/" target="_blank" rel="noreferrer noopener">Tumblr</a></td></tr><tr><td>日常使用网站</td><td><a href="https://www.google.com/" target="_blank" rel="noreferrer noopener">Google</a>, <a href="https://mail.google.com/" target="_blank" rel="noreferrer noopener">Gmail</a>, <a href="https://www.amazon.com/" target="_blank" rel="noreferrer noopener">Amazon</a>, <a href="https://www.ask.com/" target="_blank" rel="noreferrer noopener">Ask</a>, <a href="https://duckduckgo.com/" target="_blank" rel="noreferrer noopener">DuckDuckGo</a>, <a href="https://www.bing.com/" target="_blank" rel="noreferrer noopener">Bing</a>, <a href="https://www.quora.com/" target="_blank" rel="noreferrer noopener">Quora</a>, <a href="https://www.youtube.com/" target="_blank" rel="noreferrer noopener">Youtube</a></td></tr><tr><td>音乐网站</td><td><a href="https://tidal.com/" target="_blank" rel="noreferrer noopener">Tidal</a>, <a href="https://open.spotify.com/" target="_blank" rel="noreferrer noopener">Spotify</a>, <a href="https://www.amazon.com/music/unlimited" target="_blank" rel="noreferrer noopener">Amazon Music Unlimited</a>, <a href="https://soundcloud.com/" target="_blank" rel="noreferrer noopener">Soundcloud</a>, <a href="https://us.pandora.net/" target="_blank" rel="noreferrer noopener">Pandora</a>, <a href="https://www.apple.com/apple-music/" target="_blank" rel="noreferrer noopener">Apple Music</a>, <a href="https://www.boomplay.com/" target="_blank" rel="noreferrer noopener">Boomplay</a></td></tr><tr><td>新闻网站</td><td><a href="https://www.nytimes.com/" target="_blank" rel="noreferrer noopener">纽约时报</a>, <a href="https://www.reuters.com/" target="_blank" rel="noreferrer noopener">路透社</a>, <a href="https://www.wsj.com/" target="_blank" rel="noreferrer noopener">华尔街日报</a>, <a href="https://news.yahoo.com/" target="_blank" rel="noreferrer noopener">Yahoo! News</a>, <a href="https://www.bbc.co.uk/" target="_blank" rel="noreferrer noopener">BBC</a>, <a href="https://www.bloomberg.com/" target="_blank" rel="noreferrer noopener">Bloomberg</a>, <a href="https://www.foxnews.com/" target="_blank" rel="noreferrer noopener">Foxnews</a></td></tr><tr><td>流媒体网站</td><td><a href="https://www.disneyplus.com/" target="_blank" rel="noreferrer noopener">Disney+</a>, <a href="https://www.netflix.com/" target="_blank" rel="noreferrer noopener">Netflix</a>, <a href="https://www.hbo.com/" target="_blank" rel="noreferrer noopener">HBO</a>, <a href="https://www.imdb.com/" target="_blank" rel="noreferrer noopener">IMBD</a>, <a href="https://www.hulu.com/" target="_blank" rel="noreferrer noopener">Hulu</a>, <a href="https://www.hotstar.com/" target="_blank" rel="noreferrer noopener">HotStar</a>, <a href="https://www.espn.com/" target="_blank" rel="noreferrer noopener">ESPN</a></td></tr><tr><td>学习网站</td><td><a href="https://www.udemy.com/" target="_blank" rel="noreferrer noopener">Udemy</a>, <a href="https://www.kadenze.com/" target="_blank" rel="noreferrer noopener">Kadenze</a>, <a href="https://www.udacity.com/" target="_blank" rel="noreferrer noopener">Udacity</a>, <a href="https://www.coursera.org/" target="_blank" rel="noreferrer noopener">Coursera</a>, <a href="https://www.ewant.org/" target="_blank" rel="noreferrer noopener">Ewant</a>, <a href="https://www.ted.com/" target="_blank" rel="noreferrer noopener">TED</a>, <a href="https://www.edx.org/" target="_blank" rel="noreferrer noopener">edX</a></td></tr></tbody></table>

## 免费科学上网靠谱吗？

我们面对价格低廉，甚至免费产品时，常常容易心动。如果是免费纸巾、免费锅碗瓢盆等免费日常用品，那可以较为安全去使用。但如果你在选择各种付费 APP、翻墙软件时，请务必谨慎那些免费的东西，因为网传有各种网友使用免费科学上网工具被抓的案子。

都说“便宜没好货”，**你最好不要选择免费科学上网工具**，因为一款良好的科学上网工具需要开发者花大量金钱和时间去维护各个服务器，因此需要收费去维持公司正常运营。同时免费软件在连接上不够稳定，能够被黑客简单侵入，甚至被防火墙发现并禁止；**另外用户数据安全和隐私保护的功能也没有付费翻墙软件做得好，常常会泄露用户个人上网数据、或者真实 IP 地址。**

**另外也尽量不要选择小那些打着“纯中文”的海外市场翻墙软件**，因为一款科学上网软件只针对中文市场，它钓鱼的概率会相比同类软件大，可靠的商业翻墙工具不可能只针对中国市场运营，它们一定是国际化程度很高的 APP。

## 翻墙软件、技术黑名单

对于中国境内的翻墙用户而言，浏览器搜索关键词，便会出现五花八门的翻墙工具。对于一些不懂行的用户而言，很容易就被套路，上当受骗。**以下翻墙软件或者技术都存在钓鱼嫌疑、泄漏隐私、卷款跑路等问题**，不能保证电脑和手机的安全性，请注意识别、使用。

-   酷鸟浏览器
-   Tuber浏览器
-   绿光浏览器
-   光年 VPN
-   老王 VPN
-   Turbo VPN
-   VPN Master
-   SkyVPN

-   SuperVPN
-   SkyVPN
-   蚂蚁VPN
-   佛跳墙VPN7
-   QuickFox
-   Bean VPN
-   LimeVPN

## 翻墙/科学上网注意事项

翻墙、科学上网、VPN、梯子等都是同一个意思，就是通过技术来绕过中国防火长城的监管和限制，去访问一些国外的网站和服务。那在翻墙出去以后，是不是就可以随心所欲，畅所欲言？需要注意一些什么呢？

-   1、**不要自己租用服务器搭建 VPN 或 SSL**，更不要将你搭建的翻墙工具分享或者售卖给其他人，一旦被发现，很有可能会面临罚款或者监禁。
-   2、**不要使用中国国内的小服务商的 VPN**，以及警惕网上所谓“免费科学上网 VPN”、“免费科学上网节点”，因为这些虽然免费省钱，但你的各种账号密码、个人信息存在着巨大的泄露风险。
-   3、翻墙后**不要将国内不允许的国外内容转发至国内**，特别是转发至微信、微博、博客、QQ 等社交平台。同时不要试图对身边的人给他们讲自己在翻墙这些事，以及国外的一些事情，避免被有心之人利用。后果轻则删贴封号，重则被请喝茶、罚款、牢狱之灾等等。
-   4、**翻墙后，定期更改国内网站、APP 等重要的账户密码**，以防使用梯子的时候被上传密码导致盗号；
-   5、尽量不要用国内的手机号绑定国外的各种网站、平台账号，比如说 YouTube、Facebook、Twitter等网站；以及尽量不要留下个人的身份信息，名字，照片，亲戚家属的等个人信息；
-   6、**尽量使用 Google 等内核浏览器浏览网页，且使用无痕模式进行访问**（这样使访问信息不被记录）。切勿使用如 360安全浏览器、QQ浏览器等国产浏览器，这些浏览器可能会上传你的访问信息到后台服务器；
-   7、**注意科学上网敏感时期**，如每年春节期间、开大会期间、每年六月上旬、各种突发事件（如香港事件、新冠疫情等），这些时候翻墙可能会出现连接不上、卡顿情况，同时更要注意自己的言论发表和传播。

## 科学上网常见问题

以下是一些科学上网/实用翻墙 VPN 的一些问题，希望可以帮助到你。

### _**问：个人使用 VPN 违法吗？**_

根据《中华人民共和国计算机信息网络国际联网管理暂行规定》里第六条所说，计算机信息网络直接进行国际联网，必须使用邮电部国家公用电信网提供的国际出入口信道。任何单位和个人不得自行建立或者使用其他信道进行国际联网。也就是说，在中国个人使用和建立VPN是违法行为。

但中国有上千万的国际贸易从业者、海外投资从业者、留学生等人群，而对于这些人来说，“翻墙”对他们来说是必需品，他们必须要借助 Google、Facebook、Youtube、Skype 和 Whatsapp 等工具去开展工作**。这种不会危害国家安全的性质的翻墙一般不会遭到处罚**，不过偶尔还是有倒霉蛋因使用 VPN 被罚。但如果你科学上网的目的是访问或者讨论一些跟政治、文化和宗教相关的网站、话题，或者是观看色情网站等。那么这种翻墙性质是犯法的，一旦被发现，就会受到处罚。

### _**问：用 VPN 会被发现吗？**_

网络运营商是可以随时监控网民的互联网使用情况的。理论上说，使用 VPN 是可以被运营商发现的，而且你还是用了国产浏览器、设备、软件的话将会更容易被发现。但目前有些 VPN 加入了伪装、混淆功能来避免 VPN 流量被发现，是有一定安全保障的。只要你使用 VPN 做一些正面的事，就不用担心用 VPN 或其它翻墙梯子就不会被发现。

### _**问：代理与 VPN 哪个更好？**_

VPN 和代理都执行相同的任务来保护在线用户的身份。但使用不同的操作模式。VPN 提供了广泛的功能，如终止开关、拆分隧道、SmartDNS、协议部分等代理。**它可以帮助用户有选择地允许/阻止单个应用程序访问 Internet，VPN 翻墙工具提供更好的安全性、数据加密和可靠的连接。**而代理服务只隐藏你的身份，并且使用时非常不稳定的，容易暴露身份。因此你可以根据需要选择。不过可以说的是，凭借众多可用和安全功能，**VPN 更占优势**。

### _**问：自己搭建梯子可以吗？**_

首先根据工信部的规定：“未经电信主管部门批准，不得自行建立或租用专线（含虚拟专用网络VPN）等其他信道开展跨境经营活动。”，所以自己搭建梯子是违法的。除此之外，防火长城 GFW 对那些十分普通、甚至劣质的 VPN 服务封杀很严格，而一些优质的翻墙服务又很昂贵，于是很多热心网友或者相关技术人员也开始搭建梯子自用。但并不推荐使用这种方法。因为首先你需要具备一定的技术经验，如果是个技术新人，那么搭建过程十分复杂麻烦。**其次你还需要去购买或者租用国外 VPS，这个价格也许比订阅 VPN 服务还贵。**

另外自己搭建的梯子，一旦 IP 被封，购买的 VPN 服务器或者换 IP 都需要花钱。而使用付费 VPN则可以避免这些麻烦，不用自己搭建 VPN 服务器，不用配置客户端，还有大量备用 IP 可以切换使用。最后，价格还比自己搭建梯子便宜。

### _**问：VPN 会减慢我的设备速度吗？**_

是的，VPN 可能会稍微减慢你的设备速度。发生这种情况是因为你的连接是通过 VPN 服务器路由和加密的。数据到达目的地需要更长的时间。如果你选择口碑好、有一定实力的 VPN 服务提供商，你的速度不会受到太大影响。

### _**问：如何提升科学上网速度?**_

影响科学上网速度的原因是多种多样的，比如本地网络的带宽速度、数据路由方式、科学上网工具的质量、服务器节点的物理距离等。如果想要自己在翻墙时体验高速的网络速度，可以尝试以下几点：

**1、选择良好的网络带宽**：网络带宽是指在单位时间内传输的数据量，高带宽可以提供比低带宽更高的数据传输率，可以说，本地网络带宽速度直接影响了你的科学上网速度。因此首先需要提升本地的网络宽带。

**2、选择优质科学上网工具**：像上文提到的 PandaVPN、ExpressVPN 两款翻墙软件，都是经过自己和广大用户实际使用情况，结合口碑、功能等推荐的，而且都能在中国使用。

**3、选择离物理最近的服务器节点**：选择中国香港、中国台湾、日本、韩国、新加坡等地区的服务节点。如果你是中国用户的话，中国周边地区的服务器节点就是最佳的科学上网节点。

**4、打开科学上网工具的拆分隧道功能**：优秀的科学上网工具具有拆分隧道功能，为了提高上网速度，你可以打开该功能，这样当你访问海外网站时会使用 VPN 流量、宽带速度，当你访问国内的网站和 APP 时，你的数据流量不会经过翻墙 VPN 的服务器。

点击获取优质科学上网工具

### _**问：连接 VPN 时，可以用国内安全卫士/杀毒软件/浏览器吗？**_

尽量不要使用各种国产杀毒软件和浏览器，因为等他们自己有弹窗提醒网站风险功能，能够在后台看到你的一举一动。当你用百度浏览器等访问 Google 等网站，他们能够知道你在使用代理或者 VPN 等方式科学上网。然后再查询下你的 IP 地址，或许这个 IP 很快就被封了。**因此请使用谷歌浏览器或者其他隐私浏览器上网，用国外的杀毒软件等。**

### _**问：VPN 可以玩游戏吗？和加速器一样吗？**_

严格意义上来说，**游戏加速器不属于 VPN，也不是翻墙软件。**大部分游戏加速器只能为特定的游戏加速，提高游戏体验感，而没有翻墙功能，无法用于访问海外 Google、Youtube 等网站。而VPN等大量翻墙软件一般都具有高速功能，甚至游戏专线，可以当作游戏加速器使用。

但免费的 VPN 等翻墙软件通常会限制数据和速度，并且不具有伪装流量的协议，无法在中国稳定使用。如果你想玩《GTA5》、《绝地求生PUBG》这些海外游戏，且不需要翻墙的话，可以选择低延迟的专业游戏加速器。

### _**问：可以用免费破解版的 VPN 吗？**_

尽量**不要使用免费破解版 VPN**，因为它们可能是伪装的各种木马病毒软件，会偷偷收集你的游戏、社交等账号信息，甚至家庭住址、银行账号密码等，**存在非常大的安全风险**。而且换句话说，那些付费 VPN 都是由高端科技人才打造的，被他人破解的难度十分高，要破解这些 VPN 可以说几乎不可能。另外上文也提到了免费 VPN 的缺点和风险，破解版翻墙软件就更没有好用和稳定性可言。

### _**问：有绝对的不被发现的科学上网吗？**_

任何事情都没有绝对的说话，想要匿名上网是可以通过各种措施达到的，比如采取以下措施：

-   注册独立的网络帐号，不要使用 Google、Facebook 等。
-   使用独立的端对端加密的**匿名电子邮箱**（或者临时邮箱/一次性邮箱），用于注册国外社交网站或网络论坛，且邮箱帐号中不包含姓名、生日等个人信息。不要使用 163、QQ 邮箱等国产电子邮箱。
-   尽量不要使用需要手机号的软件或服务，不要将自己使用的真实手机号码绑定社交账号，尤其是采用实名制的中国 +86 号码和香港 +852 号码，使用**临时性短信验证码接受平台**（全程使用 Tor）。
-   可配合使用 VeraCrypt 创建的虚拟加密盘保存密码、密码库。
-   使用独立的、未安装中资软件的桌面级装置访问，尽可能使用虚拟机 / Live USB 系统。
-   不要同时在该装置上安装使用微信等任何国产 App 。
-   如使用 iOS，应自始至终使用非中国区 Apple ID，同时不要在中国区与非中国区 Apple ID 之间相互切换，iCloud 云上贵州存在网络监控隐患。

以上只是简单的一小部分匿名科学上网步骤，但对于普通人十分麻烦且没有必要，因为我们只是简单的翻墙上网而已，不存在国家之间的间谍行为，因此仅作了解，也不要尝试以身试法
