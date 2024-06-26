# megtog

<https://twitter.com/megtog>

## Notes

### 2024.4.8

今天搁置了 spec 学习

看了一篇 [ICO 旧文](https://web.archive.org/web/20210818204534/https://www.newyorker.com/tech/annals-of-technology/pumpers-dumpers-and-shills-the-skycoin-saga)

> He boasted that Obelisk was written by Houwu Chen, a developer who had worked on Ethereum, the second-most popular cryptocurrency platform. He posted an academic paper written by Chen on the Skycoin Web site, claiming that it was a Skycoin white paper. But when Stephens reached out to Chen, he got no response. “We kept trying to chase people down to ask details, and it was slowly revealed it just . . . didn’t exist,” he told me. In a later discussion about technical details, a Skycoin “community manager” told coinholders that “it’s too advanced to share” and that the company “can’t trust the public with it.” When pressed, Smietana wrote, of Chen, “He is a recluse, I doubt anyone can contact him or he would respond.” Smietana eventually told me that Chen had taken a payment of a million Skycoins for his work on the white paper and then left the project. (Chen declined to comment, saying, “Just don’t put my name in the article. That’s my statement.”)

  * 搜了搜关于 Houwu Chen 的信息，大概是早期 [Pyethereum 的开发者](https://blog.ethereum.org/2014/04/10/pyethereum-and-serpent-programming-guide)
    *  [照片](https://web.archive.org/web/20140509173418/https://www.ethereum.org/)
    *  [Sky: Opinion Dynamics Based Consensus for P2P Network with Trust Relationships](https://arxiv.org/abs/1501.06238v8) 这文章粗看应该挺有料的，但后来撤稿了。这文章致谢了万向的[BlockGrant X](https://web.archive.org/web/20151219053234/http://blockchainlabs.org/blockgrant-x-en/)，但看不出来具体是哪项。


### 2024.4.7

读了一些旧历史

* [Deprecating EIP 1011 in favor of a Casper+Sharding design](https://medium.com/@djrtwo/casper-%EF%B8%8F-sharding-28a90077f121) 发于 Jun 16 2018
  * 之前的想法 <https://twitter.com/megtog/status/1539972179961319427>
  * [eip-1011](https://eips.ethereum.org/EIPS/eip-1011) 结合了 PoW + PoS
  * consensus-spec 项目是在这之后启动的（Sep 20 2018）
 
* 在 consensus-spec 的 git 记录里考古
  * vitalik <https://github.com/ethereum/research/commit/093aad4a7820fd4a06be370a5b1b1586d39b48c3>
  * protolambda <https://github.com/ethereum/consensus-specs/issues/793>


### 2024.4.6

这几天清明假期有点疏于学习

这几天计划结合 MaxEB 学习 CL Specs
* 结合 week 6 内容，学习 pyspec 使用
* 学习 python 的依赖包相关知识 <https://peps.python.org/pep-0508/#extras>
* 后续学习使用 <https://github.com/ethereum/consensus-spec-tests>

### 2024.4.4 MaxEB

> Understandably, there is a lot of hype around MaxEB due to its capability to cap/reduce validator sizes, decrease network messages, and save bandwidth for solo stakers. However, people tend to overlook EIP-7549: Move committee index outside Attestation
>
> Which achieves similar benefits without necessitating validator consolidation. Assuming perfect aggregation and a 1M validator 64-committee size, we can observe a reduction from 18KB to 4KB
>
> Both solutions will coexist and complement each other, but it's essential not to underestimate the advantages of having a superior attestation aggregation structure. See @mkalinin2's notes for more detail:
>
> https://hackmd.io/@n0ble/eip7549_onchain_aggregates

<https://twitter.com/terencechain/status/1771231145583137043>

<https://ethresear.ch/t/increase-the-max-effective-balance-a-modest-proposal/15801>

