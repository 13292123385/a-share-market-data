# 手机GPT历史日线查询入口

回补批次：daily-20261026-20261113-v1。范围：2026-10-26至2026-11-13。状态：partial。
阅读页生成时间：2026-11-13T23:23:08.427041+08:00；不是交易或行情采集时间。此页为腾讯云数据库历史快照经GitHub中转。
[同批次原始JSON](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/START_HERE.md)；[计算口径](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/methodology.md)。null表示缺失，不补零。

本入口提供易读的表格页面；个股及行业查询优先读取下列.md页面。原始JSON保留作精度与字段核对。
有效股票日线83572条；候选股票—交易日83686条，114条无日线。历史全市场名册及历史ST身份未全部核实。

- 个股历史（六位代码替换CODE）：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/stocks/CODE.md
- [行业和题材名称目录](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/catalog.md)：查找名称，再打开对应历史链接。
- [逐日完整度及缺失代码](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/reports.md)；[计算口径与局限](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/methodology.md)。
- [按日期查询索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/index.json)；日期股票页：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/dates/DATE/stocks-000.md，DATE为YYYY-MM-DD；必须沿下一页链接翻页。
- [沪深300基准历史](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/indices/sh000300.md)。

来源：腾讯云PostgreSQL历史回补快照 → GitHub → ChatGPT；不是直接云端查询，不是实时行情。
收益采用回补时前复权价；区间基准10月23日。5/10日收益需6/11个交易日收盘；最大回撤为负值的收盘回撤。缺必要日期则null，不跨缺失跳算。
pct_change为计算的不复权收盘日收益，provider_pct_change为null；历史ST未核实，主板非ST筛选只是近似。
来源历史指数与事后重建样本分开；重建领涨者不是当时锁定龙头，完整题材强度缺失不补零。原有研究归档未覆盖。
请报告实际读取的批次、日期及缺失状态，未取得原文时不要根据聊天记忆补齐。

