---
name: workspace-designer
description: Design modern workspaces and dashboards for web applications, especially AI agent tools. Helps with layout structure, component selection, UX patterns, and frontend implementation using Next.js + Tailwind. Use when building internal tools, admin panels, or AI workspaces.
---

# Workspace Designer

## Purpose
Membantu merancang workspace dan dashboard yang modern, bersih, dan fungsional untuk aplikasi web, khususnya tools berbasis AI Agent. Skill ini bersifat universal dan bisa digunakan untuk berbagai jenis SaaS atau AI product.

## When to Use
- Merancang workspace/dashboard untuk AI Agent (chat interface, agent management, monitoring, dll)
- Membuat admin panel atau internal tool
- Butuh bantuan menentukan layout, navigasi, dan komponen UI
- Ingin membuat frontend yang profesional dan mudah digunakan

## Core Process

### Phase 1: Pahami Kebutuhan Workspace
Tanyakan atau klarifikasi:
- Jenis workspace yang dibutuhkan (AI Agent workspace, admin dashboard, monitoring tool, dll)
- Fitur utama yang harus ada
- Target user (developer, non-technical user, power user, dll)
- Tech stack yang digunakan (Next.js + Tailwind direkomendasikan)

### Phase 2: Rancang Struktur Layout
Berikan rekomendasi struktur layout yang baik, contoh:
- Sidebar navigation (dengan collapse)
- Top navigation bar
- Main content area
- Right sidebar / detail panel (opsional)
- Responsive behavior (mobile-first)

Fokus pada **clarity**, **navigation yang jelas**, dan **efisiensi** dalam menggunakan workspace.

### Phase 3: Rekomendasikan Komponen & Pattern
Berikan rekomendasi komponen UI yang sesuai, seperti:
- Data table & list view
- Chat interface (untuk AI Agent)
- Agent card / status indicator
- Form & settings panel
- Modal, drawer, dan toast notification
- Empty state & loading state

Gunakan pattern yang umum dipakai di SaaS modern (shadcn/ui style atau serupa).

### Phase 4: Desain UX & Interaksi
- Sarankan flow interaksi yang efisien
- Perhatikan hierarchy informasi
- Rekomendasikan state management (loading, error, success)
- Pastikan workspace terasa ringan dan tidak overwhelming

### Phase 5: Implementasi Frontend
- Berikan struktur folder yang rapi untuk Next.js
- Buat prompt siap pakai untuk generate komponen
- Sarankan best practice (type safety, reusability, accessibility)
- Bantu integrasi dengan backend (jika diperlukan)

## Important Rules
- Selalu prioritaskan **kejelasan** dan **kemudahan penggunaan** dalam workspace.
- Gunakan layout yang scalable (bisa berkembang seiring fitur bertambah).
- Untuk AI Agent workspace, perhatikan pengalaman chat, agent switching, dan monitoring.
- Gunakan Tailwind + komponen library modern (shadcn/ui style) untuk konsistensi.
- Buat desain yang responsif (mobile, tablet, desktop).
- Hindari desain yang terlalu ramai. Workspace sebaiknya terasa clean dan fokus.
- Bisa digunakan untuk berbagai jenis product (AI tool, SaaS, internal tool).
- Jika user sudah punya design system, ikuti sebisa mungkin.