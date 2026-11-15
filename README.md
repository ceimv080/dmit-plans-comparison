# dmit套餐对比：Premium、Eyeball、T1 差在哪？同配置差多少钱？香港东京值不值这个价？（附三机房全套餐价格表）

面向国内访问的建站业务，洛杉矶 Premium AN4 TINY 是 DMIT 全系里最划算的一台：$88.88/年，三网 CN2 GIA。流量吃紧的话，同价位的 Eyeball 给 1.5 倍流量。只跑脚本、做落地，或者访客主要在海外，T1 的 WEE $36.90/年就够。

下面把三档线路、三个机房、全部套餐价格摆进表里，再讲清几个多数对比文一句话带过的差异：同价不同流量、AN4 与 AN5 的 35% 差价、香港 T1 没有大陆优化这个坑，以及退款、换 IP、优惠码的具体条件。

价格数据来自第三方整理的官网定价（标注 2026 年 4 月更新），距现在已有时日，套餐与库存变动频繁，下单前请以官网实时价格和库存为准。

> **选购速览**
>
> - 国内用户建站、要晚高峰稳：洛杉矶 Premium AN4 TINY，$88.88/年
> - 流量大、线路可以退一档：洛杉矶 Eyeball AN4 TINY，$88.88/年，流量 1.5 倍
> - 只跑脚本 / 海外业务 / 落地机：洛杉矶 T1 WEE，$36.90/年，或 V2C2G $14.90/月
> - 必须低延迟（华南、香港周边用户）：香港 Premium TINY，$39.90/月
>
> 👉 [查看 DMIT 全部套餐与实时价格](https://www.dmit.io/aff.php?aff=9081)

## 三档线路到底是什么

DMIT 每个机房都分三档网络，套餐名字里的 Pro、EB、T1 就是这个意思。三档的差别不在 CPU 和内存，在回程走哪条线。

| 档位 | 线路 | 适合谁 | 价格位置 |
| --- | --- | --- | --- |
| Premium（Pro） | 三网 CN2 GIA（电信 AS4809），去回程均优化 | 用户在国内、网站或 API 不能晚高峰崩 | 最高 |
| Eyeball（EB） | 电信/联通 AS9929 + 移动 CMIN2（AS58807） | 流量需求大，能接受线路低半档 | 与 Pro 同价或略低 |
| Tier 1（T1） | 国际 Tier 1 互联，无中国大陆专项优化 | 访客在海外、跑脚本、做大流量落地 | 最低 |

全系 KVM 虚拟化，独立内核、资源真隔离，底层是 AMD EPYC 加企业级 SSD。KVM 的成本比 OpenVZ 高，这也是 DMIT 没法做到低价商家那个价位的原因。系统方面支持主流 Linux 发行版（Debian、Ubuntu、CentOS 等），装 BBR 之类自定义内核没问题。

延迟口径：洛杉矶国内访问约 150–180ms，香港约 20–50ms，东京资料只写"适合日本 IP / 亚太低延迟"，没有给具体毫秒数，别拿网上抄来的数字当准。

## 洛杉矶全套餐价格

洛杉矶是主力机房，套餐最多，也是性价比最集中的地方。AN4 是 EPYC 9004 平台，AN5 是 EPYC 9005，同配置 AN5 更贵。

### LAX Premium（三网 CN2 GIA）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY（AN4） | 1核 / 2G / 20G | 1000GB / 1Gbps | $88.88/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| TINY（AN5） | 1核 / 2G / 20G | 1000GB / 1Gbps | $119.99/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| Pocket（AN4） | 2核 / 2G / 40G | 1500GB / 4Gbps | $159.98/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| Pocket（AN5） | 2核 / 2G / 40G | 1500GB / 4Gbps | $203.90/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER（AN4） | 2核 / 2G / 80G | 3000GB / 10Gbps | $29.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER（AN5） | 2核 / 2G / 80G | 3000GB / 10Gbps | $38.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI（AN4） | 4核 / 4G / 80G | 5000GB / 10Gbps | $58.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI（AN5） | 4核 / 4G / 80G | 5000GB / 10Gbps | $76.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO（AN4） | 4核 / 4G / 160G | 7000GB / 10Gbps | $74.99/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO（AN5） | 4核 / 4G / 160G | 7000GB / 10Gbps | $99.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM（AN4） | 6核 / 8G / 160G | 15000GB / 10Gbps | $168.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM（AN5） | 6核 / 8G / 160G | 15000GB / 10Gbps | $219.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE（AN4） | 8核 / 16G / 320G | 25000GB / 10Gbps | $338.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT（AN4） | 12核 / 24G / 640G | 50000GB / 10Gbps | $619.99/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT（AN5） | 12核 / 24G / 640G | 50000GB / 10Gbps | $839.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

AN5 的 LARGE 档在不同资料里出现过 $2759.40/半年这个数，和同档 AN4 的 $338.88/月 完全对不上，按录入错误处理，没列进表，需要的话直接去官网看。

### LAX Eyeball（AS9929 + CMIN2）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY（AN4） | 1核 / 2G / 20G | 1500GB / 2Gbps | $88.88/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| TINY（AN5） | 1核 / 2G / 20G | 1500GB / 2Gbps | $119.99/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| Pocket（AN4） | 2核 / 2G / 40G | 3000GB / 4Gbps | $159.98/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| Pocket（AN5） | 2核 / 2G / 40G | 3000GB / 4Gbps | $203.90/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER（AN4） | 2核 / 2G / 80G | 5000GB / 10Gbps | $29.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER（AN5） | 2核 / 2G / 80G | 5000GB / 10Gbps | $38.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI（AN4） | 4核 / 4G / 80G | 10000GB / 10Gbps | $58.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI（AN5） | 4核 / 4G / 80G | 10000GB / 10Gbps | $76.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO（AN4） | 4核 / 4G / 160G | 14000GB / 10Gbps | $74.99/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO（AN5） | 4核 / 4G / 160G | 14000GB / 10Gbps | $99.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM（AN4） | 6核 / 8G / 160G | 30000GB / 10Gbps | $168.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM（AN5） | 6核 / 8G / 160G | 30000GB / 10Gbps | $219.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE（AN4） | 8核 / 16G / 320G | 50000GB / 10Gbps | $338.88/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT（AN4） | 12核 / 24G / 640G | 100000GB / 10Gbps | $619.99/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT（AN5） | 12核 / 24G / 640G | 100000GB / 10Gbps | $839.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### LAX Tier 1

| 套餐 | 配置（CPU/内存/SSD） | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| WEE（AN4） | 1核 / 1G / 20G | 1000GB / — | $36.90/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| TINY（AN4） | 1核 / 1G / 20G | 2000GB / — | $6.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER（AN4） | 2核 / 2G / 40G | 4000GB / 10Gbps | $12.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI（AN4） | 2核 / 4G / 80G | 8000GB / 10Gbps | $21.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO（AN4） | 4核 / 4G / 120G | 16000GB / 10Gbps | $32.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| G2C4G（AN4） | 2核 / 4G / 80G | 4000GB / 10Gbps | $16.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| G4C8G（AN4） | 4核 / 8G / 160G | 8000GB / 10Gbps | $36.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| G8C16G（AN4） | 8核 / 16G / 320G | 12000GB / 10Gbps | $79.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| G16C32G（AN4） | 16核 / 32G / 640G | 320000GB / 10Gbps | $199.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V2C2G（AN5） | 2核 / 2G / 40G | 5000GB / 10Gbps | $14.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V2C4G（AN5） | 2核 / 4G / 80G | 10000GB / 10Gbps | $23.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V4C4G（AN5） | 4核 / 4G / 120G | 20000GB / 10Gbps | $36.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V4C8G（AN5） | 4核 / 8G / 160G | 40000GB / 10Gbps | $52.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V8C16G（AN5） | 8核 / 16G / 240G | 80000GB / 10Gbps | $119.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| V12C24G（AN5） | 12核 / 24G / 320G | 160000GB / 10Gbps | $199.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

## 香港与东京全套餐价格

香港的卖点是延迟，20–50ms，比洛杉矶快一个数量级。代价是同配置价格高、流量少。

### HKG Premium（三网 CN2 GIA，全部 1Gbps）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1G / 20G | 500GB | $39.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2G / 40G | 1000GB | $79.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2G / 60G | 1500GB | $119.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4G / 80G | 2000GB | $159.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8G / 160G | 2500GB | $179.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16G / 320G | 3000GB | $239.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24G / 640G | 6000GB | $499.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### HKG Eyeball（三网 CMI）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINYv2 | 1核 / 1G / 20G | 1000GB / 1Gbps | $29.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTERv2 | 1核 / 2G / 40G | 2000GB / 2Gbps | $59.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINIv2 | 2核 / 2G / 60G | 3000GB / 2Gbps | $89.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICROv2 | 4核 / 4G / 80G | 4000GB / 4Gbps | $129.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUMv2 | 4核 / 8G / 160G | 6000GB / 4Gbps | $199.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGEv2 | 8核 / 16G / 320G | 12000GB / 4Gbps | $389.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANTv2 | 8核 / 24G / 640G | 24000GB / 4Gbps | $789.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### HKG Tier 1

| 套餐 | 配置（CPU/内存/SSD） | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| WEE | 1核 / 1G / 20G | 1000GB | $36.90/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| TINY | 1核 / 1G / 20G | 2000GB | $6.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2G / 40G | 4000GB | $12.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2G / 60G | 8000GB | $21.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4G / 80G | 16000GB | $32.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8G / 160G | 32000GB | $49.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16G / 320G | 64000GB | $99.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24G / 640G | 128000GB | $199.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### TYO Premium（三网 CN2 GIA，全部 1Gbps）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1G / 20G | 500GB | $21.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2G / 40G | 1000GB | $39.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2G / 60G | 2000GB | $79.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4G / 80G | 4000GB | $159.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8G / 160G | 5000GB | $259.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16G / 320G | 8000GB | $429.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24G / 640G | 15000GB | $799.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### TYO Eyeball（三网 CMI）

| 套餐 | 配置（CPU/内存/SSD） | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1核 / 1G / 20G | 1000GB / 1Gbps | $25.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2G / 40G | 2000GB / 2Gbps | $55.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2G / 60G | 3000GB / 2Gbps | $85.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4G / 80G | 4000GB / 4Gbps | $119.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8G / 160G | 6000GB / 4Gbps | $179.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16G / 320G | 12000GB / 4Gbps | $369.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24G / 640G | 24000GB / 4Gbps | $749.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

### TYO Tier 1

| 套餐 | 配置（CPU/内存/SSD） | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| WEE | 1核 / 1G / 20G | 1000GB | $36.90/年 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| TINY | 1核 / 1G / 20G | 2000GB | $6.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| STARTER | 1核 / 2G / 40G | 4000GB | $12.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MINI | 2核 / 2G / 60G | 8000GB | $21.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MICRO | 4核 / 4G / 80G | 16000GB | $32.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| MEDIUM | 4核 / 8G / 160G | 32000GB | $49.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| LARGE | 8核 / 16G / 320G | 64000GB | $99.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |
| GIANT | 8核 / 24G / 640G | 128000GB | $199.90/月 | [ 选择](https://www.dmit.io/aff.php?aff=9081) |

## 同价不同流量：Pro 和 EB 的分水岭

洛杉矶 Premium 和 Eyeball 的基础档价格完全一样，差在流量给多少。

| 档位 | Pro 流量 | EB 流量 | 倍数 |
| --- | --- | --- | --- |
| TINY（$88.88/年） | 1000GB | 1500GB | 1.5× |
| Pocket（$159.98/年） | 1500GB | 3000GB | 2.0× |
| STARTER（$29.90/月） | 3000GB | 5000GB | 1.67× |
| MINI（$58.88/月） | 5000GB | 10000GB | 2.0× |
| MEDIUM（$168.88/月） | 15000GB | 30000GB | 2.0× |

同样 $29.90 一个月，Pro 给 3000GB，EB 给 5000GB。这笔账要看你缺的是线路还是流量。

Pro 走三网 CN2 GIA，电信、联通、移动三家在晚高峰都能保持稳定。EB 是电信联通走 AS9929、移动走 CMIN2，移动用户的体感其实和 Pro 差不了太多，电信联通高峰期会差一口气。

判断规则很直接：网站有付费用户、掉线就有人找你，买 Pro；个人博客、图床、下载站这类流量吃紧但偶尔慢一点能忍的，买 EB。以移动宽带为主的用户，EB 的 CMIN2 回程已经够用。

👉 [用年付方案开通洛杉矶 Eyeball，同价多 50% 流量](https://www.dmit.io/aff.php?aff=9081)

## AN4 还是 AN5：35% 的差价花得值不值

同一个 Pro TINY，AN4 是 $88.88/年，AN5 是 $119.99/年，差 $31.11，约 35%。月付档也一样，STARTER 从 $29.90 涨到 $38.90。

AN5 是 EPYC 9005 平台，第三方测评说单核跑分比 AN4 的 EPYC 9004 提升约 50%，多核更明显。这个数字没有官方页面佐证，当参考就好。

实际判断：轻量建站、反向代理、跑几个 Docker 服务，AN4 完全够，多花的 35% 换不来可感知的差别。真正该上 AN5 的是计算密集型任务：编译、转码、跑数据处理脚本、CPU 长时间打满的活。这种场景下单核性能的差距会直接变成任务完成时间。

👉 [对比 AN4 与 AN5 各档价格后下单](https://www.dmit.io/aff.php?aff=9081)

## 香港和东京值不值这个价

香港 Premium TINY 是 $39.90/月，折年约 $478.8，配置只有 1核/1G/20G、500GB 流量。同样的钱在洛杉矶能买到 Pro MEDIUM（$168.88/月不算，退一步说 STARTER $29.90/月也只是它的四分之三）。

买香港买的是延迟。20–50ms 和 150–180ms 的差别，对实时交互类应用是质变：远程桌面、实时协作、游戏加速、需要频繁请求的 API。纯展示型网站用不上这个差距，CDN 一层就抹平了。

东京 Pro TINY 是 $21.90/月，500GB 流量，比香港便宜近一半。适合需要日本原生 IP、面向亚太用户的场景。

**香港 T1 这个坑要单独说。** 很多人看到香港机房就默认"国内访问快"，但 T1 系列没有大陆方向优化，国内访问这个节点的延迟可能比洛杉矶 Premium 还高。香港 T1 WEE 年付 $36.90 确实便宜，流量也给到 1000GB，但它是给海外业务和落地机用的，不是给国内用户访问的。买之前想清楚。

## 限制、退款与售后

这些条款只写在官方 FAQ 和条款页里，多数对比文不提，但直接影响你要不要下单。

**退款**：购买 3 天内且流量使用不超过 30GB，可申请全额退款，扣除支付网关手续费。30 天内可按剩余价值比例退款。退到账户余额免手续费，原路退回可能被扣费。三种情况不退：续费订单、同一系列退款已达 3 次、IP 被封。

3 天窗口足够跑一遍 ping 和 MTR 验线路。洛杉矶 Pro 系列的测试 IP 是 154.17.12.22，下单前就能自己测。

**换 IP**：每 15 天可免费换一次，仅限 IP 被墙的情况。其他情况 $5 一次。2026 年 1 月起支持自助换 IP，不用等工单。

**机房不可迁移**：买了香港想换洛杉矶，只能重新下单，数据自己迁。选机房这一步没有后悔药。

**默认密钥登录**：DMIT 不开密码直连，开通后要在控制台上传 SSH 公钥才能连。第一次用的人容易卡在这一步，先准备好密钥对。

**缺货**：因为不超售，热门套餐（尤其香港、东京的 Premium）经常售罄，补货没有固定时间表，官方 Telegram 会发通知。看中了别拖。

**支付**：支付宝、微信支付、PayPal、信用卡、加密货币都支持，国内用户直接支付宝。

关于流量跑超之后会怎样，第三方资料的说法是限速不断网，Pro 和 EB 超额后限速到个位数 Mbps。这条只有单一来源，别把它当"无限流量"用。

👉 [确认退款与换 IP 规则后从官网入口下单](https://www.dmit.io/aff.php?aff=9081)

## 优惠码：两个码，条件都很窄

目前能查到的两个码都限定洛杉矶、限定非月付订单，而且是循环折扣（recurring），不是只第一期便宜：

- `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF`：洛杉矶 Eyeball 系列，季付及以上，循环 8 折
- `PVM-LAX-LAUNCH-NON-MONTHLY-RECURRING-20OFF`：洛杉矶 Premium 系列，非月付订单

填写位置在订单页的 "Apply Promo Code" 输入框，输完点验证。优惠码随时可能失效，付款前必须在购物车确认折扣真的生效了，别等到扣款后才发现没打上。

除这两个之外，目前没有普适全线的通用码。看到"全场 8 折"之类的说法，基本是把这两个限定码扩大解释了。

关于续费：资料里没有任何"首期特价、续费涨价"的证据，这两个码本身就是循环折扣。续费价是否变动以官网账单为准，别信臆测的涨幅。

## 按场景选：一张表定下来

| 你的情况 | 选这个 | 价格 |
| --- | --- | --- |
| 国内用户访问的博客、小型站点 | 洛杉矶 Pro AN4 TINY | $88.88/年 |
| 流量大、线路可退半档 | 洛杉矶 EB AN4 TINY | $88.88/年 |
| CPU 长时间打满（编译、转码、数据处理） | 洛杉矶 Pro AN5 STARTER | $38.90/月 |
| 海外业务、大流量落地、跑脚本 | LAX T1 V2C2G 或 WEE | $14.90/月 或 $36.90/年 |
| 实时交互，延迟必须低 | 香港 Pro TINY | $39.90/月 |
| 需要日本 IP / 亚太节点 | 东京 Pro TINY | $21.90/月 |
| 只是想有台机器练手 | 香港或东京 T1 WEE | $36.90/年 |

顺带说一句竞品。第三方测评提到 DMIT 是搬瓦工的上游之一，两家都做 CN2 GIA。区别在于 DMIT 走自有网络、不超售，线路更纯粹；搬瓦工的 CN2 GIA 套餐流量通常给得更多，价格相对亲民。这个说法只来自单一第三方文章，没有官方确认，当参考。追求绝对低价和流量额度，可以自己去比；追求晚高峰稳定和资源真实分配，DMIT 这一档值这个钱。

## 下单前最后确认三件事

**一、库存。** 热门款经常没货，尤其是香港和东京的 Pro 系列。填完订单发现售罄很浪费时间，先看库存再决定。

**二、优惠码是否生效。** 在购物车页面看到折后总价变了再付款，别凭"我填了"就以为打上了。

**三、机房选对。** 不能迁移。国内用户访问就选洛杉矶 Pro 或 EB，别为了"香港离得近"去买香港 T1。

只需要一台稳定的、国内访问不掉链子的机器，洛杉矶 Pro AN4 TINY $88.88/年，这一台覆盖 80% 的人。流量吃紧就换 EB，同价多一半。要低延迟再加钱上香港，要便宜就走 T1。

👉 [前往 DMIT 核对实时价格与库存](https://www.dmit.io/aff.php?aff=9081)
