# Ethics — NATIVESCRIPT

**Project:** NATIVESCRIPT  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `45b3b99afd89f19e799da84203aa19d673f7b20a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5d03a741bf094a2243895527b7cdb35e7a1926b96e3c91673dfb8aeacc751baf`  
**Date:** October 2026

## Position

NATIVESCRIPT is packaged for offline deployment with a verifiable audit trail. The
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
