# Mathematics for AI Literacy — Resources

## Knowledge

### Linear Algebra

- [Book: _Linear Algebra and Its Applications_ — Gilbert Strang (5th ed.)](https://math.mit.edu/~gs/linearalgebra/)
  The canonical applied linear algebra text. Strang emphasizes geometric intuition over proof. Use for: building intuition about vector spaces, matrices as transformations, eigenvalues, SVD. Chapters 1–7 cover everything needed.

- [Video: MIT 18.06 Linear Algebra — Gilbert Strang (OCW)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
  The legendary lecture series. Strang's blackboard lectures are unmatched for building visual understanding. Use for: primary learning — watch before reading the corresponding book chapter.

- [Video: _Essence of Linear Algebra_ — 3Blue1Brown (YouTube playlist)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
  15 animated shorts (~15 min each) that build geometric intuition for vectors, matrices, determinants, eigenvalues, and abstract vector spaces. Use for: first-pass intuition before diving into formal material. Best consumed over a weekend.

- [Article: _The Matrix Calculus You Need For Deep Learning_ — Terence Parr & Jeremy Howard](https://explained.ai/matrix-calculus/index.html)
  Compact reference for the matrix derivatives that show up in backpropagation. Use for: bridging linear algebra to how neural networks actually learn. Read after mastering matrix multiplication and the chain rule.

### Probability & Statistics

- [Book: _Introduction to Probability_ — Blitzstein & Hwang](https://probabilitybook.net/)
  Rigorous but intuitive introduction to probability, with strong emphasis on conditioning and Bayesian reasoning. Use for: building probabilistic thinking from the ground up. Chapters 1–9 cover the core.

- [Video: Statistics 110: Probability — Joe Blitzstein (Harvard, YouTube)](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
  Lectures that pair with the Blitzstein & Hwang book. Blitzstein is a gifted explainer. Use for: primary learning alongside the book.

- [Video: _Bayes Theorem_ — 3Blue1Brown (YouTube)](https://www.youtube.com/watch?v=HZGCoVF3YvM)
  The single best 15-minute explanation of Bayes' theorem and why it matters. Use for: the moment when Bayesian reasoning clicks.

- [Book: _Probability and Statistics for Computer Scientists_ — Michael Baron (2nd ed.)](https://www.routledge.com/Probability-and-Statistics-for-Computer-Scientists/Baron/p/book/9781439875902)
  Probability and statistics with a CS/engineering orientation. Covers simulation, bootstrap, and ML-relevant topics. Use for: a second perspective when Blitzstein feels too abstract — this book connects probability to computation.

### Connecting Math to AI

- [Article: _Attention Is All You Need_ — Vaswani et al. (arXiv)](https://arxiv.org/abs/1706.03762)
  The transformer paper. Dense but readable with solid linear algebra and probability. Use for: the capstone — read this after building competence in both pillars and see how they fuse into a working system.

- [Article: _An Interactive Guide to the Fourier Transform_ — BetterExplained](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/)
  Not directly about AI, but Fourier transforms build intuition for why certain representations (bases, decompositions) are powerful — a bridge from linear algebra to signal processing to embeddings.

- [Book: _Pattern Recognition and Machine Learning_ — Christopher Bishop](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/)
  The classic ML text. Heavy but rewarding. Use for: reference — dip into specific chapters (2: Probability Distributions, 3: Linear Models for Regression, 12: Principal Component Analysis) once the foundations are solid.

### Background / Warmup

- [Video: _The Essence of Calculus_ — 3Blue1Brown (YouTube playlist)](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
  Refresher if single-variable calculus is rusty. Use for: making sure derivatives and integrals are intuitive before applying them in probability and optimization.

## Wisdom (Communities)

- [r/learnmath](https://reddit.com/r/learnmath)
  High-quality, well-moderated community for math learners. Use for: getting unstuck on specific concepts. Search before posting — most linear algebra and probability questions have been answered.

- [r/MachineLearning — "Simple Questions" thread](https://reddit.com/r/MachineLearning)
  The weekly simple questions thread is surprisingly welcoming to conceptual questions. Use for: asking "why does X work?" questions that bridge math to AI.

- [Mathematics Stack Exchange](https://math.stackexchange.com/)
  For precise, well-posed questions about specific mathematical concepts. Higher bar for question quality than Reddit, but answers are correspondingly rigorous.

## Gaps

- **No single resource connects linear algebra + probability to transformer/generative AI architecture in a math-first but code-free way.** Most AI explainers either skip the math (too shallow) or dive into PyTorch (too implementation-heavy). We will need to bridge this gap through lessons that build the connection directly.

- **Resources on "AI literacy for decision-makers" tend to be math-free and thus shallow.** The niche of "enough math to think critically, not enough to build" is underserved. This is the gap this teaching workspace targets.
