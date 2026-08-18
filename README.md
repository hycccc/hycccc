# Yuchen Hu · 胡雨辰

Music data & evaluation at ByteDance Seed. Recording Arts, Shanghai Conservatory of Music.

## Selected work

| Project | What it shows |
|---|---|
| **[soundlabel](https://github.com/hycccc/soundlabel)** | Open-source framework for running an AI music label — `soundlabel demo` runs the full loop with zero API keys: A&R brief → generation → scoring gate → blind Critic verdict → catalog. The mothership the projects below plug into. |
| **[claude-oncall](https://github.com/hycccc/claude-oncall)** | Production sidecar pattern for the Claude Agent SDK: git-snapshot revert, context aggregation with freshness budgets, cost-annotated opt-in autonomy. |
| **[musicgen-if-eval](https://github.com/hycccc/musicgen-if-eval)** · [live demo](https://hycccc.github.io/musicgen-if-eval/) | Instruction-following evaluation workbench for text-to-music — a sanitized 1:1 replica of the production tool I built: requirement decomposition, PE attribution, synced A/B evidence-anchored judging. |
| **[audio-integrity-toolkit](https://github.com/hycccc/audio-integrity-toolkit)** | Acceptance-gate QC for audio datasets: fake-lossless detection via spectral cutoff, clipping, dynamic range. Extracted from a production ingestion pipeline. |
| **[songscore](https://github.com/hycccc/songscore)** | Three-tier quality scoring for generated songs — DSP rules, reward-model hook, and an anchored LLM judge whose discriminating power is guarded by dispersion regression tests. |
| **[data-mix-lab](https://github.com/hycccc/data-mix-lab)** 🚧 | Controlled data-composition experiments on an open video model — same base, same recipe, only the mix varies. The three-arm mix planner is shipped and property-tested. |
| **[liner-notes](https://github.com/hycccc/liner-notes)** | Personal-site template for musicians (extracted from [yuchenhu.com](https://yuchenhu.com)): music player, album *workshop*, travel map, agent-written blog. |


## How I work

- **Data foundations for music generation** — sourcing at the tens-of-millions-of-songs scale, acceptance pipelines (dedup / metadata-audio matching / lossless detection), LLM-as-judge + human-verification targeted sourcing
- **Structured music captioning** — section-level captions, ten controllable dimensions (vocals, instrumentation, genre, emotion, rhythm, melody, harmony, beat, BPM, time signature)
- **Evaluation systems** — genre-balanced benchmarks, CMOS/MOS human-eval operations, calibrating auto metrics against human gold: *auto metrics as guardrails, human eval as gold — every scorer has its own pop bias.*

## Elsewhere

- Website: [yuchenhu.com](https://yuchenhu.com)
- Instruments: saxophone, electric guitar, piano, wind synth — composition / arrangement / recording / mixing
