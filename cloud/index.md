# 腾讯云行情GitHub中转统一入口

转接页面生成时间：2026-11-17T15:09:40.699018+08:00（不是行情采集时间）
手机普通ChatGPT优先读取 [一次读取入口](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/START_HERE.md)。
先核对下表各自交易日。午间、收盘和研究时点独立；缺失不补零。
当前最新有效行情：2026-11-17 close；采集观察时间：2026-11-17T15:05:01.286756+08:00；运行号：20261117T150501286756+0800；状态：partial。


| 内容 | 交易日 | 观察时点 | 状态 |
|---|---|---|---|
| [close](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-17/20261117T150501286756%2B0800/latest.md) | 2026-11-17 | 2026-11-17T15:05:01.286756+08:00 | partial |
| [midday](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-17/20261117T120501233850%2B0800-e34279e428/latest.md) | 2026-11-17 | 2026-11-17T12:07:11.806249+08:00 | partial |
| [lifecycle](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-16/20261116T212002-eba72beb151c4a3ebb6b687c45531ac3/latest.md) | 2026-11-16 | 2026-11-16T21:20:47.015249+08:00 | partial |
| [research-v2](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-16/20261116T212049-80150f2c0e7a4077b2ea8eda20e2218d/latest.md) | 2026-11-16 | 2026-11-16T21:20:49+08:00 | partial_research |

## 按需读取

- 先读 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)，再读对应 summary_url。
- 单股链接模板：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/close/stocks/CODE.json；午间：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/midday/stocks/CODE.json。CODE为六位代码。
- 全量 market_quotes.json 很大；问个股时用单股文件，避免工具截断。
- index.json 各流的 archive_url 指向不可变归档，可固定该目录读取，避免跨轮混合。
- 仅发布规范化行情与研究字段；不含私有代码、原始网页、账户或私人证据。


## 历史日线回补查询

[2026-10-26至2026-11-13：历史日线、收益回撤、行业题材及逐日完整度](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/START_HERE.md)。这是固定历史回补批次，状态partial，不是最新实时行情；历史查询请进入该入口。
