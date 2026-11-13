# 腾讯云行情：GitHub中转手机读取入口

本页由腾讯云采集结果自动生成，通过GitHub中转供联网读取。
页面生成时间：2026-11-13T13:54:45.900238+08:00。这不是行情采集时间。

当前最新有效行情：**2026-11-13 午间**；采集观察时间：2026-11-13T12:06:11.805146+08:00。
运行号：20261113T120501405040+0800-936ad4b38f；完整性状态：partial。
以下摘要与单股链接属于这一轮归档；题材研究另有自己的日期和运行号。

## 一次读取摘要

```json
{
  "schema_version": 1,
  "access_path": "Tencent cloud collection -> GitHub relay -> ChatGPT",
  "page_generated_at": "2026-11-13T13:54:45.900238+08:00",
  "latest_market": {
    "trade_date": "2026-11-13",
    "run_id": "20261113T120501405040+0800-936ad4b38f",
    "session": "midday",
    "as_of": "2026-11-13T12:06:11.805146+08:00",
    "status": "partial",
    "collection_status": "partial",
    "source_freshness": "逐股行情时间戳未全部独立核验；时间为采集观察时点",
    "all_market_verified": false,
    "market_quote_rows": 5578,
    "indices_available": 0,
    "expected_indices": 4,
    "market_scope": "沪深北A股全市场快照；以官方代码名单核对覆盖",
    "pool_scope": "上游股票池返回范围，未额外套用主板非ST研究筛选；完整性仍待核验",
    "stream": "midday",
    "code_coverage": {
      "status": "differences_found",
      "expected_count": 5579,
      "observed_count": 5578,
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
      "records": 5578,
      "up": 2341,
      "down": 2996,
      "flat": 241,
      "known_turnover_yuan": 986072386275.0,
      "timestamp_verified_rows": 0,
      "timestamp_unavailable_rows": 5578
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/",
    "stock_url_template": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/stocks/CODE.json"
  },
  "example_stock": {
    "code": "600000",
    "availability": "available",
    "trade_date": "2026-11-13",
    "session": "midday",
    "run_id": "20261113T120501405040+0800-936ad4b38f",
    "quote": {
      "code": "600000",
      "name": "浦发银行",
      "last": 10.38,
      "open": 10.19,
      "high_so_far": 10.39,
      "low_so_far": 10.12,
      "change_pct": 1.665,
      "amount_yuan_so_far": 421986515.0,
      "provider_timestamp": null,
      "date_verification": "provider_timestamp_unavailable",
      "midday_timestamp_verified": false
    },
    "url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/stocks/600000.json"
  },
  "themes": {
    "trade_date": "2026-11-12",
    "run_id": "20261112T211924-cec0579f7798448298d3ad329db7d93f",
    "status": "partial_research",
    "ranking_scope": "dated_partial_active_associations",
    "observed_at": "2026-11-12T21:19:24+08:00",
    "strength_definition": "0–100的样本观察活跃度，不是已独立核验的正式全市场题材强度。",
    "formal_full_market_strength_available": false,
    "missing_data": [
      "完整历史题材成分未知，不能用当前成员倒填；正式全市场强度与相对市场收益为空",
      "40日全主板轻量行情仅有9/40日已存快照，快照字段未全部独立核验",
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
        "as_of": "2026-11-12",
        "rank": 1,
        "activity_score": 99.820742,
        "composite_score": 99.820742,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "B": {
        "theme_id": "影视内容",
        "theme_name": "影视内容",
        "as_of": "2026-11-12",
        "rank": 3,
        "activity_score": 80.626546,
        "composite_score": 80.626546,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "C": null
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-12/20261112T211924-cec0579f7798448298d3ad329db7d93f/"
  }
}
```

## 按问题读取完整原文

- [本轮完整行情摘要](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/latest.json)；[行情说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/latest.md)。
- 其他股票使用六位代码替换 CODE：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/stocks/CODE.json
- [代码覆盖与缺失股票](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/market_coverage.json)；[指数](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/indices.json)。
- [涨停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/limit_up.json)；[炸板池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/broken.json)；[跌停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/limit_down.json)。
- [首板候选](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/first_board_candidates.json)；[后续跟踪](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/followup.json)；[晋级观察](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/promotion.json)。
- 全市场逐股表：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/midday/2026-11-13/20261113T120501405040%2B0800-936ad4b38f/market_quotes.json。该文件较大，问个股优先读取单股文件。
- [题材评分与核心股：2026-11-12](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-12/20261112T211924-cec0579f7798448298d3ad329db7d93f/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-12/20261112T211924-cec0579f7798448298d3ad329db7d93f/latest.md)。
- [长期跟踪与题材关联：2026-11-12](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-12/20261112T211736-cb487b9135ab4bb7a9e130f2683a8687/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-12/20261112T211736-cb487b9135ab4bb7a9e130f2683a8687/latest.md)。

## 读取规则

- 最新行情只从有效午间/收盘归档中按交易日选择；同日收盘优先。午间不代表全天收盘。
- 回答时保留trade_date、session、as_of、run_id、status和missing_data；page_generated_at不能充当采集或逐股报价时间。
- partial/partial_research表示有缺失；代码覆盖率不是价格准确率。null与未知不补零，未独立核验的日期不猜测补齐。
- 摘要列表若标有summary_truncated=true，完整项仍在上述本轮原文链接中。
- 如果联网失败、返回旧版本或内容截断，明确说明实际读到的日期或失败；不得声称已取得更新数据。
- 本页是GitHub中转，读取它不等于直接查询腾讯云；题材评分不能冒充正式全市场强度或真实策略收益。
- 其他独立数据流和固定入口见 [机器索引](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json) 与 [状态](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/status.json)。
