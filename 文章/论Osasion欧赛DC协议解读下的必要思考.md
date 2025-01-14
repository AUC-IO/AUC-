## 论Osasion欧赛DC协议解读下的必要思考

伴随最近Osasion欧赛项目消息的逐渐铺排，结合推特等内容进行梳理和学习，社区联合基金会编译组也对Osasion欧赛发布的内容做了相关梳理和汇编，以方便社区的伙伴学习和了解。首先需要解决几个问题，即DC协议你不知道的价值？什么是DC协议？DC协议来自哪里？DC协议又能解决什么样的问题？

带着以上问题进入今天的内容，首先根据推特等渠道的信息脉络，可以明确DC协议全称为民主校准无限抛物线回归协议(Democratic Calibration Unlimited Parabolic Regression Protocol)，简称：DC 协议。关于DC协议解决的内容，可以通过对中文版DC协议的解读进行了解。

可以确定的是，在对DC协议内容进行解读时，我们无法忽略一点就在于信息来源。本次协议的内容最初应是来自于2.0版本白皮书的内容，按照计划将在Osasion欧赛发展路径Q4季度进行发布。因此，暂时不提及发展路径还未披露的问题，就目前Troy网体的节点数据并没有过500列，即使先期条件全部达到，也就是按照时间推算也会在10月-12月进行披露。那么，为何会提前披露部分内容呢？根据协议信息我们得知，原来是触发DC协议激活的一个要因比较临近了。因此可以得到结论，在实际数据的发展过程中，因其变量因素与实际设计发生变化时，将会触发相应的机制。结合DC协议内容触发的相关条件，主要原因在于MPOS激励矿池跌破极限观测值，临近DC协议触发值。因此，DC协议也才可能提前与节点用户见面。

通过以上信息的总结，最真实的感受在于Osasion欧赛复杂体系设计的核心就是用户。无论是出矿、提供流动性还是市场机制，一切似乎都和用户产生较为密切的关系。简单而言，节点激活数据。而治理端依赖于社区与节点用户，其设计涉及的领域之广，体系之复杂，目前真不是一朝一夕就能看懂看全Osasion欧赛的。完成各渠道信息的梳理，再来看看实际的内容。关于DC协议的内容，主要就需要理解DC协议的作用、触发的条件以及独特的亮点。明确以上三点，理解DC协议并了解其深度含义就方便多了。

首先是DC协议的作用。从协议的触发条件就可以看出来，解答了第二个点就能完整答复第一个点的问题。若要激活DC协议，其一，激活节点矿工至第125250个节点，即完成500列共轭阵列的分布。一层建基数列完毕，开启二层核心筑基，启动 DC 协议。其二，激励矿池未出矿余额触及固定数值 (≤1010000.00000000UORA)时，契约自动激活。二者触发条件为独立运作条件，属于条件契约型绑定。契约一经触发，即激活 DC 协议对所有休眠节点检索流动性质押状态资格的认定。

以上内容清晰明了地阐明了协议的核心内容，一经梳理主要涉及三个板块，将内容完整解读后，DC协议的意义不言而喻。但这里也留存一个疑问，就是为什么第二条件的限制值是101万？虽无来源依据，我们大胆的跟区块同步节点竞选联系上，因为区块同步节点的竞选的合格票数也是101，只是目前尚且不知晓其存在的联系关系，方向判定可能来源于节点状态的判定上。

第一个版块就是关于激活DC协议契约条件，背后你不得不深究的问题。根据条件一激活节点矿工至第125250个节点，即完成500列共轭阵列的分布后触发。也就是说MPOS激励矿池余额一直高于101万UORA，原则上并不会提前触发DC协议，而协议也将在2.0白皮书公布中与大家见面。

但这里释放出明确的三个信息，一是明确质押流动性的阈值一直存在且是很早就已经设计完成的。其次，DC协议也分主动性和被动性条件触发，其含义值得深究，再者根据现有数据测算，这个DC协议按照被动条件激活，这应当算是激励机制之一。如果没有这个协议，可能会造成后续休眠节点失去保障性和激励性，于是必然会有相应的限制。因此，对于DC协议的出现，我们毫不意外。

500列主动触发，说明DC协议在早期的数据模型中就已设计完成智能合约嵌套。根据数据早期模型，体量节点激活的背后是持续倍增的休眠节点，激励矿池作为UORA流动性提供地，总量供给出现流动性欠缺，甚至引发倒挂，但UORA依据实际流动性质押量作为M1乘数，UORA不设倒挂的可能，因此机制才会存在激励矿池清零的可能，这个点很重要。换言之，就是当激励矿池不足以支付一次Staking质押收益的时候，激励矿池就会进入累计期。当激励矿池累计量大于当日应激励休眠节点UORA总量时，将启动一次Staking质押的出矿，并借此来限制通胀率维持在较低的水平，同时也杜绝滋生不公平和懈怠的可能。因此Staking质押出矿，即可按天出，也可按次出，这二者的巧妙之处也在于此。这一切也由社区型节点决定，市场机制交由市场左右，这也是贝叶斯去中心化分布的核心。

