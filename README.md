# Statistical Arbitrage for Sports Betting Project

<p align="center">
  <img src="https://user-images.githubusercontent.com/113403062/190924275-629eaf18-183c-4781-81a2-fd0337143ba9.jpg" alt="animated"/>
</p>

*以上是输出Excel文件的示例。*

## 此项目鉴于**ryankrumenacker/ports-betting-arbitrage-project**项目修改而来。

利用**实时体育赔率 API**（https://the-odds-api.com/）获取数据，整理统计后在在全球即将到来的体育赛事中寻找赔率差的套利机会。
## 简单的比喻：

### 比如A-B两支球队比赛，在**A平台**的赔率是A（45%）- B（55%），但在**B平台**的赔率是A（65%）- B（35%），那么我们在**A平台**买B赢，在**B平台**买A赢，就可以保证无论A-B两支球队哪支球队获胜，我们都能获得稳定的收益。

**实时体育赔率 API**是一个免费的、开放源代码的 API，可以跟踪美国各地的博彩公司提供的任何给定的体育赛事的当前赔率。通过 API 的数据，该程序能够找到在八个最近即将到来的体育赛事中的所有可能的套利机会。一旦程序找到这些机会并进行了必要的计算以使用户了解输出，它会将所有发现写入一个 Excel 文件供用户访问。该文件包括**ID**和**Sport Key**（这两个指标都是针对实时体育赔率 API 的特定指标），以及每个博彩公司的每个相应赌注的**预期收益、书商、名称、赔率**和**购买金额**。文件中的每一行都代表一个套利机会。

