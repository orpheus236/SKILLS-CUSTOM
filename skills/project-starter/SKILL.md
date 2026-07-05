---
name: project-starter
description: Help build new projects from scratch. Provides structured guidance and scaffolding for starting any type of project (web app, full-stack, backend, AI agent, etc.). Use when starting a new project from zero.
---

# Project Starter

## Purpose
Membantu user memulai project baru dari awal dengan cara yang terstruktur, rapi, dan profesional. Skill ini memberikan panduan proses sekaligus rekomendasi struktur project yang baik.

## When to Use
- User ingin membuat project baru dari nol
- Butuh bantuan menentukan struktur folder dan arsitektur dasar
- Ingin setup project yang clean dan scalable sejak awal
- Mau memulai project dengan tech stack tertentu (Next.js, Python, Full-stack, dll)

## Core Process

### Phase 1: Pahami Project
Tanyakan hal-hal berikut:
- Nama project dan tujuannya
- Jenis project (Web App, SaaS, Landing Page, AI Agent, Backend API, Full-stack, dll)
- Tech stack yang ingin dipakai (atau tanyakan preferensi)
- Target user / audience
- Fitur utama yang harus ada di awal

### Phase 2: Rekomendasikan Tech Stack & Arsitektur
Berdasarkan jawaban user, berikan rekomendasi:
- Tech stack yang paling cocok
- Alasan pemilihan stack tersebut
- Alternatif stack (jika ada)
- High-level architecture (monolith, modular, dll)

### Phase 3: Rancang Struktur Project
Berikan struktur folder yang rapi dan scalable, contoh:
- Untuk Next.js: app router structure, components, lib, types, dll
- Untuk Python: src layout, domain-driven, atau clean architecture
- Untuk Full-stack: pemisahan frontend & backend yang jelas

Selalu jelaskan alasan di balik struktur yang dipilih.

### Phase 4: Setup Awal & Scaffolding
Bantu user dengan:
- Command untuk inisialisasi project
- File dan folder penting yang harus dibuat di awal
- Konfigurasi dasar (ESLint, Prettier, TypeScript, testing, dll)
- README.md awal yang baik
- Git initialization & .gitignore

### Phase 5: Langkah Selanjutnya
Berikan roadmap singkat untuk fase awal development, misalnya:
- Setup authentication (jika perlu)
- Buat halaman/feature pertama
- Setup database / state management
- Testing setup

## Important Rules
- Selalu tanyakan tech stack dan tujuan project terlebih dahulu sebelum memberikan rekomendasi.
- Berikan alasan di setiap rekomendasi struktur atau tech stack.
- Hindari membuat struktur yang terlalu rumit di awal. Utamakan kesederhanaan dan scalability.
- Bisa menangani berbagai jenis project (bukan hanya satu framework).
- Jika user belum yakin dengan tech stack, berikan beberapa opsi beserta pro & cons-nya.
- Fokus pada kualitas struktur project sejak hari pertama.