# Daylor Williams

I build and evaluate AI agent systems, and I do ML research on vision-transformer representations. Cognitive Science (Computing specialization) at UCLA, graduating June 2027.

A major focus of my current work is agent evaluation: defining what correct behavior means when a system can reach the same result through different execution paths, and building the tooling to measure it.

## Current work

### [AgentTrace](https://github.com/daylorwilliams5/AgentTrace)

Independent project, in active development. A React and TypeScript developer tool for debugging AI agents by comparing two execution trajectories. Source is public and MIT licensed; write-up at [daylor.ai/agenttrace](https://daylor.ai/agenttrace).

- Normalizes traces into a common representation and aligns two runs using deterministic weighted Needleman-Wunsch sequence alignment.
- Produces field-level behavioral diffs, collapses identical regions, and surfaces the first observable divergence.
- Validated on real Claude Code sessions run as controlled pairs.

AgentTrace reports where two runs first differ in observable behavior. It does not determine root cause or explain why a run diverged.

### UCLA Technology Development Group

AI Product Intern. Building and evaluating a multi-stage agentic system for patent prior-art search.

- Core system work in Go, evaluation tooling in Python.
- Golden-case evaluation infrastructure using recorded responses and tolerance-based expected outputs.
- Failure and edge-case analysis feeding retrieval strategy, stopping conditions, and human-review boundaries.
- Interviews with patent evaluators and licensing officers to translate expert workflow into system requirements.

Source and data are internal to UCLA TDG and are not public.

### UCLA Computational Vision and Learning Lab

Representation analysis of DINOv3 vision-transformer embeddings in PyTorch, using subspace decomposition, PCA, LDA, and linear projections across 2,000+ synthetic images and 400 real-world objects.

For the vertical/horizontal spatial relation specifically, a linear probe reaches 97.9% mean leave-one-object-out accuracy across 400 held-out objects. This result is for that relation and does not extend to the other relations under study. Intervention experiments are in progress.

## Public repositories

[clip-binding-probe](https://github.com/daylorwilliams5/clip-binding-probe)
Where attribute binding appears and disappears inside CLIP's vision encoder, and whether a learned projection can recover it. Layer-wise probes with permutation tests and leave-one-shape-out evaluation. The finding is negative: the recovered signal is entangled with object identity and does not transfer to unseen shapes.

[grapes-search-plus](https://github.com/daylorwilliams5/grapes-search-plus)
Fellowship search over 363 records from the UCLA Division of Graduate Education dataset. Python extraction and enrichment pipeline that builds a dependency-free single-file HTML app. [Live demo](https://daylorwilliams5.github.io/grapes-search-plus/grapes-fellowship-finder.html).

## Technical

Languages: Python, TypeScript, Go, SQL

ML: PyTorch, vision transformers, representation analysis, linear probes, evaluation design

Agent systems: agent evaluation, trace comparison, sequence alignment, golden-case evaluation, failure analysis

Development: React, REST APIs, OAuth, DuckDB, Git

## Links

[daylor.ai](https://daylor.ai) · [LinkedIn](https://www.linkedin.com/in/daylor-williams-a87b0b27a/) · [daylor@daylor.ai](mailto:daylor@daylor.ai)
