# 云端行情统一入口

入口更新时间：2026-11-12T23:57:52.856993+08:00
先核对下表各自交易日。午间、收盘和研究时点独立；缺失不补零。

| 内容 | 交易日 | 观察时点 | 状态 |
|---|---|---|---|
| [close](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/close/latest.md) | 2026-11-12 | 2026-11-12T23:47:31.777886+08:00 | partial |
| midday | 尚无有效归档 | 未知 | waiting_for_valid_midday |
| [lifecycle](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/lifecycle/latest.md) | 2026-11-12 | 2026-11-12T21:19:22.313926+08:00 | partial |
| [research-v2](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/research-v2/latest.md) | 2026-11-12 | 2026-11-12T21:19:24+08:00 | partial_research |

## 按需读取

- 先读 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)，再读对应 summary_url。
- 单股链接模板：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/close/stocks/CODE.json；午间：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/midday/stocks/CODE.json。CODE为六位代码。
- 全量 market_quotes.json 很大；问个股时用单股文件，避免工具截断。
- index.json 各流的 archive_url 指向不可变归档，可固定该目录读取，避免跨轮混合。
- 仅发布规范化行情与研究字段；不含私有代码、原始网页、账户或私人证据。
