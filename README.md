# DarkMark Tutorials

A living library of self-paced, deep-understanding courses. Each collection is built around a mission — a reason to learn — with beautiful, single-topic HTML lessons designed to be read, returned to, and built upon.

**[→ Browse the library](https://mlesk.github.io/darkmark-tutorials/)** (GitHub Pages)

---

## The Library

### ₿ [Learn Bitcoin](learn-bitcoin/)

Understand the Bitcoin transaction lifecycle end-to-end — from key generation and UTXO structure through signature, broadcast, mempool, mining, and final confirmation. Protocol-level depth for the curious developer.

**4 lessons** · accent: orange

### ⎇ [Learn Git Worktrees](learn-git-worktrees/)

Master git worktrees for parallel agentic coding — spin up isolated working directories per AI agent, share a single `.git` repository, and never accidentally step on your own state. Infrastructure for daily workflow.

**5 lessons** + glossary · accent: emerald

### ∑ [Learn Math for AI](learn-math-for-ai/)

Develop the linear algebra and probability depth to genuinely understand what AI systems do, where they fail, and how to think through approaches — grounded in the actual mathematics rather than marketing or vibes.

**15 lessons** across two pillars (linear algebra, probability) and a bridge (softmax), culminating in the full transformer architecture · accent: blue

---

## How It Works

This repository is built around the **teach** philosophy — every collection is driven by a mission, not a syllabus:

| Concept              | File                    | Purpose                                                                                                        |
| -------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Mission**          | `MISSION.md`            | Why you're learning — grounds every teaching decision                                                          |
| **Notes**            | `NOTES.md`              | Teacher scratchpad: your preferences, zone of proximal development                                             |
| **Resources**        | `RESOURCES.md`          | Curated high-trust sources (books, videos, papers, communities)                                                |
| **Lessons**          | `lessons/*.html`        | Self-contained HTML — one tightly-scoped thing per lesson. Beautiful typography, interactive where appropriate |
| **Reference**        | `reference/*.html`      | Compressed essence — cheat sheets, glossaries, quick-reference cards                                           |
| **Learning Records** | `learning-records/*.md` | ADR-style records capturing non-obvious insights and demonstrated competence                                   |

Knowledge comes from high-trust resources → skills come from interactive lessons → wisdom comes from community.

## Reading Locally

Every lesson is a standalone HTML file. Open any lesson in your browser:

```sh
open learn-git-worktrees/lessons/0000-git-worktrees-mental-model.html
```

Or start from the library landing page:

```sh
open index.html
```

No build step, no dependencies — pure HTML and CSS.

## Published as GitHub Pages

The library is published at **[mark.github.io/darkmark-tutorials](https://mlesk.github.io/darkmark-tutorials/)** via GitHub Pages. The root `index.html` is the library landing page. Each collection has its own index with the full lesson table of contents. Every lesson includes prev/next navigation to walk through the course in sequence.

To enable Pages on your own fork: **Settings → Pages → Source: Deploy from branch → `main` / root**.

## License

Public domain via [The Unlicense](LICENSE). All content is free to copy, modify, publish, use, or remix for any purpose.
