---
name: prd-creator
description: Create detailed and comprehensive Product Requirements Documents (PRD). Supports codebase analysis, prioritization, and effort estimation. Use when defining new features, improvements, or new products.
---

# PRD Creator

## Purpose
Membantu membuat Product Requirements Document (PRD) yang detail, terstruktur, dan actionable. Skill ini bisa menganalisis codebase yang sudah ada, menentukan prioritas, serta memberikan estimasi effort.

## When to Use
- Merancang fitur baru yang kompleks
- Membuat PRD untuk product baru atau major update
- Butuh dokumentasi yang lengkap sebelum mulai development
- Ingin mempertimbangkan existing codebase sebelum menulis requirement

## Core Process

### Phase 1: Pahami Konteks & Tujuan
- Klarifikasi apa yang ingin dibangun (fitur / product / improvement)
- Pahami tujuan bisnis dan user yang ingin dicapai
- Tanyakan prioritas relatif terhadap fitur lain (jika ada)
- Identifikasi apakah ada existing codebase yang perlu dianalisis

### Phase 2: Analisis Codebase (jika ada)
Jika user memberikan akses ke codebase:
- Pahami struktur project saat ini
- Identifikasi komponen/module yang relevan dengan fitur baru
- Cari existing pattern, convention, dan technical debt yang perlu diperhatikan
- Evaluasi dampak perubahan terhadap sistem yang sudah ada

### Phase 3: Susun Struktur PRD
Buat PRD dengan struktur berikut (bisa disesuaikan):

1. **Executive Summary**
2. **Problem Statement** (masalah yang ingin diselesaikan)
3. **Goals & Success Metrics** (tujuan + cara mengukur keberhasilan)
4. **User Stories / Use Cases**
5. **Functional Requirements** (detail fitur yang dibutuhkan)
6. **Non-Functional Requirements** (performance, security, scalability, dll)
7. **Technical Considerations** (berdasarkan analisis codebase)
8. **Dependencies & Risks**
9. **Prioritization** (MoSCoW atau High/Medium/Low)
10. **Effort Estimation** (dalam story point atau hari/orang)
11. **Open Questions** (hal yang masih perlu diklarifikasi)

### Phase 4: Prioritas & Estimasi
- Bantu tentukan prioritas fitur berdasarkan value vs effort
- Berikan estimasi kasar (Low / Medium / High complexity)
- Sarankan pendekatan bertahap (MVP → Full version) jika diperlukan

### Phase 5: Review & Finalisasi
- Review kelengkapan PRD
- Pastikan requirement jelas, measurable, dan tidak ambigu
- Berikan rekomendasi tambahan jika ada gap

## Important Rules
- PRD harus **detail** dan **actionable** untuk tim development.
- Selalu pertimbangkan **existing codebase** jika tersedia (jangan membuat requirement yang bertentangan dengan arsitektur saat ini).
- Sertakan **Success Metrics** yang jelas dan bisa diukur.
- Berikan **Prioritas** dan **Estimasi Effort** di setiap requirement penting.
- Gunakan bahasa yang netral dan profesional.
- Jika ada ambiguity, catat sebagai **Open Questions**.
- Bisa digunakan untuk berbagai jenis product (AI tool, SaaS, internal tool, dll).
- Jangan terlalu teknis di bagian requirement bisnis, tapi tetap realistis secara teknis.