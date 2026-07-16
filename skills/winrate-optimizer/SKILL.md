---
name: winrate-optimizer
description: Analyze and improve trading strategy winrate across Futures, Forex, and equities. Reviews signal quality, entry/exit logic, risk management, regime adaptation, and performance metrics. Best used for strategy review, backtest analysis, and bot optimization.
---

# Winrate Optimizer

## Purpose
Membantu meningkatkan kualitas keputusan trading dengan menganalisis strategi secara sistematis, mengidentifikasi akar masalah, dan memberi rekomendasi perbaikan yang fokus pada winrate sehat, bukan sekadar hasil agresif.

## When to Use
- User ingin meningkatkan winrate strategi trading
- Strategi sering menghasilkan false signal atau overtrading
- Butuh review mendalam terhadap logic entry, exit, dan risk management
- Ingin menganalisis backtest, live trading data, atau codebase bot

## What This Skill Evaluates

Skill ini akan mengevaluasi:

1. **Signal Quality** — Akurasi sinyal, false positive rate, dan kualitas filter
2. **Entry Logic** — Timing entry, konfirmasi setup, dan eksekusi
3. **Risk Management** — Position sizing, risk per trade, leverage, dan exposure
4. **Exit Strategy** — Take profit, stop loss, trailing stop, dan exit timing
5. **Market Regime Adaptation** — Kemampuan beradaptasi di trending, ranging, atau volatile market
6. **Overtrading & Trade Management** — Frekuensi trading dan kualitas setup
7. **Overall Performance** — Winrate, Profit Factor, Expectancy, Drawdown, dan Recovery Factor

## Workflow

### Phase 1: Pahami Kondisi Saat Ini
- Minta data performa trading (winrate, total trade, profit factor, drawdown, dll)
- Tanyakan instrument yang digunakan (Futures, Forex, Saham) dan timeframe
- Klarifikasi target winrate atau metrik yang ingin dicapai

### Phase 2: Analisis Codebase (jika tersedia)
- Baca dan pahami logic trading (scanner, signal engine, decision making, risk, exit)
- Identifikasi bagian yang berpotensi menyebabkan winrate rendah
- Evaluasi implementasi di berbagai market dan kondisi pasar

### Phase 3: Analisis Data Trading
- Analisis hasil backtest atau live trading
- Identifikasi pola kekalahan per market atau regime
- Hitung metrik penting per kondisi market

### Phase 4: Diagnosis & Identifikasi Masalah
Berikan diagnosis yang jelas, misalnya:
- Signal terlalu longgar di ranging market
- Trailing stop kurang efektif di trending market
- Position sizing tidak adaptif terhadap volatility
- Kurangnya filter market regime
- Overtrading akibat kualitas setup yang lemah

### Phase 5: Rekomendasi Perbaikan
Berikan rekomendasi yang diprioritaskan (High / Medium / Low impact), mencakup:
- Perbaikan signal dan filtering
- Optimasi risk management dan position sizing
- Perbaikan exit strategy
- Penambahan regime detection
- Pengurangan overtrading
- Saran parameter tuning atau penambahan logic baru

Untuk setiap rekomendasi, sertakan:
- alasan mengapa penting
- dampak yang diharapkan
- petunjuk implementasi yang konkret

### Phase 6: Prioritas & Roadmap
- Urutkan perbaikan dari quick win ke structural improvement
- Berikan roadmap bertahap yang realistis
- Estimasi dampak terhadap winrate jika memungkinkan

## Important Rules
- Skill ini bersifat universal untuk Futures, Forex, dan Saham.
- Selalu berikan bukti atau alasan di balik diagnosis.
- Rekomendasi harus spesifik dan implementable.
- Prioritaskan risk management — jangan hanya mengejar winrate tinggi dengan risiko besar.
- Untuk Futures, perhatikan leverage, funding rate, dan likuiditas.
- Untuk Forex dan Saham, perhatikan spread, volatility, dan session trading.
- Jika data tidak lengkap, catat sebagai Open Item.