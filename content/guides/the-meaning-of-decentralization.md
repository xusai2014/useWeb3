---
title: '去中心化的意义'
description: ''
authors: ['Eric Hughes']
level: 新手
tags: ['Web3']
languages: []
featured: false
third: true
date: 2022-03-04
dateAdded: 2022-03-04
---

原文链接 [The Meaning of Decentralization](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274) 作者：Vitalik Buterin

“去中心化”这个词是在加密经济学中见到的最多的一个词之一，也是通常被视为到底是不是区块链的依据。然而这个词，也可能是被人们定义的最不恰当的一个词。数千小时的投入研究和价值数十亿美元的哈希算力都被用来试图实现去中心化，并保护和提高去中心化的程度。当人们讨论协议并变得开始激烈时，非常常见的是，一个协议（扩展协议）的支持者会声称对方的协议提案是“中心化”的，并以此作为最后击倒对方推理的论据 。

但是实际上，很多人对“去中心化”这个词的真正意义并没有那么了解。例如经常有人拿下面这张图来理解去中心化，但实际上完全没用，而这样情况屡见不鲜。

示意图：

<img src="/images/the-m-diagram.png" style="width: 40vw;max-width: 900px;display: block;margin: 10px auto;" alt="去中心化">

现在，让我们来看看问答网站上关于“分布式和分散的区别是什么？”的两个回答。
第一个回答实际上是在机械地复述上面的图表，而第二个回答则截然不同，他说：“分布式意思是说，并非交易的所有过程都在同一个地点处理，而去中心化意思是没有任何的单一个体可以对交易的处理进行控制。”与此同时，在以太坊问答社区“Ethereum stack exchange”上最顶部答案给出了和上图非常类似的图表，只是“分布式”和“去中心化”的位子换了。显然，这个澄清和说明一下是很有必要的。

### 去中心化的三个维度

当人们谈论软件体系中去中心化时，实际上谈论的是三个独立的（中心化或去中心化）纬度。虽然在某些情况下，很难看出如何在没有另一个的情况下拥有其中一个，但总的来说，它们是相对独立的。

具体如下：

 - 基础架构（去）中心化：一个系统由多少台**物理计算机**组成？在系统运行时，能够承受多少台计算机同时崩溃，而系统不受影响？
 - 体制建设（去）中心化：系统中有多少**个人或组织***拥有计算机的最终控制权？
 - 整体逻辑（去）中心化：系统中呈现和维护的**接口和数据结构**，更像一个单体还是更像一个由无数不固定的单位组成的集群？简单来说：如果把一个系统分成两部分，每部分都包含供应商和用户，那么这两部分能否单独作为独立系统运行下去？

把这三个维度画在一张表里，可能会更清楚：

<img src="/images/the-m-logic.png" style="width: 40vw;max-width: 900px;display: block;margin: 10px auto;">
<img src="/images/the-m-logic-cn.png" style="width: 40vw;max-width: 900px;display: block;margin: 10px auto;">


需要说明的是，这些维度现在的排放位置可能还比较粗糙，也存在很多争议，但我们仍然可以看一些例子，来帮助我们更好的理解这三个维度。

公司：传统的公司在体制上是集中的（一个CEO），在基础架构上是集中的（一个总部），在整体逻辑上是集中的（不能把它分成两半）

法律：现代法律体系分为大陆法和普通法，大陆法依赖于一个中心化的立法机构制定，而普通法是由许多法官依靠先例来制定的。由于现在很多法院享有自由立法权，因此大陆法有一小部分是去中心化的，对比大陆法，普通法的去中心化程度更高。但在逻辑上，两者都是中心化的（法律就是法律）。

语言：语言在逻辑上是分散的、去中心化的，Alice和Bob所讲的英语，不需要和Amy与Tony讲的英语一致。没有任何一种语言的存在需要中心化的基础设施或机构做支撑，同时英语的语法规则也不是仅由某一个人创造和掌控的。

BitTorrent网络：和英语一样，BitTorrent在逻辑上也是去中心化的，CDN也是类似，但在控制权上它们都受某家公司的控制。

区块链：在体制上去中心化、民主的(没有任何单一个体来掌控它)；在架构上去中心化、分散的（没有基础设施的中心故障点）；在逻辑上中心化（有一个共同认可的状态，并且系统表现的像一个单一计算机）。

