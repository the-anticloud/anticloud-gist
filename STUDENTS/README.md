# Students — GIST

**Project:** GIST  
**Category:** PHILOSOPHY_SEMANTICS  
**Upstream:** https://github.com/semanticarts/gist  
**Pinned commit:** `4669a16af13ca30be27cb1fecd2176fe120af899`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5b739de3fda0e339b84ae835dc53838704d26c32e2f244c2bd89597a89a4aec1`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4669a16af13ca30be27cb1fecd2176fe120af899`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5b739de3fda0e339b84ae835dc53838704d26c32e2f244c2bd89597a89a4aec1`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
