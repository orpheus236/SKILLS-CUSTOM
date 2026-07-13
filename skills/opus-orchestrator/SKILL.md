---
name: opus-orchestrator
description: Use Opus as the architect/orchestrator. Routes implementation work primarily to Grok 4.5 while maintaining high judgment quality. Use when building or improving multi-step features, agents, or complex systems.
---

# Opus Orchestrator with Grok 4.5 Implementer

## Purpose
Menggunakan **Opus** sebagai architect utama (perencanaan, decomposition, verification), sementara **Grok 4.5** sebagai implementer utama untuk eksekusi (coding).

## Core Pattern

### 1. Architect Role (Opus)
- Bertanggung jawab atas:
  - Requirements & planning
  - Task decomposition
  - Specification writing
  - Decision making
  - Final verification

### 2. Implementation Lane (Grok 4.5)
- **Default implementer**: Grok 4.5 (via Grok CLI)
- Keunggulan Grok 4.5: cepat, murah, dan kuat untuk implementasi rutin
- Untuk task high-stakes, bisa race dengan model lain (Sonnet, dll) lalu Opus memilih yang terbaik

### 3. Routing Doctrine
- Opus memutuskan kapan harus delegate ke Grok 4.5
- Opus hanya melakukan judgment, bukan mengetik kode volume besar
- Setiap hasil implementasi dari Grok 4.5 diverifikasi oleh Opus sebelum diterima

## Cara Pakai

1. Mulai session dengan model **Opus**
2. Berikan task seperti biasa, skill ini akan otomatis mengarahkan workflow:
   - Opus merencanakan dan membuat spec
   - Delegate ke Grok 4.5 untuk implementasi
   - Opus verifikasi hasil

Contoh prompt:
"Add new risk management engine to Orpheus-AI. Plan it, delegate implementation to Grok 4.5, and verify before marking done."

## Important Rules
- Opus adalah architect — jangan biarkan ia melakukan coding volume besar.
- Grok 4.5 adalah default implementer (pastikan Grok CLI sudah terinstall dan authenticated).
- Selalu verifikasi hasil implementasi sebelum accept.
- Gunakan cross-check jika diperlukan (Opus review hasil Grok 4.5).
- Cocok untuk project kamu (Orpheus-AI, multi-agent system, dll).
- Prioritaskan reliability, risk management, dan performance.

## Setup Grok 4.5 Implementer
Pastikan Grok CLI sudah terinstall:
```bash
grok login