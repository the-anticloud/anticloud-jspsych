# Students — JSPSYCH

**Project:** JSPSYCH  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/jspsych/jsPsych  
**Pinned commit:** `3e24c16c04dc3d2c6406c219126a9c9dc4737627`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c9b40e76d2b23916e3e704f839b48b4247a2a4ec1e1da1516076b916ea0c4d8`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `3e24c16c04dc3d2c6406c219126a9c9dc4737627`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `4c9b40e76d2b23916e3e704f839b48b4247a2a4ec1e1da1516076b916ea0c4d8`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
