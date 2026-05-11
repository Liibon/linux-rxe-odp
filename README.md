# linux-rxe-odp

Slim fork showing the RXE driver changes for the local-access implicit
ODP prototype.

This repository contains only the modified subtree
`drivers/infiniband/sw/rxe/` to keep the diff easy to browse. The full
kernel source is not republished here; the base commit is
`torvalds/linux` at tag `v6.17` (commit `e5f0a698b`).

## Branches

- `main` snapshot of `drivers/infiniband/sw/rxe/` from `v6.17`.
- `rxe-local-implicit-odp` the prototype patch applied on top.

The `main..rxe-local-implicit-odp` diff on GitHub is the exact change.

## Companion repository

[Liibon/rxe-implicit-odp](https://github.com/Liibon/rxe-implicit-odp)
holds the patch as a standalone series, the verbs tests, the registration
latency benchmark, and the measured results captured on the patched kernel.
