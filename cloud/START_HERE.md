# 腾讯云行情：GitHub中转手机读取入口

本页由腾讯云采集结果自动生成，通过GitHub中转供联网读取。
页面生成时间：2026-11-24T15:11:36.811608+08:00。这不是行情采集时间。

当前最新有效行情：**2026-11-24 收盘**；采集观察时间：2026-11-24T15:05:02.077564+08:00。
运行号：20261124T150502077564+0800；完整性状态：partial。
以下摘要与单股链接属于这一轮归档；题材研究另有自己的日期和运行号。

## 一次读取摘要

```json
{
  "schema_version": 1,
  "access_path": "Tencent cloud collection -> GitHub relay -> ChatGPT",
  "page_generated_at": "2026-11-24T15:11:36.811608+08:00",
  "latest_market": {
    "trade_date": "2026-11-24",
    "run_id": "20261124T150502077564+0800",
    "session": "close",
    "fetched_at": "2026-11-24T15:05:02.077564+08:00",
    "as_of": "2026-11-24T15:05:02.077564+08:00",
    "status": "partial",
    "collection_status": "partial",
    "source_freshness": "逐股行情时间戳未全部独立核验；时间为采集观察时点",
    "all_market_verified": false,
    "market_quote_rows": 5581,
    "indices_available": 2,
    "expected_indices": 4,
    "market_scope": "沪深北A股全市场快照；以官方代码名单核对覆盖",
    "pool_scope": "沪深主板非ST研究池；排除科创、创业和北交所，不代表全A股涨停总数",
    "stream": "close",
    "code_coverage": {
      "status": "code_coverage_matched",
      "expected_count": 5581,
      "observed_count": 5581,
      "all_market_verified": false,
      "missing_codes": [],
      "missing_codes_count": 0,
      "missing_codes_summary_truncated": false
    },
    "missing_data": [
      "深圳A股成交额交叉核验未通过或不可比较",
      "首板后续跟踪存在历史名单或价格缺失，详见followup",
      "创业板指指定日期收盘值",
      "中证2000指定日期收盘值"
    ],
    "missing_data_count": 4,
    "missing_data_summary_truncated": false,
    "market_estimates": {
      "records": 5581,
      "up": 1952,
      "down": 3498,
      "flat": 131,
      "turnover_yuan": 1667800445242.0,
      "source": "新浪",
      "scope": "沪深北候选范围（以官方名单核验结果为准）"
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/",
    "stock_url_template": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/stocks/CODE.json"
  },
  "example_stock": {
    "code": "600000",
    "availability": "available",
    "trade_date": "2026-11-24",
    "session": "close",
    "run_id": "20261124T150502077564+0800",
    "quote": {
      "code": "600000",
      "name": "浦发银行",
      "last": 10.69,
      "open": 10.62,
      "high": 10.75,
      "low": 10.45,
      "change_pct": -0.558,
      "amount_yuan": 771751341.0,
      "provider_timestamp": null,
      "quote_date": null,
      "date_verification": "not_independently_verified"
    },
    "url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/stocks/600000.json"
  },
  "themes": {
    "trade_date": "2026-11-23",
    "run_id": "20261123T212107-a9a78f05915d47fea1998e8fe2c6f09b",
    "status": "partial_research",
    "ranking_scope": "dated_partial_active_associations",
    "observed_at": "2026-11-23T21:21:07+08:00",
    "strength_definition": "0–100的样本观察活跃度，不是已独立核验的正式全市场题材强度。",
    "formal_full_market_strength_available": false,
    "missing_data": [
      "完整历史题材成分未知，不能用当前成员倒填；正式全市场强度与相对市场收益为空",
      "40日全主板轻量行情仅有16/40日已存快照，快照字段未全部独立核验",
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
        "as_of": "2026-11-23",
        "rank": 1,
        "activity_score": 98.30912,
        "composite_score": 98.30912,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "B": {
        "theme_id": "光通信",
        "theme_name": "光通信",
        "as_of": "2026-11-23",
        "rank": 2,
        "activity_score": 76.216468,
        "composite_score": 76.216468,
        "full_score": null,
        "score_kind": "partial_observed_activity",
        "seat_status": "provisional_observation",
        "scope": "dated_observed_associations"
      },
      "C": null
    },
    "archive_url": "https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-23/20261123T212107-a9a78f05915d47fea1998e8fe2c6f09b/"
  }
}
```

## 按问题读取完整原文

- [本轮完整行情摘要](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/latest.json)；[行情说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/latest.md)。
- 其他股票使用六位代码替换 CODE：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/stocks/CODE.json
- [代码覆盖与缺失股票](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/market_coverage.json)；[指数](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/indices.json)。
- [涨停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/limit_up.json)；[炸板池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/broken.json)；[跌停池](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/limit_down.json)。
- [首板候选](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/first_board_candidates.json)；[后续跟踪](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/followup.json)；[晋级观察](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/promotion.json)。
- 全市场逐股表：https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/close/2026-11-24/20261124T150502077564%2B0800/market_quotes.json。该文件较大，问个股优先读取单股文件。
- [题材评分与核心股：2026-11-23](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-23/20261123T212107-a9a78f05915d47fea1998e8fe2c6f09b/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/research-v2/2026-11-23/20261123T212107-a9a78f05915d47fea1998e8fe2c6f09b/latest.md)。
- [长期跟踪与题材关联：2026-11-23](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-23/20261123T212001-272302ad929e4aa5ad1367801ebe4f63/latest.json)；[说明](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/archive/lifecycle/2026-11-23/20261123T212001-272302ad929e4aa5ad1367801ebe4f63/latest.md)。

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
