# Teaching Notes — Math for AI Literacy

## User Preferences

- **No coding.** Lessons should not involve writing or reading code. Mathematical notation, diagrams, and conceptual reasoning only.
- **No proofs.** Focus on intuition, geometric understanding, and applied reasoning. If a proof is the best way to convey understanding, include it — but never as an end in itself.
- **Visual-first.** Prefer geometric/diagrammatic explanations over algebraic manipulation. The user should be able to "see" what's happening.
- **AI-grounded.** Every concept should be tied back to a concrete AI application or question. If it doesn't help the user think about AI systems, it doesn't belong in a lesson.

## Zone of Proximal Development

- Baseline: single-variable calculus (derivatives, integrals, limits, chain rule) — comfortable but not expert.
- Starting point for linear algebra: vectors and matrices are new. Start with geometric intuition (vectors as arrows, matrices as transformations).
- Starting point for probability: basic probability (coins, dice, conditional probability) likely familiar but not formalized. Bayesian reasoning and continuous distributions are the growth edge.
- The user's calculus background means the continuous side of probability (PDFs, integration for expectation) is accessible but will need refreshing.

## Sequencing Principle

The entire course is structured as a **pyramid with the transformer at the top**. Lesson 0000 gives the big picture — what a transformer does and why each mathematical pillar matters. Every subsequent lesson explicitly traces back to the transformer: "Here's the piece of the puzzle you're building now."

The two pillars (linear algebra and probability) are developed in interleaved sequence, converging at Lesson 0012 (Softmax — the bridge) and Lessons 0013–0014 (Attention + Full Transformer). Each lesson opens with a "Puzzle Piece" callout that shows exactly where this concept fits in the transformer architecture.

**Lesson Sequence:**

- 0000: Transformer overview (north star)
- 0001–0006: Linear algebra pillar (vectors → matrices → multiplication → embeddings → projections → SVD)
- 0007–0011: Probability pillar (fundamentals → Bayes → distributions → entropy → KL)
- 0012: Softmax — the bridge where both pillars fuse
- 0013: Attention mechanism — the core innovation
- 0014: Complete transformer architecture + guided paper reading

## Glossary Note

Create GLOSSARY.md once the user has demonstrated understanding of at least 5-6 terms. Don't pre-populate it — glossary entries should be earned through demonstrated competence.
