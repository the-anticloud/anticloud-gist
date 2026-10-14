# Educators — GIST

**Project:** GIST  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/semanticarts/gist  
**Pinned commit:** `4669a16af13ca30be27cb1fecd2176fe120af899`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5b739de3fda0e339b84ae835dc53838704d26c32e2f244c2bd89597a89a4aec1`  
**Date:** October 2026

## Teaching with GIST

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5b739de3fda0e339b84ae835dc53838704d26c32e2f244c2bd89597a89a4aec1` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
