# Ethics — JSPSYCH

**Project:** JSPSYCH  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/jspsych/jsPsych  
**Pinned commit:** `3e24c16c04dc3d2c6406c219126a9c9dc4737627`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c9b40e76d2b23916e3e704f839b48b4247a2a4ec1e1da1516076b916ea0c4d8`  
**Date:** October 2026

## Position

JSPSYCH is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
