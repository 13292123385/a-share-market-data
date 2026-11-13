# 腾讯云A股历史日线回补：手机GPT读取入口

范围：2026-10-26至2026-11-13，共15个交易日。批次：daily-20261026-20261113-v1。
GitHub中转导出时间：2026-11-13T23:12:20.955704+08:00；这是历史快照导出时间，不是行情交易时间。
来源：腾讯云PostgreSQL已校验回补数据；本目录为固定历史批次，不代表最新实时行情。

状态：partial。有效股票日线83572条，候选股票—交易日83686条；114条没有日线，其中100条有停牌表支持，14条待核验；缺失保留null。
分母为已保存官方名册并集按上市日期过滤的候选数，历史退市名册完整性未全部核实。

## 按问题读取

- 个股：使用六位代码替换CODE：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/stocks/CODE.json。文件包含本批次全部可用日期的OHLC、量额、换手率与5/10日及区间收益、回撤和相对指数强度。
- [逐日完整度和缺失代码](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/reports.json)；[按日期查询索引及分页](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/index.json)。
- [行业和概念题材名称目录](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/catalog.md)：按名称查找后读取对应历史原文；不要猜链接中的标识。
- 指定日期股票第一页：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/dates/DATE/stocks-000.json；DATE为YYYY-MM-DD。每页50条，必须沿next_url翻页，不能把第一页当全市场。
- 指定日期行业/概念/样本：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/dates/DATE/themes-KIND-000.json；KIND见机器索引，按next_url翻页。
- [计算口径与局限](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/methodology.json)；[沪深300历史](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/indices/sh000300.json)。

## 必须保留的口径

- 不复权OHLC用于原始行情；收益采用回补时抓取的前复权序列，不是当时已知复权价或真实策略收益。
- pct_change是计算的不复权相邻交易日收盘收益，除权日可能与交易所涨跌幅不同。provider_pct_change为空；adjusted_daily_return_pct是前复权日收益。
- 5日/10日收益分别需要6个/11个交易日收盘。区间收益基于10月23日收盘；最大回撤为包含基准日的收盘回撤，负值表示下跌。缺必要日期则null，不跨缺失跳算。
- 相对基准为沪深300价格指数：excess_return_pp是百分点差，relative_return_pct是增长倍数之比减一。
- historical_non_st_verified=false。research_filter_proxy仅按沪深主板及当前归档名称筛选，不能冒充逐日历史非ST池。
- 来源历史指数、第三方带日期活跃样本、当前归属重建分开保存；重建领涨者不是原有锁定龙头结论。正式全成分强度、缺失值不补零。
- 原有首板、连板、炸板及题材评分归档未覆盖。读取失败或截断须说明，不用聊天记忆补齐。

|交易日|有效日线/候选数|缺日线|行业指数|概念指数|
|---|---:|---:|---:|---:|
|2026-10-26|5570/5577|7|90|375|
|2026-10-27|5570/5577|7|90|375|
|2026-10-28|5570/5577|7|90|375|
|2026-10-29|5570/5578|8|90|375|
|2026-10-30|5571/5578|7|90|375|
|2026-11-02|5571/5578|7|90|375|
|2026-11-03|5570/5579|9|90|375|
|2026-11-04|5572/5579|7|90|375|
|2026-11-05|5571/5579|8|90|375|
|2026-11-06|5573/5580|7|90|375|
|2026-11-09|5573/5580|7|90|375|
|2026-11-10|5573/5581|8|90|375|
|2026-11-11|5574/5581|7|90|375|
|2026-11-12|5573/5581|8|90|375|
|2026-11-13|5571/5581|10|90|369|
