# Forext

> A context forest — where knowledge grows in relation, not in isolation.

Forext is a personal knowledge system built around the idea that **context is the unit of meaning**. Notes don't exist alone; they exist in relation to one another. The connections between ideas are as important as the ideas themselves.

Where a digital garden is tended and curated, a forest grows dense and interconnected. Every node in Forext is not just content — it is context.

## Concept

A forest has no single root. It's a distributed network of growth where each tree shapes and is shaped by its neighbors — light, soil, root systems all shared. Forext applies this model to knowledge:

- **Nodes** are individual notes, concepts, or observations
- **Edges** are the links between them — explicit connections that carry meaning
- **The graph is the forest** — the living map that makes context visible at a glance

The graph visualization is the primary interface. It sits above every note, showing where you are in the forest before you read what the note says.

## Structure

```
content/      — source notes (Markdown / Obsidian)
quartz/       — underlying engine (Quartz v4)
quartz.config.ts   — site configuration
quartz.layout.ts   — layout and component arrangement
```

## Running locally

```bash
npx quartz build --serve
```

## Built on

Forext is a fork of [Quartz v4](https://quartz.jzhao.xyz/) by jackyzha0 — a static site generator for Obsidian notes and digital gardens. The core rendering engine, plugin system, and graph component are all Quartz. Forext is the configuration, philosophy, and content layer on top.