很多时候，当别人在谈论区块链的优点时，他们描述的是拥有一个“中央数据库”的便利好处；中心化是逻辑的中心化，在许多情况下这种中心化可以说是好的（虽然来自IPFS的Juan Benet支持尽可能的推进逻辑上的去中心化，因为逻辑上去中心化的系统在网络分散区中更易存活下来，并且在世界上连通性差的区域也能很好的运行等，并见本文从Scuttlebot开始明确倡导逻辑的分散化）。

基础架构上的分散化往往导致政治上的集中，但也不一定——在正式的民主体系中，政客们在一些会晤室见面并投票，但是这个房间的维护者并不能够获得大量的决策权改变结果。在计算机化系统中，架构上而不是逻辑上的去中心化可能会发生，如果有一个在线社区为了方便而使用了一个权利集中的论坛，但是如果有一个广为接受的社会契约却遭到论坛的拥有着恶意的破坏的话，那么这个论坛里的所有的人都会离开去另外一个论坛（这个社区是由一群在其他论坛看到审查制度可能在实践中执行的一群反抗的人组成）
整体逻辑的中心化使得基础架构上的去中心化更加困难，但也不是不可能-可以看到，分散的共识网络已经被证明有用了，但却比维护BitTorrent更困难。逻辑集中化使得政治分权更加困难-在逻辑集中化系统中，更难通过简单的“活和让你活”来解决争论。



#### 为什么需要去中心化？

接下来这个问题是，为什么去中心化会有用？通常会有以下几个观点：

 - 容错性：去中心化的系统不太可能意外失效，因为他们依赖于很多独立的组件，而这些独立的组件不太可能一起意外失效。
 - 抗攻击性：去中心化的系统使得被攻击破坏和操控的成本更高，因为他们缺少敏感的中心点，而中心点则容易被比周围经济系统规模更低的成本攻击。
 - 抗合谋性：去中心化系统中参与者更难以牺牲其他参与者为代价而密谋使他们自己获利。而不得不说的是，公司和政府的领导者们密谋做一些利于自己而伤害公民、客户、员工和公众，这是常常发生的事情。

所有的三个论点都是重要和有效的。但是一旦当你开始考虑决定协议的时候，这三个论证都会导致一些有趣和不一样的结论。让我就一个一个的展开这些论证。

关于容错力，核心论证点很简单。什么会不太可能发生：一台计算机出现故障？还是十台计算机中有五台计算机同时出现故障？这个原理是毋庸置疑的，在现实生活中的很多情形中也可以用的到，包括喷气机发动，备用发电机，特别是在诸如医院，军事基地的基础设施，投资组合多元化的地方,当然还有，计算机网络。

然而，这种有效同时也很重要的去中心化，有时远不如一个偶尔用来预测的数学模型的灵丹妙药。原因就是共模故障。当然，四个喷气发动机比起一个喷气发动机来看更不容易出故障，但如果说这四个喷气发动机都是同一个工厂制造的呢？而且这四个喷气发动机都是被同一个不合格的员工制作的呢？

今天的区块链能有效设防共模故障吗？没有必要，可以参考以下场景：

1. 区块链的所有节点都在相同的客户端软件运行，这个客户端软件居然有一个错误。
2. 区块链的所有节点都在相同的客户端软件进行，这个客户端软件的开发团队居然都是社会腐败分子。
3. 提出升级更新协议的研发团队居然是社会腐败分子。
4. 在区块链的工作量证明中，70%的矿工在同一个国家，该国家政府决定为了国家安全的考虑抢占所有的采矿场。
5. 大部分的采矿硬件是由同一家公司建造的，这家公司被贿赂或者被强迫开了一个后门，允许这个硬件被随意关闭。
6. 在区块链权益证明中，70%的利率货币在同一个交易所中。

从容错能力的去中心化的整体观点会看到所有这些方面，并会想如何最小化这些问题。那么从这可以看出，一些结论自然是显而易见的；

