# Org chart

```
SUMMIT
Chief Investment Officer -- sits in Sigma, final sign-off on every use case
|
+-- ALPHA DESK (crypto)
|     +-- Oracle         Senior Crypto Market Analyst -- desk lead
|     +-- Cipher         Crypto Data Analyst
|     +-- Kronos         Crypto Data Acquirer
|     +-- Specter        Meme Coin and New Launch Monitor
|     +-- Sentinel       Crypto Alert and Notification Manager
|     +-- Volta          Technical Analysis Specialist (also supports Beta Desk)
|
+-- BETA DESK (equities)
|     +-- Athena         Senior Stock Market Analyst -- desk lead
|     +-- Ledger         Stocks Data Analyst
|     +-- Hermes         Stocks Data Acquirer
|     +-- Beacon         Stock Alert and Notification Manager
|     +-- Sterling       Fundamental Financial Analyst
|     +-- Vanguard       Commodities and Futures Analyst
|     +-- Gaia           Global Climate and Weather Intelligence Analyst
|     +-- Harbinger      Consumer Stress and Recession Leading Indicator
|
+-- YANKEE DESK (US-focused)
|     +-- Madison        Senior US Equity Analyst
|     +-- Hamilton       Fundamental Financial Analyst, US Markets
|     +-- Garrison       US Market End of Day Briefing
|
+-- GAMMA (review and oversight)
|     +-- Auditor        Performance Auditor (system and pipeline health)
|     +-- Cartographer   Portfolio and Equity Curve Tracker (every use case)
|     +-- Counsel        Strategic Trading Advisor (weekly review)
|
+-- SIGMA (macro, strategy, and architecture)
|     +-- Summit         Chief Investment Officer
|     +-- Contrarian     Devil's Advocate (stress-tests every use case)
|     +-- Atlas          Geopolitical and Macro Intelligence Analyst
|     +-- Nixon          US Analyst
|     +-- Rideau         Canadian Analyst
|     +-- Strategist     Portfolio Strategist and Playbook Advisor
|     +-- Axiom          System Knowledge and Architecture Authority
|     +-- Scribe         Business Requirements and Architecture Authority
|     +-- Tally          Backlog and Billing Tracker
|     +-- Lens           System Observability Agent
|
+-- DELTA (operations and infrastructure)
|     +-- Forge          Development Director -- team lead
|     +-- Wrench         Full Stack Developer
|     +-- Aegis          Security and System Monitor
|     +-- Vault          Backup and Data Integrity Manager
|     +-- Mason          WordPress Developer and Site Manager
|
+-- PI (standalone)
|     +-- Prometheus     Prediction Market Intelligence Analyst
|
+-- EXECUTION (standalone)
      +-- Trader         Autonomous Paper Trader -- active on Alpha Desk use cases only

Cross-cutting relationships (do not follow the tree above):
  - Summit sits in Sigma administratively, but is confirmed via real
    soul_inbox writes to receive output from every Alpha and Beta use
    case, which is why it appears on every one of them.
  - Contrarian was investigated directly and confirmed to operate only
    in the interactive #ask-sigma committee code path, not in any
    scheduled per-use-case pipeline. It is not claimed on individual
    use cases, since there is no real evidence it reviews them
    automatically.
  - Atlas (Sigma) receives real soul_inbox writes from two specific
    Alpha use cases (002, 004) and is a real, direct core contributor
    to every Commodities use case (verified soul_loader call).
  - Trader, Garrison, Cartographer, and Auditor are not claimed on any
    individual use case in this repo. Each was investigated directly;
    none had real, traceable per-use-case code evidence strong enough
    to publish, even though their own bios describe related work at
    the platform or desk level.
```
