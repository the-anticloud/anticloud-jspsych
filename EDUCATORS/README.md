# Educators — JSPSYCH

**Project:** JSPSYCH  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/jspsych/jsPsych  
**Pinned commit:** `3e24c16c04dc3d2c6406c219126a9c9dc4737627`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c9b40e76d2b23916e3e704f839b48b4247a2a4ec1e1da1516076b916ea0c4d8`  
**Date:** October 2026

## Teaching with JSPSYCH

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `4c9b40e76d2b23916e3e704f839b48b4247a2a4ec1e1da1516076b916ea0c4d8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
