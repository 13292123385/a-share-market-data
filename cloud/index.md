# 腾讯云行情GitHub中转统一入口

转接页面生成时间：2026-11-20T12:07:22.410642+08:00（不是行情采集时间）
手机普通ChatGPT优先读取 [一次读取入口](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/START_HERE.md)。
先核对下表各自交易日。午间、收盘和研究时点独立；缺失不补零。
当前最新有效行情：2026-11-20 midday；采集观察时间：2026-11-20T12:07:22.273760+08:00；运行号：20261120T120501686057+0800-82f4749d9b；状态：partial。


| 内容 | 交易日 | 观察时点 | 状态 |
|---|---|---|---|
| [close](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-19/20261119T150501205909%2B0800/latest.md) | 2026-11-19 | 2026-11-19T15:05:01.205909+08:00 | partial |
| [midday](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-20/20261120T120501686057%2B0800-82f4749d9b/latest.md) | 2026-11-20 | 2026-11-20T12:07:22.273760+08:00 | partial |
| [lifecycle](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-19/20261119T212001-ce5ce0ec90a448e29c05ba718cb3706a/latest.md) | 2026-11-19 | 2026-11-19T21:20:46.538800+08:00 | partial |
| [research-v2](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-19/20261119T212052-2adf3a35ae514fd9b2685d3a37552f11/latest.md) | 2026-11-19 | 2026-11-19T21:20:52+08:00 | partial_research |

## 按需读取

- 先读 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)，再读对应 summary_url。
- 单股链接模板：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/close/stocks/CODE.json；午间：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/midday/stocks/CODE.json。CODE为六位代码。
- 全量 market_quotes.json 很大；问个股时用单股文件，避免工具截断。
- index.json 各流的 archive_url 指向不可变归档，可固定该目录读取，避免跨轮混合。
- 仅发布规范化行情与研究字段；不含私有代码、原始网页、账户或私人证据。


## 历史日线回补查询

[2026-10-26至2026-11-13：历史日线、收益回撤、行业题材及逐日完整度](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/START_HERE.md)。这是固定历史回补批次，状态partial，不是最新实时行情；历史查询请进入该入口。
