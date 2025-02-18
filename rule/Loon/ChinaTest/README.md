# ChinaTest

## 前言

本项目的ChinaTest分流规则由爬虫程序自动维护。

定时爬取互联网上开源的ChinaTest分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2021-01-11 03:02:20。

## 规则统计

总计规则：72395 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 72331 |
| USER-AGENT | 33 |
| DOMAIN | 11 |
| IP-CIDR | 4 |
| DOMAIN-KEYWORD | 12 |
| IP-CIDR6 | 4 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Loon 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/ChinaTest/ChinaTest.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Loon/ChinaTest/ChinaTest_Domain.list

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

## 重复统计

当前分流规则，已包含以下子规则：

- China

除非特殊需求，否则不建议重复引用。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [WhiteList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/WhiteList)    | 23   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   4.35% |
|  [Bilibili](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Bilibili)    | 60   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   33.33% |
|  [DiDi](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/DiDi)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Meitu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Meitu)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Pinduoduo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Pinduoduo)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Sina](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Sina)    | 10   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   90.0% |
|  [Baidu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Baidu)    | 265   | [70](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   26.42% |
|  [360](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/360)    | 249   | [66](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   26.51% |
|  [4399](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/4399)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   76.92% |
|  [VipShop](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/VipShop)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [XiaoMi](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/XiaoMi)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Weibo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Weibo)    | 4   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   75.0% |
|  [ByteDance](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ByteDance)    | 211   | [61](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   28.91% |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/China)    | 689   | [685](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   99.42% |
|  [SohuSogo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/SohuSogo)    | 10   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   80.0% |
|  [CCTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CCTV)    | 42   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   14.29% |
|  [Xunlei](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Xunlei)    | 8   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   75.0% |
|  [Huawei](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Huawei)    | 9   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   77.78% |
|  [Tencent](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Tencent)    | 19   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [ChinaMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaMedia)    | 141   | [49](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   34.75% |
|  [NetEase](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/NetEase)    | 22   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   40.91% |
|  [iQiyi](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/iQiyi)    | 17   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   5.88% |
|  [Douyu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Douyu)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Himalaya](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Himalaya)    | 4   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [Alibaba](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Alibaba)    | 1222   | [257](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   21.03% |
|  [115](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/115)    | 9   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   55.56% |
|  [12306](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/12306)    | 3   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   33.33% |
|  [17173](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/17173)    | 57   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   21.05% |
|  [178](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/178)    | 22   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [17zuoye](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/17zuoye)    | 24   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   16.67% |
|  [36kr](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/36kr)    | 2   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [51Job](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/51Job)    | 19   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   31.58% |
|  [56](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/56)    | 10   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [58TongCheng](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/58TongCheng)    | 49   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   44.9% |
|  [ABC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ABC)    | 6   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   16.67% |
|  [Agora](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Agora)    | 3   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   66.67% |
|  [AliPay](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AliPay)    | 13   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   61.54% |
|  [AnTianKeJi](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AnTianKeJi)    | 11   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   27.27% |
|  [Anjuke](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Anjuke)    | 8   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [BOC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BOC)    | 15   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   66.67% |
|  [BOCOM](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BOCOM)    | 6   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [BaiFenDian](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BaiFenDian)    | 10   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   20.0% |
|  [BaoFengYingYin](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BaoFengYingYin)    | 16   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   18.75% |
|  [BianFeng](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BianFeng)    | 100   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   8.0% |
|  [Bootcss](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Bootcss)    | 3   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   66.67% |
|  [CCB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CCB)    | 13   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   46.15% |
|  [CEB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CEB)    | 15   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   93.33% |
|  [CGB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CGB)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   25.0% |
|  [CIBN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CIBN)    | 71   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   12.68% |
|  [CITIC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CITIC)    | 27   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   55.56% |
|  [CMB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CMB)    | 17   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   11.76% |
|  [CNKI](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CNKI)    | 17   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   11.76% |
|  [CSDN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CSDN)    | 15   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   26.67% |
|  [AcFun](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AcFun)    | 5   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   40.0% |
|  [CaiNiao](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CaiNiao)    | 9   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   44.44% |
|  [CaiXinChuanMei](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/CaiXinChuanMei)    | 24   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   20.83% |
|  [Camera360](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Camera360)    | 8   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   37.5% |
|  [ChinaMobile](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaMobile)    | 28   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   53.57% |
|  [ChinaNews](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaNews)    | 4   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   25.0% |
|  [ChinaTelecom](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaTelecom)    | 83   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   22.89% |
|  [ChinaUnicom](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChinaUnicom)    | 24   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   29.17% |
|  [ChuangKeTie](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChuangKeTie)    | 5   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   20.0% |
|  [ChunYou](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/ChunYou)    | 39   | [25](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   64.1% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Apple)    | 102   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   7.84% |
|  [iCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/iCloud)    | 51   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   5.88% |
|  [OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/OneDrive)    | 17   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   5.88% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Microsoft)    | 99   | [30](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   30.3% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Google)    | 111   | [35](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   31.53% |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingLite)    | 20730   | [651](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   3.14% |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Advertising)    | 46940   | [1151](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   2.45% |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AdvertisingTest)    | 67125   | [1179](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   1.76% |
|  [Hijacking](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Hijacking)    | 219   | [56](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   25.57% |
|  [Privacy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Privacy)    | 2813   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   0.07% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Game)    | 63   | [17](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   26.98% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Blizzard)    | 6   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Steam)    | 16   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/SteamCN)    | 14   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   35.71% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Proxy)    | 27941   | [179](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   0.64% |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Global)    | 1290   | [41](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   3.18% |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/GlobalMedia)    | 1145   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   0.17% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/BlackList)    | 770   | [27](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   3.51% |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Speedtest)    | 5   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   40.0% |
|  [TikTok](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/TikTok)    | 11   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   18.18% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/PayPal)    | 5   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   80.0% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Sony)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   100.0% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Developer)    | 23   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   4.35% |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Scholar)    | 76   | [60](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   78.95% |
|  [TeamViewer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/TeamViewer)    | 10   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   50.0% |
|  [AsianMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/AsianMedia)    | 27   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   51.85% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Adobe)    | 34   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   5.88% |
|  [Lan](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Loon/Lan)    | 25   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Loon/ChinaTest/ChinaTest_Repeat.list)   |   12.0% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的ChinaTest分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的ChinaTest分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/China.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/China.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/China.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Mainland.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/CN.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/direct.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/China/China.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Domestic.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Domestic.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Region/China.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 程序特点

### 断链处理

对于某些已删除或失效的数据源，继续使用本地缓存的文件，减少因为断链造成的影响。

### 规则过滤

通过关键字、正则、模糊匹配三种方式对规则进行过滤，以移除部分数据源中的错误规则。

### 合并去重

不仅对完全相同的规则进行去重，还会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6等规则间的包含关系进行合并去重。

### 域名解析

对DOMAIN类型的规则进行DNS解析记录查询，丢弃连续多次无法解析的域名。

### 正则合并

通过程序对相似正则进行合并，不定时手动核验正则合并结果。

### 正则推导

通过程序对含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的ChinaTest分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。