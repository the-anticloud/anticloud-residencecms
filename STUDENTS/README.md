# Students — RESIDENCECMS

**Project:** RESIDENCECMS  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/Coderberg/ResidenceCMS  
**Pinned commit:** `e87f47341ce1ffe648e1de95ad70919df7f7e20c`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `588bfb23048dce746be18bc1d22663aaf5cbd80ab085775999c4afaaa5db3590`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e87f47341ce1ffe648e1de95ad70919df7f7e20c`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `588bfb23048dce746be18bc1d22663aaf5cbd80ab085775999c4afaaa5db3590`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
