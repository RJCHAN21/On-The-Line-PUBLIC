# On The Line

**On The Line** is a Unity game about surviving the pressure of a modern ISP call center. Manage a live queue of incoming support calls, make fast dialogue decisions, and complete troubleshooting minigames under a ticking shift timer. The challenge is not combat, but control: staying efficient, protecting KPI, and hitting quota before the workday falls apart.

## Overview

Set within a high-pressure support environment, **On The Line** turns the stress of real-time service work into a systems-driven gameplay loop. Every call competes for your attention. Leave customers waiting too long and urgency rises. Handle calls poorly and your performance slips. Stay sharp, prioritize well, and keep the shift under control long enough to make it to the end of the day.

## Features

- **Live call queue management** with escalating urgency
- **Dialogue-based issue triage** that affects call flow and outcome
- **Troubleshooting minigames** tied to customer service problems
- **KPI and quota tracking** built around a 5.0-based performance model
- **Shift progression** with rising pressure across multiple days
- **Failure and recovery flow** through end-of-day and game-over states
- **Desktop-style UI flow** built around fast player interaction

## Gameplay Loop

1. Calls enter the queue over time.
2. Waiting calls grow more urgent if ignored.
3. The player chooses which call to answer next.
4. A short dialogue phase helps identify the issue.
5. The player completes a troubleshooting activity to resolve the problem.
6. Performance updates based on speed, mistakes, and call quality.
7. The shift continues until the day ends, quota is met, or KPI breaks down.

## Core Design Focus

### Pressure Through Systems

The game creates tension through workload, prioritization, and time management rather than combat. Success depends on staying organized under pressure and making good decisions while the queue keeps moving.

### Readable, Playable Support Work

Instead of simulating support work passively, **On The Line** turns it into active gameplay. Queue handling, dialogue choices, and troubleshooting are all designed to feel immediate, readable, and gameable.

### Performance as Survival

The score is not just a reward layer. KPI, quota, and per-call outcomes are central to whether a shift remains manageable or begins to spiral.

## Current Content

The finished playable build includes:

- Real-time queue pressure
- Call aging and escalation states
- Dialogue-driven call handling
- Multiple troubleshooting puzzle types
- Per-call score pressure and mistake penalties
- Daily quota and KPI evaluation
- End-of-day summary flow
- Game-over summary flow
- Pause and app-style menu navigation

## Controls

- **Mouse:** Answer calls, navigate the UI, select dialogue, and interact with minigames
- **Keyboard:** `Escape` toggles the pause and app-close state

## Built With

- **Unity**
- Data-driven customer and issue setup
- Pooled spawning for incoming calls
- Gameplay-first systems focused on clarity, pressure, and replayable shift flow

## Project Status

**Status:** Finished playable project

**On The Line** is presented here as a completed game project. Future updates may improve polish, balancing, or presentation, but the core experience and intended gameplay loop are already in place.

## Why This Project Stands Out

**On The Line** explores a setting that games rarely center: the stress of customer support as the source of challenge. By turning queue pressure, troubleshooting, and performance management into gameplay, it creates a distinct form of tension built on mental load instead of physical action.

## Credits

### Developers
- Carlo Arañez
- Reginald Jervaise Chan
- Orlie Vincent Gendraule
- Xaviery Bonson Padaoan

### Minigames
- Orlie Vincent Gendraule

### Music & SFX
- Reginald Jervaise Chan

### Art Designer
- Carlos Alberto
- Xaviery Bonson Padaoan

### Fonts
- Tiny Worlds – Thaleah
- Nytrock – GNF

### Plugins
- Okitoki Games – EasyTalk Dialogue System
- The Naughty Cult – Hot Reload
- More Mountains – Feel

---
