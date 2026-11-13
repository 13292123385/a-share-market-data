# 腾讯云行情GitHub中转统一入口

转接页面生成时间：2026-11-13T20:43:05.977678+08:00（不是行情采集时间）
手机普通ChatGPT优先读取 [一次读取入口](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/START_HERE.md)。
先核对下表各自交易日。午间、收盘和研究时点独立；缺失不补零。
当前最新有效行情：2026-11-13 close；采集观察时间：2026-11-13T15:05:01.905143+08:00；运行号：20261113T152001481189+0800；状态：partial。


| 内容 | 交易日 | 观察时点 | 状态 |
|---|---|---|---|
| [close](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-13/20261113T152001481189%2B0800/latest.md) | 2026-11-13 | 2026-11-13T15:05:01.905143+08:00 | partial |
| [midday](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/latest.md) | 2026-11-13 | 2026-11-13T12:06:11.805146+08:00 | partial |
| [lifecycle](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-13/20261113T182002-56c5a970e839481e8f792f869a509139/latest.md) | 2026-11-13 | 2026-11-13T18:21:50.916102+08:00 | partial |
| [research-v2](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-13/20261113T182153-f258be4536c34249a43cb056597472f5/latest.md) | 2026-11-13 | 2026-11-13T18:21:53+08:00 | partial_research |

## 按需读取

- 先读 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)，再读对应 summary_url。
- 单股链接模板：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/close/stocks/CODE.json；午间：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/midday/stocks/CODE.json。CODE为六位代码。
- 全量 market_quotes.json 很大；问个股时用单股文件，避免工具截断。
- index.json 各流的 archive_url 指向不可变归档，可固定该目录读取，避免跨轮混合。
- 仅发布规范化行情与研究字段；不含私有代码、原始网页、账户或私人证据。
