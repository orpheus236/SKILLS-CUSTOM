---
name: winrate-optimizer
description: Analyze and improve winrate for Binance Futures trading strategies. Evaluates performance, identifies weaknesses in signal, entry, risk management, and exit logic, then provides prioritized recommendations. Can analyze codebase and trading data.
---

# Winrate Optimizer

## Purpose
Membantu meningkatkan winrate trading futures Binance dengan cara menganalisis performa saat ini, mengidentifikasi kelemahan, dan memberikan rekomendasi perbaikan yang spesifik dan actionable.

## When to Use
- Winrate trading bot sedang rendah atau stagnan
- Ingin melakukan optimasi strategi secara menyeluruh
- Butuh diagnosis mendalam terhadap logic trading (signal, entry, risk, exit)
- Sebelum melakukan perubahan besar pada strategi trading

## Core Analysis Dimensions

Skill ini akan mengevaluasi aspek-aspek berikut:

1. **Signal Quality** — Akurasi sinyal, false positive rate, konfirmasi multi-factor
2. **Entry Logic** — Timing entry, konfirmasi, slippage
3. **Risk Management** — Position sizing, risk per trade, leverage management
4. **Exit Strategy** — Take profit, stop loss, trailing stop effectiveness
5. **Market Regime Adaptation** — Kemampuan strategi beradaptasi di market trending vs ranging
6. **Overtrading & Frequency** — Jumlah trade dan kualitas seleksi setup
7. **Overall Performance Metrics** — Winrate, Profit Factor, Expectancy, Max Drawdown, Recovery Factor

## Core Process

### Phase 1: Pahami Kondisi Saat Ini
- Minta data performa trading (winrate, total trade, profit factor, drawdown, dll)
- Tanyakan periode backtest / live trading yang ingin dianalisis
- Klarifikasi apakah ada target winrate atau metrik tertentu yang ingin dicapai

### Phase 2: Analisis Codebase (jika tersedia)
- Baca dan pahami logic trading di Orpheus-AI (scanner, signal engine, decision making, risk management, trailing stop, dll)
- Identifikasi bagian mana yang berpotensi menjadi penyebab winrate rendah
- Evaluasi implementasi multi-factor analysis, risk rules, dan exit logic

### Phase 3: Analisis Data Trading (jika tersedia)
- Analisis hasil backtest atau live trading log
- Identifikasi pola kekalahan (misalnya: kalah di ranging market, kalah di high volatility, exit terlalu cepat, dll)
- Hitung metrik penting (winrate per kondisi market, average win/loss, dll)

### Phase 4: Diagnosis & Identifikasi Masalah
Berikan diagnosis yang jelas, contoh:
- Signal terlalu longgar → banyak false signal
- Trailing stop terlalu agresif → sering kena stop padahal trend masih bagus
- Position sizing tidak konsisten
- Kurangnya regime detection

### Phase 5: Rekomendasi Perbaikan
Berikan rekomendasi yang diprioritaskan (High / Medium / Low impact), meliputi:
- Perbaikan di signal & filtering
- Peningkatan risk management & position sizing
- Optimasi exit strategy
- Penambahan market regime detection
- Pengurangan overtrading
- Saran parameter tuning atau penambahan filter baru

### Phase 6: Prioritas & Roadmap
- Berikan urutan prioritas perbaikan
- Sarankan pendekatan bertahap (quick win → medium → structural improvement)
- Estimasi dampak terhadap winrate jika memungkinkan

## Important Rules
- Selalu berikan **bukti** atau alasan di balik setiap diagnosis.
- Rekomendasi harus **spesifik** dan **implementable** di kode.
- Pertimbangkan **risk management** sebagai prioritas tinggi (jangan hanya kejar winrate tinggi dengan risiko besar).
- Untuk futures trading, perhatikan juga faktor **leverage**, **funding rate**, dan **slippage**.
- Jika data tidak lengkap, catat sebagai **Open Item** dan sarankan data apa yang perlu disediakan.
- Bisa digunakan untuk strategi futures Binance (scalping, swing, atau trend following).
- Fokus pada peningkatan **kualitas** setup, bukan hanya menambah jumlah trade.