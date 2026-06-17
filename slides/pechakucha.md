---
marp: true
paginate: true
transition: fade
auto-advance: 20
---

<!-- slide 1 -->
# Who's my person?

My relative — an adult Burmese speaker wanting better English for work and daily life.

**The challenge:** Every English app assumes you can already read English.

---

<!-- slide 2 -->
# Their problem

- Duolingo, Babbel → full English interface → lost before starting
- Translation apps → no structure, no progression
- Classes → too expensive, too rigid

**Gap:** No app that starts from Burmese and guides you toward English.

---

<!-- slide 3 -->
# What I built

**Pyaw (ပြော)** — *"to speak"*

A Burmese-first English learning web app:
- Lessons explained entirely in Burmese
- Vocabulary with pronunciation guides + Burmese translations
- Clean, minimal UI built for beginners
- Vue 3 + TypeScript + Vite

---

<!-- slide 4 -->
# How I built it

- **MCP:** Filesystem MCP reads/writes lesson JSON files in `src/`
- **Skill:** `vocab-builder` — generates vocabulary lists with Burmese translations and phonetics
- **Agent:** `lesson-planner` — designs full structured lessons from a topic

Claude Code handled content generation; I handled UI and routing.

---

<!-- slide 5 -->
# Why it matters

Burmese speakers are underserved in EdTech.

Pyaw lowers the barrier by letting learners start in **their own language** — not the one they are trying to learn.

Small project. Real person. Real need.

---

<!-- slide 6 -->
# Done checklist

- [x] repo public (github.com/earth957/earth957)
- [x] MCP configured (.mcp.json)
- [x] Skill added (.claude/skills/vocab-builder/)
- [x] Agent added (.claude/agents/lesson-planner.md)
- [x] report.md in team-10 repo
