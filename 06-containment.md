---
title: Containment Online
description: A browser-based, point-and-click sci-fi MMO with a fully 3D voxel world
date: 11-07-2026
slug: containment
excerpt: A server-authoritative browser MMO set inside a containment facility, rendered entirely from procedural voxels with Three.js
tags: [TypeScript, Three.js, Node.js, WebSocket, SQLite, Kubernetes]
github: https://github.com/aidenharwood/portfolio-node-containment
demo: https://containment.aidenharwood.uk
featured: true
---

# Containment Online

A browser-based, point-and-click sci-fi MMO set inside a containment facility run by the Meridian Directorate. The world is fully 3D, built from voxels at runtime, with a freely orbiting camera, click-to-walk movement and context-menu interactions.

## Features

- **Server-authoritative**: clients only send intents; a 300ms tick validates, simulates and broadcasts every outcome
- **Skills, not classes**: characters differ only cosmetically, and every stat derives from trained skills plus gear
- **Combat**: tick-based melee and ranged combat with aggro, leashing, loot tables, respawns and visible projectiles
- **Gathering and crafting**: every piece of gear and every healing item can be gathered, refined and made
- **Quests and dialogue**: a data-driven quest engine with conditional dialogue trees and effects
- **Built for crowds**: zone layers with overflow copies, single-way combat and shared credit in multi-combat areas
- **Procedural art**: no model or texture assets; characters, creatures, items and icons are all built from voxels

## Technology Stack

- **Client**: TypeScript, Three.js, Vite
- **Server**: Node.js 24 running TypeScript directly, WebSocket (`ws`), zod-validated protocol
- **Persistence**: `node:sqlite`
- **Infrastructure**: Docker, Kubernetes, Helm, ArgoCD, Traefik
