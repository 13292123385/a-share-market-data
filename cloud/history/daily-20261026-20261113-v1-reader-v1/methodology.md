# 历史回补计算口径及局限

回补批次：daily-20261026-20261113-v1。范围：2026-10-26至2026-11-13。状态：partial。
阅读页生成时间：2026-11-13T23:23:08.427041+08:00；不是交易或行情采集时间。此页为腾讯云数据库历史快照经GitHub中转。
[同批次原始JSON](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1/methodology.json)；[计算口径](https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/history/daily-20261026-20261113-v1-reader-v1/methodology.md)。null表示缺失，不补零。

- batch_id：daily-20261026-20261113-v1
- start_date：2026-10-26
- end_date：2026-11-13
- created_at：2026-11-13T22:42:34.497126+08:00
- finished_at：2026-11-13T22:43:19.608031+08:00
- benchmark：CSI300 sh000300 price index
- metrics_basis：qfq captured at backfill time; retrospective, not point-in-time adjusted price
- daily_pct_change_basis：unadjusted close/previous exchange-session close; corporate actions may differ from exchange percentage
- pct_change_notice：Provider daily percentage unavailable; pct_change is computed unadjusted close return, adjusted_daily_return_pct is qfq close return. Neither is certified exchange-reported percentage.
- drawdown_basis：negative close-to-close drawdown, includes baseline close; not intraday maximum drawdown
- interval_baseline：last exchange session before 2026-10-26; unavailable baseline yields null
- scope_note：Union of available official rosters, listing-date filtered. Historical delistings absent in all saved rosters cannot be guaranteed.
- missing_policy：No zero imputation, no price forward fill, no inferred suspension confirmation; unavailable metric is null.
- historical_universe_verified：false
- historical_non_st_verified：false
- original_research：untouched, separate reconstruction batch
- crosscheck：Five stocks / 75 daily bars matched independent Sina OHLC within 0.011 yuan and volume/amount within 0.5% or 100 units; sixth stock 689009 unavailable from Sina. Not full-market verification.
- protected_archive_files：8213
- protected_archives_verified_unchanged：true
