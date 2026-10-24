# The Whisperer

Privacy-first, non-generative AI for creative continuity in music production.

**Status:** Active prototype / independent R&D  
**Creator:** Monika Wiczewa  
**Domain:** AI × Music / Creative Technology  
**Source:** Development source is maintained privately.

## Creative continuity for music production

DAWs preserve audio and project state, but the reasoning around creative work can disappear between sessions: what the artist was trying, why a direction was chosen, what remained unresolved and what they intended to revisit.

The Whisperer explores how artists’ intentions, decisions and unfinished creative directions can be preserved across DAW sessions without assuming creative authorship. It provides a memory and context layer around music-production workflows, helping artists return to their own work with continuity.

## The central question

> Can AI preserve creative continuity without assuming creative authorship?

The project investigates how recorded session context and explicit artist-authored intentions can support recall over time. Observed activity and an artist’s stated intention remain distinct: activity alone does not establish what the artist meant or wanted.

## What the prototype explores

**Creative Session Memory** is a foundational capability within The Whisperer. The current working prototype brings together:

- Read-only observation of authorised DAW/session activity.
- Persistent session memory and artist-authored contextual notes.
- Explicit unfinished intentions, with resolution and history.
- Evidence-backed recall and session re-entry.
- Provenance-aware records that retain the source of recalled context.
- Optional local language-model assistance for retrieval and evidence selection, with deterministic fallback.
- Local audio measurements, kept separate from creative judgement.
- Local-first handling of artist data.

Two questions guide the experience:

> “Where was I?”  
> “What was I going to do next?”

Answers retrieve and reconstruct recorded context and explicit intentions. They do not claim access to unrecorded thoughts or independently infer the artist’s creative goals.

## Example workflow

*Illustrative workflow; the note below is an example, not a published artist recording.*

**Session 1**

The artist works normally in the DAW while The Whisperer observes authorised session context. The artist explicitly records an intention:

> “Chorus feels crowded. Revisit the guitars tomorrow.”

The session ends, with that intention still unresolved.

**Session 2**

The artist returns and asks **“Where was I?”** The Whisperer recalls relevant recorded session context. When asked **“What was I going to do next?”**, it retrieves the unresolved artist-authored intention.

The artist decides how to proceed and may later mark the intention resolved. The system preserves the intention; the artist supplies it and makes the musical decisions.

## Human authorship by design

**The AI remembers the artist’s recorded intentions. It doesn’t invent them.**

The Whisperer supports memory, context and continuity. It does not compose music, generate songs, automatically arrange or autonomously mix a session. It does not make hidden changes to the DAW or take creative decisions on the artist’s behalf.

The human remains the creative decision-maker.

## Current prototype

A working prototype exists, with **REAPER as the current development and test DAW**. It demonstrates Creative Session Memory through read-only session observation, explicit notes and intentions, provenance-aware recall and local audio measurements.

An optional local language-model layer assists retrieval and evidence selection. The recall workflow also supports deterministic operation without a language model. No model generates music.

REAPER is the present implementation environment; The Whisperer’s broader direction is DAW-integrated creative assistance. **Pro Tools is a longer-term intended integration direction. A working Pro Tools integration is not currently implemented.**

The prototype is under development. Hands-on artist-session rehearsal and validation on the creator’s Windows setup remain ongoing work. It is not presented as a commercially deployed or research-validated product.

## Research and design direction

The project connects human-centred AI, creative memory and longitudinal context with artist agency, provenance and privacy. Its focus is responsible assistance that supports an artist’s own process and preserves the distinction between recorded evidence, stated intention and creative judgement.

## Development status

The Whisperer is under active independent development. Its implementation repository is private and proprietary.

This public showcase documents the project’s purpose, current scope and selected public-facing material. It is not an open-source software release. Public demonstration material may be added here following review.

<!-- Future reviewed public demo material can be added beneath this section. -->

## About the creator

**Monika Wiczewa - AI Engineer / Creative Technologist**

- **MSc Computer Science (Artificial Intelligence: Speech & Language Processing)** - University of Sheffield; Distinction, awarded 2026.
- **BA (Hons) English Language & Linguistics** — University of Sheffield, 2019.

Her work sits at the intersection of AI, language, music and creative technology, with a particular interest in human-centred AI and systems that augment human creativity.

## Links

- [GitHub profile](https://github.com/monikawiczewa)
- [LinkedIn](https://www.linkedin.com/in/monika-wiczewa-9771771a3/)

© 2026 Monika Wiczewa. All rights reserved.
