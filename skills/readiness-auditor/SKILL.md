---
name: readiness-auditor
description: Perform comprehensive production readiness audit for AI agents and systems. Evaluates code quality, testing, security, reliability, observability, deployment readiness, and more. Use before releasing AI agents or complex systems to production.
---

# Readiness Auditor

## Purpose
Melakukan audit menyeluruh untuk mengevaluasi apakah sebuah AI Agent atau system sudah siap digunakan di production. Skill ini memberikan penilaian objektif beserta rekomendasi perbaikan.

## When to Use
- Sebelum merilis AI Agent atau fitur besar ke production
- Melakukan health check pada system yang sudah berjalan
- Menilai kesiapan infrastructure, code, dan operational aspect
- Ingin mendapatkan checklist dan rekomendasi yang terstruktur

## Core Audit Dimensions

Skill ini akan mengevaluasi aspek-aspek berikut:

1. **Code Quality & Maintainability**
2. **Testing & Quality Assurance**
3. **Security & Safety** (termasuk prompt injection, tool abuse, dll)
4. **Reliability & Error Handling**
5. **Observability** (logging, tracing, monitoring)
6. **Performance & Scalability**
7. **Documentation**
8. **Deployment & Infrastructure Readiness**
9. **Operational Readiness** (runbook, alerting, incident response)
10. **AI-Specific Concerns** (prompt consistency, agent reliability, cost/token management)

## Core Process

### Phase 1: Pahami Scope Audit
- Klarifikasi apa yang akan diaudit (satu agent, beberapa agent, seluruh system, atau infrastructure)
- Tanyakan tingkat readiness yang diharapkan (MVP, Beta, atau Production-grade)
- Identifikasi apakah ada codebase yang perlu dianalisis

### Phase 2: Analisis Codebase & System
Jika codebase tersedia:
- Review struktur project dan arsitektur
- Evaluasi code quality, error handling, dan maintainability
- Periksa testing coverage dan kualitas test
- Analisis security posture (terutama yang berkaitan dengan AI Agent)
- Tinjau dokumentasi dan observability implementation

### Phase 3: Lakukan Audit per Dimensi
Evaluasi setiap dimensi dengan checklist yang relevan. Berikan penilaian:
- **Ready**
- **Needs Improvement**
- **Not Ready**

 Sertakan bukti dan contoh dari codebase jika memungkinkan.

### Phase 4: Berikan Rekomendasi & Prioritas
- Susun temuan berdasarkan tingkat kepentingan (Critical / High / Medium / Low)
- Berikan rekomendasi perbaikan yang spesifik dan actionable
- Sarankan urutan prioritas perbaikan

### Phase 5: Kesimpulan & Go/No-Go Recommendation
Berikan kesimpulan akhir berupa:
- Status kesiapan secara keseluruhan
- Rekomendasi go / no-go (atau conditional go)
- Daftar item yang **harus** diselesaikan sebelum production

## Important Rules
- Fokus pada **production readiness**, bukan hanya code quality.
- Berikan penilaian yang **objektif** dan **berbasis bukti**.
- Untuk AI Agent, perhatikan aspek khusus seperti reliability agent, security (prompt injection, tool misuse), cost management, dan observability decision-making process.
- Jika ada aspek yang tidak bisa dinilai karena kurangnya informasi, catat sebagai **Open Item**.
- Rekomendasi harus **actionable** dan realistis.
- Bisa digunakan untuk berbagai jenis AI system (single agent, multi-agent, RAG, tool-using agent, dll).
- Selalu berikan **prioritas** pada temuan yang paling kritis.