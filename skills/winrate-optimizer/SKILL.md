---
name: winrate-optimizer
description: Analyze and improve winrate for trading strategies across various markets (Futures, Forex, Saham). Evaluates signal quality, risk management, exit strategy, regime detection, and overall performance. Can analyze codebase and trading data.
---

# Winrate Optimizer

## Purpose
Membantu meningkatkan winrate trading di berbagai instrument (Binance Futures, Forex, Saham) dengan menganalisis performa, mengidentifikasi kelemahan, dan memberikan rekomendasi perbaikan yang spesifik.

## When to Use
- Winrate strategi trading sedang rendah atau stagnan
- Ingin optimasi strategi di Futures, Forex, atau Saham
- Melakukan review mendalam terhadap logic trading
- Sebelum melakukan perubahan besar pada bot atau strategi

## Core Analysis Dimensions

Skill ini akan mengevaluasi:

1. **Signal Quality** — Akurasi sinyal, false positive rate, multi-factor confirmation
2. **Entry Logic** — Timing entry, konfirmasi, slippage
3. **Risk Management** — Position sizing, risk per trade, leverage management
4. **Exit Strategy** — Take profit, stop loss, trailing stop effectiveness
5. **Market Regime Adaptation** — Kemampuan beradaptasi di trending, ranging, volatile market
6. **Overtrading & Trade Management** — Frekuensi trade, quality setup
7. **Overall Performance** — Winrate, Profit Factor, Expectancy, Drawdown, Recovery Factor

## Core Process

### Phase 1: Pahami Kondisi Saat Ini
- Minta data performa trading (winrate, total trade, profit factor, drawdown, dll)
- Tanyakan market yang digunakan (Futures, Forex, Saham) dan timeframe
- Klarifikasi target winrate atau metrik yang ingin dicapai

### Phase 2: Analisis Codebase (jika tersedia)
- Baca dan pahami logic trading (scanner, signal engine, decision making, risk, exit)
- Identifikasi bagian yang berpotensi menyebabkan winrate rendah
- Evaluasi implementasi di berbagai market (Futures, Forex, Saham)

### Phase 3: Analisis Data Trading
- Analisis hasil backtest atau live trading
- Identifikasi pola kekalahan per market
- Hitung metrik penting per kondisi market

### Phase 4: Diagnosis & Identifikasi Masalah
Berikan diagnosis yang jelas, contoh:
- Signal terlalu longgar di ranging market
- Trailing stop kurang efektif di trending market
- Position sizing tidak adaptif terhadap volatility
- Kurangnya filter market regime

### Phase 5: Rekomendasi Perbaikan
Berikan rekomendasi yang diprioritaskan (High / Medium / Low impact), meliputi:
- Perbaikan signal & filtering (bisa berbeda per market)
- Optimasi risk management & position sizing
- Perbaikan exit strategy
- Penambahan regime detection
- Pengurangan overtrading
- Saran parameter tuning atau penambahan logic baru

### Phase 6: Prioritas & Roadmap
- Urutan prioritas perbaikan
- Pendekatan bertahap (quick win → structural improvement)
- Estimasi dampak terhadap winrate jika memungkinkan

## Important Rules
- Skill ini bersifat **universal** untuk Futures, Forex, dan Saham.
- Selalu berikan **bukti** atau alasan di balik diagnosis.
- Rekomendasi harus **spesifik** dan **implementable**.
- Prioritaskan **risk management** — jangan hanya mengejar winrate tinggi dengan risiko besar.
- Untuk Futures, perhatikan leverage dan funding rate.
- Untuk Forex & Saham, perhatikan spread, volatility, dan session (London, New York, dll).
- Jika data tidak lengkap, catat sebagai Open Item.