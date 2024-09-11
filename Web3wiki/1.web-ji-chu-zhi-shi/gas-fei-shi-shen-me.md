# Gas费是什么

Gas费用是以太坊网络上执行交易或智能合约操作所需支付的费用。在以太坊上，所有的操作都需要消耗计算资源，例如计算时间、内存等，这些资源的消耗会导致网络拥堵和资源竞争。Gas费用就是用来衡量这些资源消耗的单位，而实际支付的Gas费用由交易的发起者设定，并且是以以太币（Ether）的形式支付。

Gas费用的计算取决于以下几个因素：

* Gas价格（Gas Price）：Gas价格是以太坊网络上执行每个计算步骤所需支付的以太币数量，以Gwei（10^-9以太）为单位计算。Gas价格越高，交易执行的优先级越高，因为矿工更愿意打包那些支付更高Gas价格的交易。
* Gas限额（Gas Limit）：Gas限额是指交易或智能合约操作可以消耗的最大Gas数量。如果Gas消耗超出了Gas限额，交易或操作将被中止，但已经消耗的Gas费用将不会退还。

&#x20;

因此，Gas费用的总额可以通过以下公式计算：总费用 = Gas价格 × Gas限额

在以太坊上，Gas费用是由用户设定的，通常交易的发起者会根据网络拥堵情况和交易的紧急程度来设定Gas价格。较高的Gas价格会吸引矿工更快地打包交易，但也会导致交易成本增加。因此，在选择Gas价格时，用户需要权衡交易的紧急性和成本。

和银行转账不同的是，gas fee的费用是每时每刻都在变化的。如果某个时间段，区块链网络的交易特别多（我们称之为“拥堵”），矿工会优先选择高gas的交易去打包成区块，所以，如果想要较快完成交易，我们需要支付更高的费用。而有的时候，交易的人比较少，那么我们支付的gas fee就会比较低。以太坊的gas fee单位是Gwei，ETH = 1000,000,000 GWEI。

除了转账，区块链也可以完成其他操作。但是不论什么操作，都需要用到gas。一般来说，操作越复杂，gas的费用就越高。我们一般可以通过gwei的大小，判断现在是不是执行这笔交易的好时机（如果不着急的话）。如果急于完成某笔交易，那么就需要在交易的时候提供更高的gas，来让矿工更快地去把这笔交易记入区块链，即“上链”。

如何查看gas fee？

查看网站：[https://etherscan.io/gastracker](https://etherscan.io/gastracker)

chrome 拓展：[https://chromewebstore.google.com/detail/blocknative-gas-fee-estim/ablbagjepecncofimgjmdpnhnfjiecfm](https://chromewebstore.google.com/detail/blocknative-gas-fee-estim/ablbagjepecncofimgjmdpnhnfjiecfm)&#x20;

更多细节：[https://ultrasound.money/](https://ultrasound.money/)
