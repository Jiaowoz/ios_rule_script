# 去广告精简版

## 前言

本项目的去广告精简版分流规则由爬虫程序自动维护。

定时爬取互联网上开源的去广告精简版分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

本分流规则不包含任何知乎去广告规则。可能存在部分误拦截，建议搭配WhiteList分流规则进行修正，将其置于本分流规则之前，并进行放行。


去广告精简版分流规则中含有URL-REGEX类型，此类的规则对于HTTPS请求需要MITM使用才能生效。


<<<<<<< HEAD
最后检查时间：2020-10-26 16:28:07。

## 规则统计

总计规则：44358 条。
=======
最后检查时间：2020-11-07 00:12:31。

## 规则统计

总计规则：41859 条。
>>>>>>> upstream/master

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
<<<<<<< HEAD
| DOMAIN | 26146 |
=======
| DOMAIN | 23647 |
>>>>>>> upstream/master
| DOMAIN-KEYWORD | 47 |
| DOMAIN-SUFFIX | 17643 |
| IP-CIDR | 200 |
| URL-REGEX | 322 |
## 重复统计

去广告精简版分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Adobe)    | 34   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Adobe.list)   |   14.71%  |
<<<<<<< HEAD
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Advertising)    | 140228   | [44358](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Advertising.list)   |   31.63%  |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingTest)    | 165828   | [44358](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/AdvertisingTest.list)   |   26.75%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Apple)    | 1805   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Apple.list)   |   0.11%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BlackList)    | 778   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/BlackList.list)   |   1.29%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/China)    | 598   | [7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/China.list)   |   1.17%  |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaTest)    | 73776   | [677](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/ChinaTest.list)   |   0.92%  |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaMedia)    | 75   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/ChinaMedia.list)   |   1.33%  |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/WhiteList)    | 21   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/WhiteList.list)   |   9.52%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Google)    | 123   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Google.list)   |   8.13%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/YouTube)    | 14   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/YouTube.list)   |   7.14%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Microsoft)    | 98   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Microsoft.list)   |   1.02%  |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Niconico)    | 5   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Niconico.list)   |   20.00%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Global)    | 841   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Global.list)   |   0.24%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/GlobalMedia)    | 296   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/GlobalMedia.list)   |   1.01%  |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Hijacking)    | 209   | [202](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Hijacking.list)   |   96.65%  |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Privacy)    | 2716   | [2419](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Privacy.list)   |   89.06%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Proxy)    | 27355   | [63](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Proxy.list)   |   0.23%  |
=======
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Advertising)    | 93227   | [22213](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Advertising.list)   |   23.83%  |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingTest)    | 109520   | [21956](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/AdvertisingTest.list)   |   20.05%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Apple)    | 160   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Apple.list)   |   1.25%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BlackList)    | 781   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/BlackList.list)   |   1.28%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/China)    | 593   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/China.list)   |   1.01%  |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaTest)    | 73807   | [681](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/ChinaTest.list)   |   0.92%  |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaMedia)    | 74   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/ChinaMedia.list)   |   1.35%  |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/WhiteList)    | 21   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/WhiteList.list)   |   4.76%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Google)    | 123   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Google.list)   |   8.13%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/YouTube)    | 14   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/YouTube.list)   |   7.14%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Microsoft)    | 97   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Microsoft.list)   |   1.03%  |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Niconico)    | 5   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Niconico.list)   |   20.00%  |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Global)    | 827   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Global.list)   |   0.24%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/GlobalMedia)    | 268   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/GlobalMedia.list)   |   1.12%  |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Hijacking)    | 209   | [202](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Hijacking.list)   |   96.65%  |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Privacy)    | 2721   | [2413](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Privacy.list)   |   88.68%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Proxy)    | 27399   | [61](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Proxy.list)   |   0.22%  |
>>>>>>> upstream/master
|  [Tencent](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Tencent)    | 19   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite/Repeat/Tencent.list)   |   5.26%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Loon 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/AdvertisingLite/AdvertisingLite.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/AdvertisingLite/Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/AdvertisingLite/AdvertisingLite.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/AdvertisingLite/Domain.list

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

## 数据来源

本项目的去广告精简版分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的去广告精简版分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list
- https://raw.githubusercontent.com/NobyDa/ND-AD/master/Surge/AD_Block.txt
- https://raw.githubusercontent.com/NobyDa/Script/master/Surge/AdRule.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Guard/Advertising.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Liby.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Tide.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Reject.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/Advertising.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Advertising/LianXiangJia/LianXiangJia.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 去广告问题

本项目的去广告精简版规则仅是将网络上开源的去广告规则整合去重，**非实际规则维护者**。数据源规则无法去除的广告，本项目的去广告精简版规则也无能为力。

所以很抱歉，没办法处理关于某个APP无法去除广告的反馈，除非您能明确数据源的规则可以去除，而整合后的规则无法去除。同样，也没办法协助您处理去广告精简版规则误拦截的问题，除非您能明确告知哪条规则存在问题，我会将其加入规则黑名单，下次爬虫程序更新时将其去除。

<<<<<<< HEAD
=======
### 特定APP去广告

#### 知乎

本规则不包含知乎去广告，知乎去广告请移步：https://github.com/blackmatrix7/ios_rule_script/tree/master/script/zhihu

#### 哔哩哔哩

如需更完整的哔哩哔哩去广告，请移步：https://github.com/blackmatrix7/ios_rule_script/tree/master/script/bilibili

#### YouTube

本规则不包含YouTube去广告，请自行寻找其他解决方案。

>>>>>>> upstream/master
### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的去广告精简版分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。