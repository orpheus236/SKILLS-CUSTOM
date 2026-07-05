---
name: codebase-auditor
description: Perform comprehensive codebase inspection, architecture review, and systematic bug detection. Use when user wants deep audit, structural analysis, bug hunting, or architecture review of the current project.
---

# Codebase Auditor

## Purpose
Melakukan audit mendalam terhadap codebase yang sedang dikerjakan. Mengidentifikasi bug, code smell, masalah arsitektur, dan memberikan rekomendasi perbaikan yang actionable.

## When to Use
- User meminta audit, review, atau inspeksi codebase
- Sebelum melakukan refactor besar
- Ingin mengetahui kesehatan dan kualitas struktur project
- Melengkapi workflow dari using-superpowers dan Matt Pocock skills

## Core Process

### 1. Pahami Scope
- Tanyakan kepada user: mau audit keseluruhan project atau fokus ke bagian tertentu?
- Identifikasi bahasa pemrograman utama dan framework yang dipakai.

### 2. Mapping Struktur Project
- Eksplorasi struktur folder dan file utama
- Identifikasi:
  - Entry point / main files
  - Core modules vs utility
  - Layer arsitektur (jika ada)
  - File konfigurasi dan dependency

### 3. Architectural Analysis
Gunakan prinsip-prinsip berikut saat menganalisis:
- **Module Depth & Responsibility**: Apakah module terlalu besar atau terlalu kecil?
- **Coupling & Cohesion**: Seberapa erat antar module saling bergantung?
- **Seams & Abstraction**: Apakah ada boundary yang jelas?
- **Testability**: Seberapa mudah menguji logic penting secara terpisah?
- **Error Handling & Resilience**: Bagaimana error ditangani, terutama pada bagian kritis?

### 4. Systematic Issue Detection
Cari hal-hal berikut:
- Broad exception handling / bare `except`
- Silent failures (`pass` di dalam except)
- TODO/FIXME/HACK yang sudah lama atau kritis
- Duplikasi logic
- God class / file yang terlalu besar
- Hardcoded secrets atau konfigurasi sensitif
- Kurangnya logging di jalur penting
- Logic bisnis yang sulit di-test

### 5. Prioritized Findings
Susun temuan dengan kategori:
- **Critical** — Bisa menyebabkan bug serius atau risiko
- **High** — Masalah maintainability atau reliability yang signifikan
- **Medium** — Code smell yang sebaiknya diperbaiki
- **Low** — Improvement kecil

Setiap temuan harus disertai:
- Lokasi file
- Penjelasan masalah
- Dampaknya
- Rekomendasi perbaikan

### 6. Recommendations & Output
- Berikan 3–5 rekomendasi prioritas tertinggi
- Bedakan antara quick wins dan perubahan struktural
- Tawarkan untuk:
  - Membahas lebih dalam satu temuan tertentu
  - Membuat proposal refactor
  - Membuat rencana perbaikan bertahap

## Important Rules
- Selalu berikan bukti (kutip kode) saat menyebutkan masalah.
- Fokus pada hal yang berdampak tinggi, jangan terlalu detail pada style.
- Untuk project Python, berikan perhatian lebih pada error handling dan struktur module.
- Jadikan laporan mudah dibaca dan actionable.
- Setelah memberikan temuan, tawarkan langkah selanjutnya secara proaktif.