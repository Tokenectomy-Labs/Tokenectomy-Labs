# Tokenectomy Labs

> **Autonomous agent infrastructure studio & AI systems research lab.**  
> Architects of the Kronumos autonomous program repair engine and deterministic Sub-Cortex runtimes.

---

### 🔬 Core Architecture: Dual-Cortex Decoupling
Most autonomous coding agents fail due to token bloat and non-deterministic POSIX diff application. Tokenectomy Labs decouples probabilistic semantic reasoning from deterministic execution:

- **Neural Cortex:** Fine-tuned frontier and MoE models (Kairos, Metis, Aion) specialized in multi-file reasoning and root-cause synthesis.
- **Deterministic Sub-Cortex:** Safe, zero-allocation native Rust runtimes exposing a sub-5µs C-ABI for AST tree-sitter validation, terminal traceback sanitization, and diff re-anchoring.

### 📊 Benchmark & Empirical Rigor
- **SWE-bench Verified (Princeton Testbed):** Evaluated across 500 full instances under a blind, single-turn, zero-execution protocol.
- **Context Surgery:** Achieved a **93.5% token reduction** (averaging 2,512 tokens/task vs 38k+ raw tracebacks) at <$0.05 inference cost.
- **Preprints & Research DOIs:**
  - *CERN Zenodo:* [10.5281/zenodo.22929676](https://doi.org/10.5281/zenodo.22929676)
  - *Research Square:* [10.21203/rs.3.rs-11205335/v1](https://doi.org/10.21203/rs.3.rs-11205335/v1)

### 📦 Public Ecosystem
| Project | Distribution | Description |
| :--- | :--- | :--- |
| **Tokenectomy Razor** | Anthropic MCP, Crates.io, npm | Sub-millisecond M2M log cleaner & secret redaction sub-cortex |
| **tokenectomy-bot** | GitHub Actions / Native | Zero-LLM AST PR verification gate against test tampering |

---
*Maintained by Tokenectomy Labs Engineering Team • [kronumos.com](https://kronumos.com)*
