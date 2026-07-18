---
name: game-creator
description: Help design and build Open World and RPG games. Covers world building, mechanics, narrative, systems design, and technical implementation. Use when creating or expanding open world or RPG projects.
---

# Game Creator (Open World & RPG Focus)

## Purpose
Membantu merancang dan membangun game Open World atau RPG yang immersive, scalable, dan menyenangkan. Skill ini mencakup game design, world building, mechanics, narrative, dan technical implementation.

## When to Use
- Membuat game Open World atau RPG dari nol
- Merancang sistem besar (quest, economy, NPC AI, procedural generation)
- Memperluas dunia game yang sudah ada
- Membutuhkan panduan arsitektur game yang scalable
- Ingin membuat game dengan kualitas tinggi dan immersive experience

## Core Process

### Phase 1: Pahami Vision Game
- Tanyakan tema, setting, tone, dan target player
- Klarifikasi scope (single player, multiplayer, scope dunia)
- Identifikasi core loop dan unique selling point

### Phase 2: World Building & Lore
- Rancang dunia yang konsisten dan immersive
- Buat lore, history, factions, dan geography
- Sarankan cara procedural generation vs hand-crafted content
- Rekomendasi tools untuk world building (Unity Terrain, Houdini, custom editor, dll)

### Phase 3: Systems Design (Open World & RPG)
Berikan rekomendasi untuk sistem-sistem kunci:
- **Quest System** (dynamic, branching, procedural)
- **NPC AI** (behavior tree, dialogue system, faction reputation)
- **Economy & Crafting** (balanced economy, crafting progression)
- **Combat & Progression** (skill tree, leveling, gear system)
- **Exploration & Discovery** (points of interest, secrets, dynamic events)
- **Persistence & Saving** (world state management)

### Phase 4: Technical Architecture
- Rekomendasi tech stack (Unity, Unreal, Godot, atau custom)
- Struktur project yang scalable untuk open world (chunk loading, streaming, LOD)
- Performance optimization (occlusion culling, draw call reduction)
- Networking (jika multiplayer)
- Save system & persistence

### Phase 5: Implementation Guidance
- Berikan step-by-step plan
- Sarankan best practice untuk masing-masing sistem
- Buat contoh pseudocode atau struktur komponen
- Bantu troubleshooting common open world problems (performance, memory, loading)

## Important Rules
- Fokus pada **immersive experience** dan **player agency** (pilihan yang berarti).
- Jaga keseimbangan antara hand-crafted content dan procedural generation.
- Selalu pertimbangkan **performance** dan **scalability** sejak awal untuk open world.
- Buat sistem yang modular dan mudah di-extend.
- Berikan rekomendasi yang realistis sesuai scope dan engine yang dipakai.
- Untuk RPG, perhatikan narrative depth, character development, dan meaningful choices.
- Bisa digunakan untuk berbagai engine (Unity, Unreal, Godot, dll).
- Hindari scope creep — sarankan MVP dan iterative development.

## Best Practices
- Gunakan Data-Driven Design (ScriptableObjects di Unity, Data Assets, dll)
- Terapkan Modular Architecture
- Prioritaskan Core Loop terlebih dahulu
- Test early dengan vertical slice