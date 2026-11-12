# 手机读取入口

先读同目录 index.md、index.json、status.json。按各流交易日和时点使用数据。单股读取 close/stocks/CODE.json；午间读取 midday/stocks/CODE.json。CODE为六位代码。固定归档位置见 https://raw.githubusercontent.com/13292123385/a-share-market-data/main/cloud/index.json 各流archive_url；缺失与null不解释为零，诊断不是有效午间快照。
