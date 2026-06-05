# BSC Four.meme Narrative Source Analysis

公开研究台：基于 BSC Four.meme 交易员链上数据，扩展为叙事源追踪、买入后发酵窗口统计和 BSC 打狗算法模型沉淀。

Public dashboard: reconstructs a BSC Four.meme trader's onchain behavior, then adds narrative-source candidates, post-entry fermentation windows, and reusable signal rules.

## Public Site

https://hahahakang.github.io/bsc-fourmeme-narrative-source-analysis/

This project is intentionally separate from `hahahakang/bsc-fourmeme-analysis`, which should keep the original article/report.

## What This Version Adds

- First-batch source timeline ledger: links each major token to a candidate origin event, source grade, buy-vs-source window, relationship strength, and bot implication.
- Source library: durable source objects for people, companies, projects, official accounts, media IP, Chinese short-video memes, and offchain analogues such as Jensen Huang/Marvell.
- Narrative-source candidate pool: token names, descriptions, source-type guesses, source status, and research priority.
- Fermentation window statistics: holding/exit windows, win rate, realized PnL, FDV, and liquidity by time bucket.
- FDV bucket x holding window matrix: which entry nodes and waiting windows historically worked better.
- Signal model draft: source quality, time advantage, onchain quality, liquidity execution, and risk penalties.

## Data Files

- `data/source_timeline_research.csv`
- `data/source_library.csv`
- `data/narrative_candidates.csv`
- `data/fermentation_window_summary.csv`
- `data/bucket_window_summary.csv`
- `data/source_signal_model.csv`
- `data/token_trade_summary_with_windows.csv`
- `data/buy_detail_with_fdv.csv`
- `data/fdv_bucket_summary.csv`
- `data/top_winners.csv`
- `data/top_losers.csv`

## Caveat

Onchain trade reconstruction and window statistics are derived from local decoded data. Source grades are evidence grades, not buy ratings: A means original/official source, B strong secondary source with original-post context, C token/project page attribution, D post-hoc community explanation, and E no matched source yet. This repository is for research only and is not investment advice.