被动性触发，因激励矿池不足于支持持续性质押流动性的支出，即激励矿池未出矿余额≤1010000.00000000UORA。既然是被动性触发，也就是说主动权完全掌握在社区节点搭建的市场中，由所有Osasion欧赛人决定，其中奥义结合上一段来看。这个部分我们重点关注的点是受益方，Troy网体共轭阵列前500列以内的休眠节点都是受益者，测算数据后发现这也是属于早期布道者的激励之一。而对于早期的节点用户而言，其收益早已超过600UORA。若在500列后再启动，理论上未做限制周期，同等时间线进行预估，大概将达到1200UORA-1500UORA，按照200%的Staking固定限制计算，早期节点已超过300%，500列后将预估超过1200%。到这里，可能大家会觉得有点可惜。但值得注意的是，Osasion欧赛流动性质押的矿池，并非是链上增发虚拟数据，而是实实在在的资产数据。进入激励矿池多少未来就会出来多少，并不会多也不会少。因此，早期设计的质押流动性收益，其实只在乎两个数据，一是推动搭建社区激活节点的动态占比，一是持续质押的流动性周期。

第二个板块是关于Osasion欧赛经济模型分层的问题。现阶段，因其披露的信息有限，我们仅能根据已知的信息做条理性梳理和大胆的猜测。目前，根据文件内容，明确知晓经济模型被分为三层，且在其每一层的协议内又被分为固定式模型和非固定式模型。非固定式模型就是嵌套在底层的经济模型中等待被激活的五个契约之一，通过基础的信息尚不能判断，五个契约协议是全部与DC协议一样嵌套在一层模型中还是分别嵌套在不同层次的模型中。如果全部嵌套在一层，也就意味着至少还有四个被动型契约是暂时我们无法得知的，也是目前阶段不会公开的。而通过DC协议开篇两段的内容解读可以判断，其他契约应该也和DC协议一样属于被动型或者防护型契约，只要相关条件不被触及，我们就不可能提前知道，原因在于所有机制提前发布这对社区的搭建和节点推动似乎并无益处。

第三个板块是节点状态认证带来的窥探。关于休眠节点和社区型节点的区别在于是否使用过契约戳为依据。同时，节点账户记录的收益数据也将作为节点状态的一种验证和记录。简单而言，就已披露的信息来看，节点状态认证将会分为三个状态。当激活节点时，顺利进入MPOS端完成合格矿工的认证，此时显示的状态是：激活，获得UORA质押流动性收益（休眠节点）同时也可获得AUC的获矿权益认证。第二个状态：矿工。DC协议的介入会带来节点状态的判定，此判定采集节点Staking质押流动性UORA的收益。对于节点是否能持续获取流动性收益的评判，按照DC协议的标准，满足状态变更的节点将从激活状态变更为矿工，未来将不再获取Staking质押收益，并转化为AUC矿量的获取，实质身份即共识矿工。伴随着Troy网体数据节点激活的进程，500列后将启动关于仅向上分发250列的机制。AUC出矿量获配权限（合格矿工）退出的节点将顺利转换至节点身份，即矿工完成AUC和UORA一币双挖的历史使命，经过漫长的发展教育顺利转化为超强共识的用户，即第三个状态：节点（用户）。

这里也建议社区关注这个主线，Osasion欧赛进程的核心是什么？关注的是什么？其次，节点状态的层层递进其内在的含义与项目一开始的初心和重要使命，二者是否存在必然的联系，共识深度难易点即在此。

最后，对本文做一下总结，DC协议其内在条件设置的严谨性和尊重客观事实为依据的深度逻辑性。这也再次给到Osasion欧赛所有用户和社区一些思考，Osasion欧赛源自于用户，客观上关注节点用户成长和AUC的出矿远比关注投机性和暴利性经济崛起更有价值。同时也再次提醒我们，Osasion欧赛本质上由节点用户决定，哪怕是投机也是所有Osasion欧赛人决定，提前到来的DC协议验证了一切。

每一枚AUC都很珍贵。目前，节点获得一枚AUC需要至少524个节点的激活。根据Osasion欧赛最初的愿景，若每一枚AUC留存住一个用户将改写历史，每一个节点转换一个共识者将成就辉煌。目前，AUC出矿量4827607.75196410枚AUC，仅占总出矿量的3.51%。未来路还很长，在实验端我们要秉承科学务实的态度，在生态体系的验证中也应理性看待行业的风险和Osasion欧赛的实验未来的不确定性，敬畏市场，保持初心，砥砺前行。

媒介专栏：https://www.jinse.com/news/blockchain/1127472.html
