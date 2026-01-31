# Sentient Fields (Working Title)
A 2D top-down farming / strategy sim where crops are sentient: they can cooperate with the player or organize against them.

---

## High-Level Constraints (Locked for v0)
- [ ] **2D top-down**
- [ ] **Single-player**
- [ ] **Python-only**
- [ ] Keep scope small: prototype-first, content later

---

## Phase 0 — Vision & Scope (No Code)
- [ ] Write a **1-paragraph pitch**
      There is an arcane energy in the soil. Harness it, and your harvest will be bountiful. Be careful, as inadequate care will lead to you and your farm's demise. A witch has cursed these lands, infusing the flora growing from their soil with an unexpected life force. Each plant species provides unique utility, or destructive hindrance to your farm.
      
- [ ] Define the **player fantasy**: “I am a ___ managing ___ while ___.”
- [ ] Define **what success looks like** (win condition or long-term goal)
- [ ] Define **how you fail** (bankrupt? collapse? revolt?)
- [ ] Write 3 “**This game is NOT**” statements (anti-scope-creep)

---

## Phase 1 — Core Loop (Paper Design)
- [ ] Draft the **daily gameplay loop**
  - Wake → plan → farm actions → consequences/events → end day
- [ ] List the **top 5 player actions**
  - e.g., plant, water, harvest, build, negotiate
- [ ] Decide what “**progression**” means
  - land expansion, tools, reputation, crop relations, tech tree, etc.

---

## Phase 2 — The Sentient Crop System (The Hook)
- [ ] Define what crops **want** (needs/values)
  - Examples: water, sunlight, rest, “fairness,” autonomy, safety
- [ ] Define 3 crop **moods/states**
  - e.g., Content → Frustrated → Organizing → Striking
- [ ] Define **triggers** for cooperation vs unionization
  - What player choices raise/lower “organizing pressure”?
- [ ] Define **player responses**
  - negotiate, compromise, suppress, incentives, reforms, etc.
- [ ] Define consequences of escalation
  - slowdowns, sabotage, refusal to harvest, spreading unrest, etc.

---

## Phase 3 — Systems List (Keep It Minimal)
Create 1–2 sentences for each.
- [ ] Farming system (tiles/plots, seasons?)
- [ ] Economy (money, costs, sales)
- [ ] Crafting/building (structures/tools)
- [ ] Events (random + scripted)
- [ ] NPCs (optional for later)
- [ ] Save/load (later)

---

## Phase 4 — Content Planning (Small & Expandable)
- [ ] Define 5 starter crop types
- [ ] Define 10 starter events
  - 4 neutral, 3 positive, 3 conflict
- [ ] Define 3 factions/archetypes of crops (optional)
  - e.g., “Traditionalists,” “Radicals,” “Pragmatists”

---

## Phase 5 — Tech Decisions (Still No Big Build)
- [ ] Choose framework: **Arcade** or **pygame-ce**
- [ ] Decide world representation:
  - [ ] Tile grid size (e.g., 32px tiles)
  - [ ] Chunking? (later)
- [ ] Decide data format for content (JSON recommended)
- [ ] Repo structure draft:
  - [ ] `/src`
  - [ ] `/docs`
  - [ ] `/assets`
  - [ ] `/tests` (optional early)

---

## Collaboration (GitHub)
- [ ] Define roles (rotating is fine)
  - Design lead / systems, engineering, content, art placeholder, etc.
- [ ] Agree on workflow
  - main branch protected, PRs for changes, issues for tasks
- [ ] Create labels:
  - [ ] `design`
  - [ ] `tech`
  - [ ] `content`
  - [ ] `good first task`
  - [ ] `bug`
- [ ] Add an `IDEAS.md` dump file (no judgment, just capture)

---

## First Prototype Target (When We’re Ready)
**Goal:** a tiny playable loop, not a full game.
- [ ] Move around a small map
- [ ] Place a crop
- [ ] Advance “day” and update crop state
- [ ] Show one consequence of “mood” changing
