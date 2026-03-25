# On The Line

**On The Line** is a Unity prototype about surviving the pressure of a modern ISP call center. Players work through a live queue of support calls, triage customer issues, make fast dialogue decisions, and complete troubleshooting minigames under a ticking shift timer. The challenge is not combat, but control: staying efficient, protecting KPI, and meeting quota before the workday collapses.

## Project Status

**Current state:** Playable prototype

The current build already supports the core gameplay loop, including:

- Real-time call queue management
- Call aging and urgency escalation
- Dialogue-driven issue triage
- Troubleshooting minigames
- KPI and quota-based performance tracking
- Shift progression, failure states, and next-day flow

Presentation, narrative polish, long-term progression, and some content layers are still in progress.

## Core Premise

You play as an ISP support agent trying to survive a full shift without being overwhelmed by incoming requests. Every call adds pressure to the queue, and every second spent on one customer affects the rest. To succeed, you need to balance urgency, response quality, and speed while keeping performance above the threshold for termination.

## Core Gameplay Loop

A typical session flows like this:

1. New customer calls enter the queue over time.
2. Waiting calls become more urgent the longer they are ignored.
3. You choose which call to answer next.
4. A short dialogue phase helps identify the issue and shape customer satisfaction.
5. The call moves into a troubleshooting minigame tied to the customer’s problem.
6. Your performance updates based on speed, mistakes, and overall call quality.
7. The shift continues until the day ends, you meet quota, or your KPI collapses.

## Core Systems

### Live Queue Pressure

Calls are not static tasks. They age in real time, escalate in urgency, and can eventually drop entirely if left unresolved for too long. This creates constant pressure to prioritize the right problem at the right time instead of simply clearing one call after another.

### Dialogue Triage

Each call begins with a short conversational phase where the player quickly identifies the issue and manages the interaction. Dialogue choices influence call quality, shaping how smoothly the customer reaches resolution.

### Troubleshooting Minigames

Resolved calls are not handled through menus alone. The prototype currently supports multiple troubleshooting activities, including signal-routing and network-guidance style puzzles, turning service work into active problem-solving rather than passive clicking.

### KPI and Quota Management

Performance is measured through a 5.0-based per-call score, overall KPI pressure, and a daily quota target. Mistakes, delays, dropped calls, and poor call handling all make recovery harder, while strong performance helps stabilize the shift.

### Day Escalation

As days progress, the game increases pressure through harsher requirements and tougher failure conditions. Spawn pacing, quota demands, and penalties ramp up to make later shifts feel more demanding than the first.

## What Makes the Game Distinct

**On The Line** translates workplace pressure into game systems. Its tension comes from queue escalation, decision-making, and time-sensitive troubleshooting rather than traditional combat or action mechanics. The result is a systems-driven experience built around urgency, consistency, and the feeling of trying to stay afloat during an overloaded shift.

## Current Features in the Prototype

- Shift-based gameplay structure
- Escalating incoming call queue
- Priority and aging states for unattended calls
- Dialogue choices that affect call outcome
- Multiple troubleshooting puzzle types
- Per-call score decay and mistake penalties
- KPI-based fail states
- End-of-day summary and next-day progression
- Game-over summary flow
- Pause and desktop-style UI navigation

## Controls

- **Mouse:** Answer calls, navigate UI, select dialogue, and interact with puzzle elements
- **Keyboard:** `Escape` toggles the in-game pause/app-close state

## Technical Snapshot

- Built in **Unity**
- Uses a pooled call-spawning system for incoming requests
- Driven by customer and issue data assets
- Designed as a prototype with gameplay systems already wired before final presentation polish

## Scope Notes

This README reflects the project’s current playable prototype state. It focuses on gameplay that is already supported by the existing implementation and avoids presenting unfinished content as complete. Narrative depth, art/audio orchestration, and longer-term campaign structure are still evolving.

---

This version of the README is based on the repo-grounded implementation summary provided from the current project audit, with public-facing wording layered on top for clarity and presentation.
