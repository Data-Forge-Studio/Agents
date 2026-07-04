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
  - Summit and Contrarian sit in Sigma administratively, but their work
    touches every use case on every desk, which is why both are in the
    automatic oversight tier applied to every Use-Cases file.
  - Cartographer (Gamma) is also in that automatic oversight tier, since
    portfolio tracking is inherently all-encompassing by design.
  - Auditor (Gamma) is NOT in that tier. Its review is about system and
    pipeline health, not a per-trade signoff, so it is not claimed on
    individual use cases the way Cartographer is.
  - Trader (Execution) is tagged only on Alpha Desk use cases, where
    paper execution is genuinely active today. Equity execution is
    planned, not active, and is not claimed here.
  - Garrison (Yankee Desk) is tagged on Madison's use cases as end of
    day desk context, not as a research contributor the way Madison is.
    They are the same desk doing two different jobs.
```
