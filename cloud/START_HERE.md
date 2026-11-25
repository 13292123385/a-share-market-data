# 腾讯云行情：GitHub中转手机读取入口

本页由腾讯云采集结果自动生成，通过GitHub中转供联网读取。
页面生成时间：2026-11-25T11:36:15.020646+08:00。这不是行情采集时间。

当前最新有效行情：**2026-11-25 午间**；采集观察时间：2026-11-25T11:36:14.915785+08:00。
运行号：20261125T113501682162+0800-7cd0340d40；完整性状态：partial。
以下摘要与单股链接属于这一轮归档；题材研究另有自己的日期和运行号。

## 一次读取摘要

```json
{
  "schema_version": 1,
  "access_path": "Tencent cloud collection -> GitHub relay -> ChatGPT",
  "page_generated_at": "2026-11-25T11:36:15.020646+08:00",
  "latest_market": {
    "trade_date": "2026-11-25",
    "run_id": "20261125T113501682162+0800-7cd0340d40",
    "session": "midday",
    "as_of": "2026-11-25T11:36:14.915785+08:00",
    "status": "partial",
    "collection_status": "partial",
    "source_freshness": "逐股行情时间戳未全部独立核验；时间为采集观察时点",
    "all_market_verified": false,
    "market_quote_rows": 5580,
    "indices_available": 0,
    "expected_indices": 4,
    "market_scope": "沪深北A股全市场快照；以官方代码名单核对覆盖",
    "pool_scope": "上游股票池返回范围，未额外套用主板非ST研究筛选；完整性仍待核验",
    "stream": "midday",
    "code_coverage": {
      "status": "differences_found",
      "expected_count": 5581,
      "observed_count": 5580,
      "all_market_verified": false,
      "missing_codes": [
        "689009"
      ],
      "missing_codes_count": 1,
      "missing_codes_summary_truncated": false
    },
    "missing_data": [
      "全市场批量快照及股票池缺少逐行独立行情时间戳，少量已验证补采不能代表全部行情时效",
      "上证指数带日期和上午时间戳的指数报价",
      "深证成指带日期和上午时间戳的指数报价",
      "创业板指带日期和上午时间戳的指数报价",
      "中证2000带日期和上午时间戳的指数报价",
      "全市场代码覆盖未与完整官方名单匹配"
    ],
    "missing_data_count": 6,
    "missing_data_summary_truncated": false,
    "market_estimates": {
      "records": 5580,
      "up": 2823,
      "down": 2626,
      "flat": 131,
      "known_turnover_yuan": 768759007062.0,
      "timestamp_verified_rows": 0,
      "timestamp_unavailable_rows": 5580
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/",
    "stock_url_template": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/stocks/CODE.json"
  },
  "example_stock": {
    "code": "600000",
    "availability": "available",
    "trade_date": "2026-11-25",
    "session": "midday",
    "run_id": "20261125T113501682162+0800-7cd0340d40",
    "quote": {
      "code": "600000",
      "name": "浦发银行",
      "last": 10.6,
      "open": 10.74,
      "high_so_far": 10.74,
      "low_so_far": 10.52,
      "change_pct": -0.842,
      "amount_yuan_so_far": 318932808.0,
      "provider_timestamp": null,
      "date_verification": "provider_timestamp_unavailable",
      "midday_timestamp_verified": false
    },
    "url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/stocks/600000.json"
  },
  "themes": {
    "trade_date": "2026-11-24",
    "run_id": "20261124T212106-416bead9189f41f993ecbfeeba72d227",
    "status": "partial_research",
    "ranking_scope": "dated_partial_active_associations",
    "observed_at": "2026-11-24T21:21:06+08:00",
    "strength_definition": "0–100的样本观察活跃度，不是已独立核验的正式全市场题材强度。",
    "formal_full_market_strength_available": false,
    "missing_data": [
      "完整历史题材成分未知，不能用当前成员倒填；正式全市场强度与相对市场收益为空",
      "40日全主板轻量行情仅有17/40日已存快照，快照字段未全部独立核验",
      "题材上涨广度、全成分成交份额及全成分炸板数缺少完整分母",
      "第三方历史复盘可能修订，不是当时已知快照，不能用于无偏信号回测",
      "真实业务和新催化未独立验证，C席位可空缺；带动关系待确认",
      "分钟行情、盘口及次日可执行入场缺失，成交与真实策略收益未知"
    ],
    "missing_data_count": 7,
    "missing_data_summary_truncated": true,
    "seats": {
      "A": {
        "theme_id": "机器人",
        "theme_name": "机器人",
        "as_of": "2026-11-24",
        "rank": 1,
        "activity_score": 98.619327,
        "composite_score": 98.619327,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "B": {
        "theme_id": "光通信",
        "theme_name": "光通信",
        "as_of": "2026-11-24",
        "rank": 2,
        "activity_score": 78.499625,
        "composite_score": 78.499625,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "C": null
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-24/20261124T212106-416bead9189f41f993ecbfeeba72d227/"
  }
}
```

## 按问题读取完整原文

- [本轮完整行情摘要](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/latest.json)；[行情说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/latest.md)。
- 其他股票使用六位代码替换 CODE：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/stocks/CODE.json
- [代码覆盖与缺失股票](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/market_coverage.json)；[指数](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/indices.json)。
- [涨停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/limit_up.json)；[炸板池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/broken.json)；[跌停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/limit_down.json)。
- [首板候选](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/first_board_candidates.json)；[后续跟踪](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/followup.json)；[晋级观察](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/promotion.json)。
- 全市场逐股表：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-25/20261125T113501682162%2B0800-7cd0340d40/market_quotes.json。该文件较大，问个股优先读取单股文件。
- [题材评分与核心股：2026-11-24](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-24/20261124T212106-416bead9189f41f993ecbfeeba72d227/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-24/20261124T212106-416bead9189f41f993ecbfeeba72d227/latest.md)。
- [长期跟踪与题材关联：2026-11-24](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-24/20261124T212001-af6abfb7419342b8b2a789b91dbf939b/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-24/20261124T212001-af6abfb7419342b8b2a789b91dbf939b/latest.md)。

## 读取规则

- 最新行情只从有效午间/收盘归档中按交易日选择；同日收盘优先。午间不代表全天收盘。
- 回答时保留trade_date、session、as_of、run_id、status和missing_data；page_generated_at不能充当采集或逐股报价时间。
- partial/partial_research表示有缺失；代码覆盖率不是价格准确率。null与未知不补零，未独立核验的日期不猜测补齐。
- 摘要列表若标有summary_truncated=true，完整项仍在上述本轮原文链接中。
- 如果联网失败、返回旧版本或内容截断，明确说明实际读到的日期或失败；不得声称已取得更新数据。
- 本页是GitHub中转，读取它不等于直接查询腾讯云；题材评分不能冒充正式全市场强度或真实策略收益。
- 其他独立数据流和固定入口见 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)。


## 历史日线回补查询

[2026-10-26至2026-11-13：历史日线、收益回撤、行业题材及逐日完整度](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/START_HERE.md)。这是固定历史回补批次，状态partial，不是最新实时行情；历史查询请进入该入口。
