# BRC：比特币请求评论

一个用于提交、讨论、分享和索引比特币生态系统中技术提案的存储库。数据模型、用户界面、脚本模板、编码格式、通信协议以及对现有行业实践的建设性批评都欢迎。目标是提供一个没有官僚主义负担的平台来分享想法。

## 贡献

欢迎并鼓励所有建设者的贡献。要提出新的 BRC，请 fork 这个仓库并使用 [~EXAMPLE.md](./~EXAMPLE.md) 作为模板创建一个新的 markdown 文件。下面概述了一个通用结构，这只是一个指导而不是严格的要求。一旦你的提案准备好分享，请提交一个 pull request 以便其他人可以审查和讨论。

要参与现有提案的讨论，只需打开一个 issue 并链接到相关的 BRC 文件。

## 迭代改进

我们相信鼓励讨论和提案的迭代改进，从而在比特币协议的范围内实现增量改进。我们欢迎改进建议，并致力于与贡献者合作改进提案，确保它们符合我们的指南。

**注意**，对标准的重大修订（超出修正错别字、添加上下文或措辞）应进入一个新的标准，该标准扩展或修订旧标准，以免破坏现有实现。

我们期待你的贡献，并帮助创建一个交易无缝形成、应用程序相互轻松交互的世界。

阅读更多关于兴趣领域的信息，请访问 [OpenStandards.cash](https://openstandards.cash)

## 结构

BRCs 存储库组织成目录，每个目录代表不同类别的提案。类别可能包括但不限于：

- 交易模板
- 比特币脚本模板
- 通信协议

每个提案应写成一个 markdown 文件，并应大致遵循以下内容：

- **标题：** 定义标准的描述性标题。
- **作者：** 谁写了这个标准，它来自哪里？如何联系他们？
- **摘要：** 对所提标准或模板的简要描述。
- **动机：** 提案背后的原因及其必要性。
- **规范：** 提案的详细技术规范。
- **实现：** 关于提案如何实现或已实现的信息。
- **参考文献：** 与提案相关的任何文献或外部资源。

**注意**，可以在文档中添加其他相关内容、标识符或其他信息。存储库中已存在的文档可能不遵循这些要求。

有助于描述和理解文档的内容，如媒体，也可以在适当的情况下添加到媒体子目录中。

请参考 [Banana-Powered Bitcoin Wallet Control Protocol](./~EXAMPLE.md) 作为一个有趣的示例模板，当你提出自己的标准时可以复制。

## 标准

BRC | 标准
-----|------------------
0    | [香蕉动力比特币钱包控制协议](./EXAMPLE.md)
1    | [交易创建](./wallet/0001.md)
2    | [数据加密和解密](./wallet/0002.md)
3    | [数字签名创建和验证](./wallet/0003.md)
4    | [输入赎回](./wallet/0004.md)
5    | [HTTP 钱包通信基质](./wallet/0005.md)
6    | [XDM 钱包通信基质](./wallet/0006.md)
7    | [窗口钱包通信基质](./wallet/0007.md)
8    | [Everett 风格交易信封](./transactions/0008.md)
9    | [简化支付验证](./transactions/0009.md)
10   | [默克尔证明标准化格式](./transactions/0010.md)
11   | [带高度的 TSC 证明格式](./transactions/0011.md)
12   | [原始交易格式](./transactions/0012.md)
13   | [TXO 交易对象格式](./transactions/0013.md)
14   | [比特币脚本二进制、十六进制和 ASM 格式](./scripts/0014.md)
15   | [比特币脚本汇编语言](./scripts/0015.md)
16   | [支付到公钥哈希](./scripts/0016.md)
17   | [支付到 R 谜题哈希](./scripts/0017.md)
18   | [支付到假返回](./scripts/0018.md)
19   | [支付到真返回](./scripts/0019.md)
20   | [没有 BRC-20](./tokens/0020.md)
21   | [推送交易](./scripts/0021.md)
22   | [覆盖网络数据同步](./overlays/0022.md)
23   | [联盟主机互连协议 (CHIP)](./overlays/0023.md)
24   | [覆盖网络查找服务](./overlays/0024.md)
25   | [联盟查找可用性协议 (CLAP)](./overlays/0025.md)
26   | [通用哈希解析协议](./overlays/0026.md)
27   | [直接支付协议 (DPP)](./payments/0027.md)
28   | [Paymail 支付目的地](./payments/0028.md)
29   | [简单认证的 BSV P2PKH 支付协议](./payments/0029.md)
30   | [交易扩展格式 (EF)](./transactions/0030.md)
31   | [Authrite 相互认证](./peer-to-peer/0031.md)
32   | [BIP32 密钥派生方案](./key-derivation/0032.md)
33   | [PeerServ 消息中继接口](./peer-to-peer/0033.md)
34   | [PeerServ 主机互连协议](./peer-to-peer/0034.md)
35   | （未使用，将分配下一个 BRC 到此编号）
36   | [比特币输出点格式](./outpoints/0036.md)
37   | [UTXO 存储格式的支出指令扩展](./outpoints/0037.md)
38   | 用户钱包数据格式
39   | 用户钱包数据格式加密扩展
40   | 用户钱包数据同步
41   | [PacketPay HTTP 支付机制](./payments/0041.md)
42   | [BSV 密钥派生方案 (BKDS)](./key-derivation/0042.md)
43   | [安全级别、协议 ID、密钥 ID 和对手方](./key-derivation/0043.md)
44   | [管理员保留和禁止的密钥派生协议](./key-derivation/0044.md)
45   | [将 UTXO 定义为比特币代币](./tokens/0045.md)
46   | [钱包交易输出跟踪（输出篮子）](./wallet/0046.md)
47   | [裸多重签名](./scripts/0047.md)
48   | [支付到推送丢弃](./scripts/0048.md)
49   | [用户不应看到地址](./opinions/0049.md)
50   | [提交收到的付款到钱包](./wallet/0050.md)
51   | [用户体验列表](./opinions/0051.md)
52   | [身份证书](./peer-to-peer/0052.md)
53   | [证书创建和揭示](./wallet/0053.md)
54   | [DPP 的混合支付模式](./payments/0054.md)
55   | [DPP 的 HTTPS 传输机制](./payments/0055.md)
56   | [统一抽象钱包到应用程序消息层](./wallet/0056.md)
57   | [mAPI 的合法用途](./opinions/0057.md)
58   | [默克尔路径 JSON 格式](./transactions/0058.md)
59   | [基于 UTXO 的覆盖网络的安全性和可扩展性优势](./opinions/0059.md)
60   | [简化比特币中的状态机事件链](./state-machines/0060.md)
61   | [复合默克尔路径格式](./transactions/0061.md)
62   | [背景评估扩展格式 (BEEF) 交易](./transactions/0062.md)
63   | [家谱身份协议](./peer-to-peer/0063.md)
64   | [覆盖网络交易历史跟踪](./overlays/0064.md)
65   | [交易标签和列表操作](./wallet/0065.md)
66   | [输出篮子移除和证书删除](./wallet/0066.md)
67   | [简化支付验证](./transactions/0067.md)
68   | [在互联网域上发布信任锚详细信息](./peer-to-peer/0068.md)
69   | [揭示密钥链接](./key-derivation/0069.md)
70   | [Paymail BEEF 交易](./payments/0070.md)
71   | [默克尔路径二进制格式](./transactions/0071.md)
72   | [在传输中保护 BRC-69 密钥链接信息](./key-derivation/0072.md)
73   | [应用访问的组权限](./wallet/0073.md)
74   | [BSV 统一默克尔路径 (BUMP) 格式](./transactions/0074.md)
75   | [主私钥的助记符](./key-derivation/0075.md)
76   | [图感知同步协议](./transactions/0076.md)
77   | [消息签名创建和验证](./peer-to-peer/0077.md)
78   | [便携式加密消息的序列化格式](./peer-to-peer/0078.md)
79   | [基于 UTXO 的覆盖网络的代币交换协议](./tokens/0079.md)
80   | [改进 BSV 多播服务的 MLD](./opinions/0080.md)
81   | [使用 P2PKH 交易的私有覆盖](./overlays/0081.md)
82   | [定义可扩展的 IPv6 多播协议，用于区块链交易广播和更新传递](./peer-to-peer/0082.md)
83   | [BSV 网络中的可扩展交易处理](./transactions/0083.md)
84   | [链接密钥派生方案](./key-derivation/0084.md)
85   | [验证身份密钥交换 (PIKE)](./peer-to-peer/0085.md)
86   | [双向认证的隐私受限类型 42 密钥派生](./key-derivation/0086.md)
87   | [BRC-22 主题管理器和 BRC-24 查找服务的标准化命名约定](./overlays/0087.md)
88   | [覆盖服务同步架构](./overlays/0088.md)
89   | [Web 3.0 标准（高级）](./opinions/0089.md)
90   | [关于曼荼罗网络的思考](./opinions/0090.md)
91   | [曼荼罗网络中的输出、覆盖和脚本](./opinions/0091.md)
92   | [曼荼罗代币协议](./tokens/0092.md)

## 许可证

此存储库中的所有内容均受 [Open BSV License](https://github.com/bitcoin-sv/bitcoin-sv/blob/master/LICENSE) 约束。
