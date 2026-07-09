# Calibration Discussion Tool

**An interactive drag-and-drop facilitation tool for talent calibration meetings.**

🔗 **[Try the live demo →](https://ekronz123.github.io/Calibration-Discussion-Tool/)**

> ⚠️ This demo uses entirely synthetic/fictional data. No confidential information.

---

## What It Does

Transforms talent calibration discussions from spreadsheet chaos into a focused, interactive workspace:

- **Drag-and-drop** employee cards between Review Rating categories
- **Real-time distribution tracking** against target percentages with gap indicators
- **Cycle-over-cycle arrows** (↑↓) showing directional change in Performance, Potential, and LP
- **Interactive rating editor** — adjust ratings and the outcome auto-recalculates using the Q3 2026 "75 Blocker" grid
- **Facilitator tools** — countdown timer, full undo/revert history, per-employee notes with confidence tagging
- **One-click exports** — Excel with highlighted changes, email summary, printable Leader Doc
- **Zero dependencies** — single HTML file, opens in any browser

## How It Works

1. A Python script reads source Excel data (scenario planning spreadsheet)
2. It generates a self-contained HTML file with all employee data embedded
3. Open the HTML in any browser — no server, no install, no login
4. Facilitate the calibration discussion interactively
5. Export results when done

## Built With

- **Kiro** — the entire application (Python generator + HTML/CSS/JS front-end) was built conversationally with Kiro
- No frameworks, no npm, no build step — just Python + vanilla JavaScript

## Q3 2026 Framework

This tool implements the updated rating system:

| Code | Employee-Facing Label |
|------|----------------------|
| LE | Below Expectations |
| HV1 | Meets Most Expectations |
| HV2 | Meets Expectations |
| HV3 | Exceeds Expectations |
| TT | Significantly Exceeds Expectations |

Uses the "75 Blocker" grid logic where ~75% of grid positions result in outcomes at HV1 or above.

## PXT AI Challenge 2026

Built for the PXT AI Challenge. The goal: create a working app that solves a real problem, delivers a repeatable result, and could help anyone who picks it up.

This tool is in active use for real calibration discussions — the demo version shown here uses synthetic data to allow public sharing.
