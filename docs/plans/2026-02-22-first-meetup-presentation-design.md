# NSRT First Meetup Presentation Design

**Date:** 2026-02-22
**Event:** First NSRT offline meetup
**Duration:** ~2 hours (workshop format)
**Language:** Russian
**Audience:** Russian-speaking expats in Novi Sad (Luma RSVPs)
**Venue:** TBD

## Goals (equal weight)

1. **Vision** — Attendees understand what NSRT is and why it exists
2. **Needs discovery** — Collect real problems and desires from the community
3. **Empowerment** — Show that vibecoding with Claude Code makes building tools accessible to anyone

## Structure

### Act 1: The Why (~25 min, slides)

Frame the problem and present NSRT's vision.

1. **Title slide** — NSRT, date, location
2. **Icebreaker** — "How long have you lived in Novi Sad?" (show of hands: <1 year, 1-3, 3+)
3. **The problem** — We moved here. We have Telegram chats, but do we really know our neighbors? Isolation is the default.
4. **Nobody's coming** — No app, no government, no startup will fix this. Neighborhood tools are built BY the neighborhood.
5. **What is relational technology?** — Tech that strengthens bonds between people, not platforms that extract from them. Reference RTP.
6. **NSRT principles** — The 5 manifesto points (neighbor-to-neighbor, village-scale, small tools, remix, sovereignty)
7. **What already exists** — Dear Neighbors (Chrome extension, 111 countries), Community Admin (WIP), Events API, nsrt.netlify.app
8. **The ideas list** — Quick overview of categories (connection, mutual aid, culture, infrastructure). "Starting points, not a roadmap."

### Act 2: The What (~35 min, Harmonica session)

Structured deliberation to discover real community needs.

1. **Transition** — "Enough about what I think. Let's figure this out together." Briefly introduce Harmonica.
2. **Join** (~3 min) — QR code / link. Everyone joins on phones.
3. **Deliberation** (~15-20 min) — Prompt: "Think about your daily life in Novi Sad. What's one thing that would be easier if you and your neighbors had a simple tool for it? Describe the problem, not the solution." Participants type individually, read each other's responses.
4. **Live synthesis** (~5 min) — Harmonica synthesizes responses. Show on big screen. Powerful moment — the room sees its collective needs reflected back.
5. **Discussion + vote** (~10 min) — "Does this capture it? What's missing?" Then pick which need to prototype in Act 3.
6. **Bridge** — "You just experienced one tool I built with AI. Now let's build another one — for the problem you just picked — live."

### Break (~10 min)

### Act 3: The How (~50 min, live vibecoding)

Demonstrate that building tools is accessible by vibecoding a prototype from scratch.

1. **What is vibecoding?** (~5 min, slides) — Describe what you want in plain language, AI builds it. No programming required. Introduce Claude Code. "I need a volunteer with a laptop."
2. **Volunteer setup** (~10-15 min) — On volunteer's machine, screen-shared:
   - Install Node.js if needed
   - `npm install -g @anthropic-ai/claude-code`
   - `claude` — first launch, auth
   - Discuss cost ($20/month Pro) naturally during signup
   - Fallback: use presenter's laptop if setup hits a wall
3. **Live build** (~20-25 min) — Vibecode the prototype of the audience-chosen idea. Narrate throughout:
   - Natural language prompts (not code)
   - AI scaffolding files
   - First visual result in browser
   - Iteration ("this doesn't look right, let's change it")
   - Working prototype
4. **Deploy** (~5 min) — Ship to Netlify/Vercel. Share the live URL with the room.
5. **Reflection + closing** (~10 min) —
   - "[Volunteer] went from nothing installed to a live app in under an hour."
   - "You don't need to be a programmer. You need a problem and the willingness to describe it."
   - **Call to action:** Join Telegram group. Bring ideas. I'll help you get started with vibecoding.
   - Share the Harmonica synthesis link — input is captured, not lost.

## Risk Mitigations

| Risk | Mitigation |
|------|-----------|
| No volunteer has a laptop | Fall back to presenter's laptop, narrate as fresh start |
| Volunteer's OS has issues | Timebox setup to 15 min, pivot to presenter's machine |
| No one wants to buy subscription | Use presenter's account temporarily, or switch to own laptop |
| Audience idea too complex for 25 min | Simplify scope live — "let's start with just the core" (good teaching moment) |
| Harmonica session low participation | Have 1-2 seed responses ready; prompt verbally if people are hesitant |

## Pre-Meetup Action

Send a message via Luma to RSVPs:
- What NSRT is (1 sentence)
- Bring a laptop if you want to try building something
- Optionally pre-install Node.js (link to nodejs.org)
- No technical experience required

## Deliverables

1. **HTML slide deck** — Russian language, NSRT design system (navy/amber/cream), deployable as static page
2. **Harmonica session** — Pre-configured with the deliberation prompt
3. **Luma message** — Pre-meetup prep instructions for RSVPs