1. 实现多方竞争关系是至关重要的
2. 协议升级背后的技术考量的知识必须是民主化的，这样更多的人可以更加自然的参与研究讨论和批评一些明显不良的协议变化。
3. 核心的开发和研究人员应该由多个公司或组织雇佣（或者可以找来许多的志愿者来填充）
4. 挖掘算法应该以最低程度的中心化思路去设计。
5. 理想情况下，我们使用权益证明的方法来完全摆脱硬件的中心化风险(当然我们也要非常小心由于使用了权益证明而可能带给我们的新的风险）。

需要注意的是，初始形式的容错要求在架构上是去中心化的，但是你想，社区的容错能力一旦控制着协议的持续发展，那么可以看出，政治上的去中心化也是非常重要的。

现在，让我们来看看抗攻击能力。在一些纯粹的经济模型中，即使去中心化完全不重要，你也可以得到你想要的结果。如果你创造出一种协议，验证器保证会在51%的攻击（即最终性回归）发生时让你损失5000万美元，那么这个验证器是被一家公司控制还是被一百家公司控制就不是那么重要了。5000万美元的经济安全保证金是5000万美元的经济安全边际成本。事实上，为什么中心化甚至能够最大化这种经济安全的概念是有着很深层次的博弈论的（现有区块链的交易模型反映了这个观点，因为包含在区块中的交易通过矿工/区块申请人实际上也是一种流转的独裁做法）。

然而，一旦你采用了更加丰富的经济模型，特别是承认强制性存在的可能的那种（或者更温和的那种比如定向的针对节点的DOS攻击），去中心化就变得更加重要了。如果你威胁一个人的生命安全，那么5000万美元也就变得对他们来说不再重要了。但是如果5000万美元在十个人中间传播，那么你必须威胁10倍的人数，并且要同时期的做这件事情。一般来说，在许多情况下，现代世界的特点有着攻击/防御的不对称性，有利于攻击者—一幢花费1000万美元的大楼可能会被花费10万美元不到就摧毁了，但攻击者的杠杠往往是亚线性的：如果说摧毁一个花费1000万美元的大楼只需要花费10万美元，那么一幢100万美元的大楼可能只需要3万美元的成本就可以摧毁了。更小的成本给出了很好的比率。

这种推理会导致什么样的结果呢？首先，他强烈的推动了权益证明机制，超过了工作量证明，因为计算机硬件更容易被检测，调节和攻击，而硬币则更容易被隐藏（权益证明机制也因为其他某些原因更容易抵抗来自其他节点的攻击）。其次，他也支持广泛分布的开发团队。第三，当在设计共识协议时，他也会暗示需要同时考虑经济模型和容错模型。

最终，我们可以得到三个论点中最复杂的一个，防勾结串通。串通这个行为很难定义，可能唯一真实有效的表达方法是说“我们都不喜欢的结合”。在现实生活中很多情况下，最理想的情况是每个人之间的协调配合都很完美，但是如果一个人可以协调配合但是其他人不行，那么就是很危险的了。

一个简单的例子是反托拉斯法，为了使市场一方的参与者更难聚集在一起设置监管上的障碍，行动上像一个垄断者以牺牲市场另一方参与者的利益和社会福利，来获得外部的利益。另一个例子是美国候选人和超级PAC之间协调的规则，尽管在实践中被证明难以实施。一个更小的例子是一些象棋比赛中。为了防止两个玩家在比赛中进行很多次游戏试图提高其中一个玩家分数的规则。无论你在哪，成熟机构防止不必要的协调的尝试无处不在。

在区块链协议的情况下，共识背后的数学和经济推理通常依赖于至关重要的不协调选择模型。或者假设说，一款游戏由许多小的可以独立做出决定的角色组成，如果一个角色在工作量证明中获得了超过1/3的矿力，那么他就可以通过私自采矿来获得巨大的利润。但是，我们真的可以说，当90%的比特币的矿力非常的好以至于他们能够出现在同一会议上，这未经协调的选择模型真的是现实的吗？

区块链倡导者也指出，区块链更加的安全，因为他们不能够跟着自己的想法随意改变他们的规则。但是如果说软件和协议的开发者们都为同一家公司工作，或者说是一家人坐在一个屋子里，那么上面这个安全也就不一定能保证了。总的来说，这些系统不应该是被一方单独垄断的。因此，你可以很确定地表示，区块链会更加的给予安全性如果参与方之间都不是协调的关系。

当然，这也显示出了一个根本的驳论。许多的社区，包括以太坊，经常被称赞说有着强壮的社区精神，并且能够很快反应协调实施，发布和激活分叉，在六天内解决服务器拒绝访问的问题。但是我们该如何促进和提高这种积极的协调能力，同时防止坏的矿工反复的协调51%的攻击，使他人陷入困境的“不良协调”呢？

有三种方式来回答这个问题：

1. 不用考虑太多不良的协调问题，反而，应该更多的尝试构建可以抵制他的协议。
2. 尽力找到一个好的媒介允许协议有足够多的协调演进和前进，但这个协调没有足够多到可以发起攻击。
3. 尽量学会区分什么是有利的协调什么是不利的协调，并且尽量使有利的协调更容易，不利的协调更困难。

第一种方式大部分是Casper设计的理念，然而，他本身是不够的，因为单靠经济本身并不能处理好另外两个方式中关于去中心化的考量。第二种方式则在程序开发上难以明确地进行，尤其是长期的开发工作，经常会出现开发不明确的意外。比如说，比特币的核心开发人员经常说英语，而矿工们大部分都说汉语，这就是一个美丽的意外。因为它创造了一种“两院制”管理办法，使协调更加困难，有利于降低同一模型生产的风险，因为英语和中文社区会因为距离和沟通上的困难而产生分歧并且争论一番，因此不太可能会两方会赞成同样的错误。

第三个就是社会挑战，在这方面的解决方案可以有：

1. 社会干预会试图提高参与者对区块链社区的忠诚度以防止市场一方的玩家只对自己这一方的人忠诚。
2. 在同一背景下提高各方市场参与者之间的沟通，让他们清楚，验证方，开发者和矿工都是处于同一阵营的，所以他们之间必须协调好来维护自己的利益抵抗其他的阵营。
3. 以减少鼓励验证方/矿工发展成为一对一的“特殊关系”，减少中心化的传递网络和其他类似的超协议机制的方式来设计这个协议。
4. 明确清楚这条协议的基本属性应该有哪些，什么事情是不应该做的，或者什么事情是只有在极端情况下才可以做的。

第三种去中心化，是以避免不希望发生的协调的去中心化，恐怕这也是最难实现的，权衡取舍是无法避免的。也许最好的解决方案是极度的依赖一个被保证是非常去中心化的一个小组，那就是：协议的用户。



1
容错性

容错性的核心概念其实很简单。一台计算机出现故障的概率和十台中的五台出现故障的概率相比，哪个更大？显然是前者。就好比10个鸡蛋集中装在一个篮子里的风险比分开装在10个篮子里，摔碎的风险更大。所以去中心化也是分散风险的一种方式。这种概念在现实生活中得到广泛应用，如喷气发动机、备用发电机，以及医院、军事的基础设施、金融组合投资、计算机网络等。

去中心化的容错能力虽然很有效、很重要，但远没有数学模型来得有用，原因在于有“共模故障”。四个发动机同时出故障的概率确实比一台发动机出故障的概率低，但如果这四台发动机都是同一个工厂制作的，并且在制作时存在同一个缺陷，又会怎样呢？这就是共模故障。

区块链能够防止共模故障吗？

不一定，我们可以看几个例子

☞ 区块链上所有的节点都在同一个客户端软件中运行，每个软件都不是100%完美的，都可能存在bug。

☞ 供区块链节点运行的客户端软件，是人为开发的，开发团队中可能存在相互勾结串联，行贪腐之事。

☞在以“工作量证明”为共识机制的区块链中，70%的矿工是在同一个城市，可能存在政府为了国家安全而对矿场进行管制的风险。

☞大多数挖矿设备都是由同一家公司生产的，这家公司可能会为了自身利益，被贿赂或被威胁，在挖矿设备上做个手脚，使得这些挖矿设备可以随意被关停。

☞在以“权益证明”为共识机制的区块链中，可能70%的币由同一家交易所持有。

很显然，将上面这些问题最小化，才能保证去中心化系统的容错性。

但怎么才能将这些问题最小化呢？

下面有一些建议

☞ 尽可能地保持多方竞争关系，协议升级必须是民主化的，这样才能让更多的人参与研究、讨论和改进协议。

☞ 核心开发者和研究人员应该由多个公司和组织的雇员组成（或者，他们中的一些人可以是志愿者）。

☞ 挖矿算法应该以将中心化风险降到最低程度的思路来设计。

☞ 理想情况下，“权益证明”机制可以摆脱硬件设备中心化的风险。（当然，权益证明也会带来新的风险）

☞ 值得注意的是，初级容错能力关注的往往是架构层面的去中心化，但当考虑一个系统长远发展时的容错能力，政治层面的去中心化更为重要。

2
抗攻击性

在某些纯经济模型中，你会发现去中心化根本不重要。如果你创建一个协议，协议规定“一旦发生51%攻击，验证者就会损失5000万美元”，那么验证者是被一家公司控制还是一百家公司控制，就无关紧要了。5000万美元是保证这个协议安全的边际成本。

但如果在一个“富经济模型”中，尤其是这个模型存在威胁的可能性（或者说针对节点的目标DOS攻击），去中心化就变得非常重要。如果你用一个人的生命安全来威胁他，5000万美元对这个人来说就不再重要了，你可以很容易的勒索走5000万美元。但如果是10个人分散持有5000万美元的话，你要想获得这笔钱，就必须分别同时威胁勒索这10个人，风险也就翻了10倍。

但在现实世界中，有一个特点，就是大部分情况下，攻击和防御并不对等，攻击者往往更有力。比如一栋造价1000万美元的大楼，可能只需要10万美元就能把它摧毁（费率是1%），摧毁100万美元的大楼则需要3万美元（费率是3%），再往下，造价越低的大楼，摧毁的费率会越高。

这说明什么？

首先，权益证明比工作量证明更优越，因为在PoW机制下，挖矿的硬件很容易被监测、掌控和攻击。其次，区块链开发团队分布的越广泛（包括地理位置的分布），系统就越安全。最后，在设计共识协议时，经济模型和容错模型都需要考虑进去。

3
抗合谋性

最后，我们终于可以讨论三个当中最复杂，听起来也最别扭的的一个了：抗合谋性。合谋这个词本身就很难定义，简单点解释，合谋就是大部分诚实的人“不喜欢的合作方式”。在很多情况下，当一部分人能够完美的协调合作，而另一部分人不能时，情况就变得危险了。

比如，反垄断法就是一个例子，为了防止市场参与者联合起来，实施垄断，损害消费者和社会福利，反垄断法就故意设置障碍以阻止他们。

在区块链中，共识安全背后的数学和经济模型也依赖这种“非协调选择模型”，换句话说，就是避免节点之间相互协调合作，也可以说它是建立在每个节点都能独立做决定的假设之上的。

区块链的拥护者们都认为区块链很安全，因为没有人能够随心所欲地改变协议规则，但如果区块链软件和协议的开发团队都来自同一个公司，在同一个办公大楼上班，那么区块链就没那么安全了。因此，如果一个区块链网络更分散，为之工作的人很难相互串通勾结，那它就更安全。

但这也揭示了一个根本性矛盾，很多社区，包括以太坊，都希望有一个强有力的社区精神，并能够快速协调工作。所以我们要怎样才能在拥有良好的协调关系下，又能够防止开发者们相互合谋，实施欺诈呢？

要解决这个问题，有三种途径

☞ 别阻止协调合作，试着用协议规则来阻止勾结合谋。这也是以太坊Casper 机制设计的指导思想。但只有这一点是不够的，因为经济学并不能完全解决去中心化的其它两类问题。

☞ 试着找到一个平衡点，使得合作能够有利于协议的发展，而同时又不会演变成合谋关系。这种方法很难明确设计，但它经常会有一些“小意外”产生。举个例子，比特币社区的核心开发者通常说英语，而矿工通常说中文，这可以说是一个“惊喜的意外”了，因为它无意中创造了“两院制”的治理机制。因为中文社区和英文社区沟通困难，减少了他们相互勾结的可能性，也减少了共模故障的风险。

☞ 建立一个区分“有益的合作”和“有害的合作”的标准，然后想办法让前者变得更容易，后者更难实现。这种方法包含一个社会学挑战，它需要做到以下几点：

制定一个干预措施，提高参与者对整个区块链社区忠诚度，减少参与者彼此间的忠诚度；

促进不同市场的参与者在同样的语境下进行沟通，这样就能减少同一阶层的参与者联合起来对抗其它阶层的可能性；

在设计协议时，减少验证者和矿工形成“一对一关系”的可能性，或者避免形成中心化的中继网络和其它类似的超级协议机制；

协议应该明确规定哪些事情不能做，哪些事情只有在非常极端的情况下才能做。

抗合谋的去中心化可能是最难实现的，因此我们要做一些权衡取舍，或许最好的方法是依赖一个能够保证去中心化的群体（即协议上的用户）。


