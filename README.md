# On The Line

**On The Line** is an in-development pressure-management game about working as a support agent at a modern internet service provider. Set inside a fast-moving call center workflow, the game challenges players to juggle incoming calls, respond under pressure, and solve network-related service problems before situations spiral out of control.

At its core, the game blends **queue management**, **rapid dialogue decisions**, and **technical problem-solving** into a single shift-based experience. Players must decide which calls to take, navigate short customer interactions, and complete issue-resolution sequences tied to network guidance and signal restoration. Every decision affects performance, response time, and the ability to stay ahead of an escalating workload.

The project is built around the idea of turning customer support pressure into readable, gameable systems. Rather than focusing on combat or traditional action mechanics, *On The Line* creates tension through rising urgency, limited time, and the constant risk of falling behind. A full shift becomes a test of prioritization, consistency, and efficiency.

## Project Status

This project is currently in development. Systems, balancing, and presentation are still being refined.

## Core Premise

You play as an ISP support agent trying to survive a full work shift while maintaining performance targets. Calls continue to arrive throughout the day, each with its own urgency and service issue. If too many calls are ignored, mishandled, or resolved too slowly, overall performance drops and the shift becomes harder to recover.

## Core Gameplay Pillars

### 1. Queue Pressure
Incoming calls escalate over time. Players must decide what to handle first and prevent high-priority calls from being neglected.

### 2. Customer Interaction
Each selected call begins with a short dialogue phase where players choose quick responses to identify the issue efficiently.

### 3. Technical Resolution
After identifying the problem, players complete one of the game’s service-repair activities, such as guiding a connection route or restoring a signal path.

### 4. Performance Management
The game tracks handling speed, dropped calls, and shift progress. Success depends on maintaining control under pressure rather than solving only one problem at a time.

## Current Gameplay Structure

A typical play loop looks like this:

1. New calls enter the queue.
2. Existing calls escalate if left waiting.
3. The player selects a call to answer.
4. A short customer interaction phase plays out.
5. The player resolves the associated service issue.
6. Performance updates and the player returns to the queue.
7. The shift continues until the workday ends.

## Systems Featured in the Design

- Escalating call queue states
- Fast-paced call introduction dialogue
- Multiple issue-resolution minigame types
- Per-call handling timer with pressure states
- Shift-length session structure
- Quota and KPI-style performance tracking
- Risk-reward decision-making around continuing past quota

## Design Goals

The project aims to:

- Translate the stress of real-time support work into interactive gameplay
- Make pressure and prioritization the main source of challenge
- Combine decision-making and puzzle-solving in a readable loop
- Build tension through workload escalation instead of combat

## Notes

This README is currently written as a public-facing overview. It intentionally stays high level and avoids implementation-specific details that should be filled in later from the live project codebase.
