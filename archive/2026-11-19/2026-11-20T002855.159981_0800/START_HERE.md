# 手机 GPT 读取入口

每日午盘、下午收盘的独立完整快照，先读取[market/index.md](market/index.md)，分别核对各时段的交易日、状态和报价时间。

日报读取同目录latest.md和latest.json，核对trade_date及collection_status。日报的全市场逐股快照读取market_snapshot/manifest.json并依次读取列出的全部分块，或下载完整market_snapshot.json；该快照交易日以日报为准。核对记录数，不把摘要或网页截断当作全量。首板、涨停和跟踪另见first_board.json/limit_up.json/followup.json。日期不符则说明过期，缺失不补零，不把观察统计当可成交收益。

Gist只存摘要，全市场文件以公开数据仓库为准。若聊天没有联网读取工具，请下载JSON上传。
