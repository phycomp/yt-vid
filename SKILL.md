---
name: yt-vid
description: Video production skill for YouTube content — covers content planning, script writing (two-column AV), storyboard/shot list, batch shooting, SEO (title/tags/description), 10-minute video structure, production workflow, and publishing checklist. Use when the user asks about video production, video scripts, storyboards, shot lists, YouTube SEO, content planning, or publishing workflow. Not for quant trading strategy (see quant-algo-auto).
---

# YouTube Video Production

End-to-end video production skill for YouTube content — from content planning through script writing, storyboard, shot list, batch shooting, SEO, and publishing.

## When to Use

- Planning video content (topics, calendar, pillars)
- Writing video scripts (two-column AV, hooks, CTAs)
- Creating storyboards and shot lists
- Batch shooting / filming plans
- YouTube SEO (title, tags, description, thumbnail)
- Production workflow (weekly schedule)
- Publishing checklist

## Core Principle

**Videos are won in pre-production.** The cheapest edit is on paper. A words-only script plans half the video; the visual half gets improvised. Write what's seen, beat by beat.

## Content Pillars

Define 3-4 content pillars for your channel. Example for a finance/quant channel:

| Pillar | Focus | Example Topics |
|--------|-------|----------------|
| **Backtesting & Validation** | Walk-forward, overfitting, Monte Carlo | "How to avoid overfitting" |
| **Strategy Implementation** | Code walkthroughs, tutorials | "Backtest a dual MA in 10 min" |
| **Risk & Position Sizing** | Kelly, drawdown, correlation | "Kelly Criterion: formula to code" |
| **Market Microstructure** | Slippage, fees, factors | "How slippage eats your alpha" |

## 10-Minute Video Template

```
0:00-0:30  Hook (problem/pain point, specific number)
0:30-1:30  Concept (1 core idea)
1:30-6:00  Code demo (screen recording, step-by-step)
6:00-8:00  Results + common pitfalls
8:00-9:00  Summary + next week preview
9:00-10:00 CTA (subscribe/comment/download code)
```

## Two-Column AV Script

Every script has two columns: **Audio** (what's said) and **Visual** (what's shown).

| Audio (VO/SFX) | Visual (Action/Shot) |
|----------------|----------------------|
| [VO] Hook line | Title card + B-roll |
| [VO] Concept explanation | Diagram animation |
| [VO] Code walkthrough | Screen recording |
| [SFX] Sound effect | Transition |
| [Action] Cut to camera | Talking head |

Rules:
- If the visual isn't written, it will be improvised
- No "me talking" twice in a row — plan visual variety
- Runtime math: ~130-150 wpm → 300 words ≈ 2 min video

## Storyboard (Decision Document, Not Art)

The storyboard answers one question: **"What's on screen at this beat?"**

Forms (cheapest first):
1. **Shot table** — beat, visual, duration, notes
2. **Stick figures** — rough sketches
3. **AI previz frames** — character-consistent boards (2026: 12 frames in 40-60 min)

Skip boards where a shot list suffices. For AI video, each panel = the shot brief.

## Shot List & Batch Shooting

Number every shot. Then **regroup by setup** (location/framing/outfit), not by video order. This enables batch shooting — two weeks of content in one afternoon.

Label footage: `vid#-shot#` for easy identification.

## SEO & Publishing

### Title Formula
`[Concept] + [Tool] + [Promise/Result]`
- "Walk-Forward Optimization: Validate your strategy with Python"
- "Kelly Criterion in algorithmic trading: from formula to code"

### Tags (5-8 per video)
Mix broad + specific: `quantitative trading`, `algorithmic trading`, `Python`, `backtesting`, `vectorbt`

### Description (200+ words)
- Keyword in first 2 lines
- Links, timestamps, chapters
- Call to action

### Thumbnail
- 1280x720, high contrast
- Face + text + emotion
- Test at small size

## Production Workflow (Weekly)

| Day | Task |
|-----|------|
| Mon | Topic selection + script outline + code |
| Tue | Record code demo + narration |
| Wed | Edit + subtitles + thumbnail |
| Thu | Review + schedule (publish Fri 18:00) |
| Fri | Publish + community engagement |

## Publishing Checklist

- [ ] Script written (Hook → Concept → Code → Results → CTA)
- [ ] Code tested and reproducible
- [ ] GitHub repo updated with code + notebook
- [ ] Thumbnail designed (1280x720)
- [ ] Title < 70 chars with keyword
- [ ] Description 200+ words
- [ ] Tags 5-8
- [ ] Subtitles added
- [ ] Scheduled for Friday 18:00
- [ ] Community post / teaser prepared

## KPIs (review every 4 weeks)

| Metric | Target |
|--------|--------|
| CTR (click-through rate) | > 5% |
| AVD (average view duration) | > 50% (10 min → 5+ min) |
| Subscribe conversion | > 2% |
| Comment rate | > 1% |

## Differentiation

- **Research hygiene**: emphasize "how to validate" not "what to buy"
- **Reproducible code**: every video links to GitHub repo
- **Honest results**: show real slippage/fees/overfitting
- **Chinese market**: first-mover advantage in niche topics

## Guardrails

1. Never present backtested returns as guaranteed future performance.
2. Always disclose limitations (overfitting, survivorship bias, look-ahead).
3. Never recommend specific stocks/securities as investment advice.
4. Always include risk disclaimers in video content.
5. Paper trade before live trading; start small.

## References

- `scripting-and-storyboarding` skill — SCENE framework for pre-production
- `ffmpeg-transitions-effects` skill — FFmpeg transition recipes
- `youtube-analytics` skill — YouTube Data API analytics
- `social-media-skills/skills@scripting-and-storyboarding` — scripting + storyboarding
