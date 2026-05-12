# linux-rxe-odp

Slim fork showing the RXE driver changes for local-access implicit ODP.

**Status: 2-patch RFC sent to linux-rdma 2026-05-12, awaiting review.**
- Cover: https://lore.kernel.org/r/20260512201453.21156-1-liibaegal@gmail.com

This repository contains only the modified subtree
`drivers/infiniband/sw/rxe/` to keep the diff easy to browse. The full
kernel source is not republished here; the base is `rdma/for-next` at
commit `7fd2df204f34` (Linux 7.1-rc2).

## Branches

- `main` snapshot of `drivers/infiniband/sw/rxe/` from `rdma/for-next` at 7.1-rc2.
- `rxe-local-implicit-odp` the 2-patch RFC applied on top.

The `main..rxe-local-implicit-odp` diff on GitHub is the exact change
sent upstream.

## Companion repository

[Liibon/rxe-implicit-odp](https://github.com/Liibon/rxe-implicit-odp)
holds the patches as a standalone series, the verbs tests, the
registration latency benchmark, and the measured results.
