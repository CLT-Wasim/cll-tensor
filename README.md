# cll-tensor

**shape-typed tensors** — part of [CLL](https://github.com/CLT-Wasim/CLL), the Conserving Logic Language.

> Read [`AGENTS.md`](./AGENTS.md) first. It points at the binding rules; this README is only a summary.

## Purpose

`Tensor[dtype, ...]` shapes checked at compile time, fixed-point types `fx[I,F]`/`ufx[I,F]`, `quantize`, and the reversible block library used by the RevNet experiment.

## Status

Pre-v1. Nothing here is shipped until a command produced the result and the result is in a
results table with the command that produced it. See the milestone list in
[`ROADMAP.md`](https://github.com/CLT-Wasim/CLL/blob/main/ROADMAP.md).

## Layout

* `src/`
* `tests/`

## Language policy

CLL only. Tensors and fixed-point arithmetic are library code, not compiler magic.

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
