<div align="center">

# BenchCAD

**Execution-grounded benchmarks for programmatic CAD** — evaluating whether
models can understand, generate, and edit the parametric programs behind real
mechanical parts.

[benchcad.com](https://benchcad.com) · [Benchmark & engine](https://github.com/BenchCAD/BenchCAD-main) · [Dataset](https://huggingface.co/datasets/BenchCAD/BenchCAD) · [Leaderboard](https://github.com/BenchCAD/BenchCAD-main/blob/main/LEADERBOARD.md)

</div>

## Official artifacts & roadmap

| Artifact | Status |
|---|---|
| **BenchCAD (1.0)** — 17,900 parts / 106 families / 4 tasks; scored by voxel IoU, no LLM judge | ✅ Released · frozen · cited in frontier-lab system cards |
| [benchcad.com](https://benchcad.com) · [HF dataset](https://huggingface.co/datasets/BenchCAD/BenchCAD) · leaderboard | ✅ Live |
| **BenchCAD 2.0** — agentic evaluation (tool use, execution feedback, multi-turn refinement) + dataset v2.0: community-grounded parametric designs | 🚧 In preparation — [development roadmap](https://github.com/BenchCAD-org/benchcad-2/issues/21) · [contribute a family](https://github.com/BenchCAD-org/benchcad-2/issues?q=is%3Aissue+is%3Aopen+label%3Afamily) |
| **BenchCAD-Agent** — reference agent & harness for BenchCAD | 📋 Planned |
| **BenchCAD-Assembly** — assembly-level CAD: multi-part assemblies, mating constraints | 📋 Planned ([reserved](https://github.com/BenchCAD-org/benchcad-assembly)) |
| **BenchCAD-Pro** — harder, contamination-resistant tier with private held-out evaluation | 📋 Planned ([reserved](https://github.com/BenchCAD-org/benchcad-pro)) |

## Naming policy

“BenchCAD” and the **BenchCAD-\*** prefix refer to official artifacts maintained
by the BenchCAD authors. If you build on BenchCAD, we'd love that — please:

- name derivative works ***X*-for-BenchCAD** (or similar), not *BenchCAD-X*;
- score with the official scorer and cite the paper (arXiv:2605.10865);
- want your variant to be **official**? Open an issue — collaborations are
  welcome and credited (co-authorship for substantial contributions).

Leaderboard numbers are re-graded by us from raw predictions — never
self-reported.
