# light-whitepaper
## 需求分析
  随着萨尔瓦多等国家陆续接受BTC作为法币支付， BTC的法币支付属性急需解决。10分钟一个块，每秒7笔交易，每笔交易数十美金的手续费，对于BTC支付是难以容忍的。
  我们把BTC比作M0， 那基于M0衍生出来的M1的市值将会是10倍于M0，BTC 当前在大宗市值排名中，已经超过Facebook市值， 稳居前10，离以前的全球M0 黄金就差10倍的差距。在我们屈指可数的时间内， BTC就能赶超黄金市值，成为全球的通用资产 M0， 那么M0有了， 基于M0衍生的M1，当前才刚起步，这是一个超出M0一个数量级别的市值市场。
## 当前在这个赛道的对手分析
- Liquid： 二层网络（LBTC为核心的二层隐私大宗交易流通平台）。
- ChainX： 二层网络（XBTC 为核心的二层 Dapp 平台）。
- 闪电网络：不需抵押模式的BTC小额快速支付平台。
- Coming： BTC的应用入口（接入ChainX，闪电网络等二层网络隐私社交 产品）。
## ChainX网络存在的意义
  解决这个BTC的支付问题以及 BTC上可扩展的Dapp平台（如基于BTC的defi，gamefi等), 拓展M1 生态。
## 解决2大问题(BTC跨链到二层网络 + 二层网络的拓展功能)
### 如何最信任化的解决BTC二层网络的转移问题
   目前ChainX 网络已经运行了2年多的方案，（轻节点 + 多签名托管方案）。
   随着taproot升级，结合taproot的施诺尔签名和MAST合约，做成去信任化多方安全的[BTC跨链方案](https://github.com/chainx-org/SherpaX-BTC)。
### 如何拓展二层的应用生态问题
   目前已经落地的是： Coming App,有数百万用户， 可以支持ChainX上的XBTC支付。
   正在做EVM智能合约平台的迁移，让基于XBTC的Dapp可以通过BTC的二层EVM合约平台,兼容以太坊的solidity合约，以及兼容metamask等以太坊周边工具作为该平台的使用工具。让ComingApp成为这个智能合约平台的入口。
## 路线图
2021.10， ChainX 平行链[MiniX Chain]（https://miniscan.coming.chat/）, 融合 门限签名Module以及接入Coming 门限签名钱包。为后续ChainX网络的接入做准备。

2021.11， 更换当前ChainX的多签托管模式，采用taproot升级（大约在11月份中旬左右BTC网络升级）后的 MAST合约和施诺尔签名算法组合的门限签名钱包（ComingApp），更换ChainX的多签托管验证节点。
  2点好处：
- 1， 可以任意大的托管节点规模。
- 2， 托管签名可以在Coming 门限签名 钱包中，自动化发起。

2021.12， ChainX 上 EVM合约平台的融入。
