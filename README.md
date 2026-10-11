# Yufeng Ying / 应宇峰

I work on GPU-accelerated real-time 3D reconstruction and C++ performance optimization.

Master's in Computer Science, University of Science and Technology of China (USTC).

## Godot

Godot contributor · [Merged PRs](https://github.com/godotengine/godot/pulls?q=is%3Apr+author%3AYYF233333+is%3Amerged)

Selected contributions:

- [Dictionary iteration](https://github.com/godotengine/godot/pull/104047): add const iteration and migrate resource, serialization and editor code; 725 → 271 ms in the PR's dictionary-iteration benchmark.
- [Header dependencies](https://github.com/godotengine/godot/pull/117087): separate type-conversion and method-binding headers; incremental rebuild after touching `binder_common.h`: 262 → 203 s in the PR's test.
- [Build size](https://github.com/godotengine/godot/pull/101964): use SizeBench to investigate inlining and add an optional size-focused build mode, with performance tradeoffs.

## Projects

| Project | About |
| --- | --- |
| [Lobotomy](https://github.com/vorton-lang/Lobotomy) | A personal experiment in human–agent collaboration: a persistent GUI workspace across coding harnesses. In development. |
| [Vorton](https://github.com/vorton-lang/vorton) | An in-development programming language and compiler, implemented in Rust and compiling to native programs through C11. |
| [AsGaLore](https://github.com/YYF233333/AsGaLore) | A research implementation extending GaLore with asynchronous CPU SVD offloading for memory-efficient LLM training. |
