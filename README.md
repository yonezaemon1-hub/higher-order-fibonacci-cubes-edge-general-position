# Exact edge general position numbers of higher-order Fibonacci cubes

Ryutaro Yonezu (Independent Researcher), v1.0, 2026-11-19.

For integers k >= 3, n >= 2, let A_n^(k) count binary words of length n with no k consecutive ones, A_0=1. The analytic proof establishes gp_e(Q_n(1^k)) = 2(A_n^(k)-A_(n-1)^(k)). For n >= k+1 the unique maximum edge general position set is Theta_1 union Theta_n; for 2 <= n <= k precisely the unions of two distinct complete coordinate classes are maximum. No assertion for k=2 or cyclic/spacing variants.

**Preprint. NOT HUMAN PEER REVIEWED.** Independent AI audit: **THEOREM CONDITIONAL PASS / UNIQUENESS CONDITIONAL PASS** (auditor's PUBLICATION HOLD was an authorization/review status; author has conditionally authorized this release). NOVELTY INCONCLUSIVE / REFERENCES PARTIAL. All rights reserved. No open license.

The theorem has an analytic proof. Finite computations are corroborative. The audit record is an author-provided full-response transcription; independent verbatim comparison with the source chat was not performed and the auditor’s checking code was not obtained. Read No77_v1.0.pdf or No77_v1.0.tex. Extract No77_v1.0_repro.zip, then run `python -B -I verify.py` in that directory (Python 3.10+, standard library) and compare to EXPECTED_RESULTS.txt. The verifier is byte-identical to the frozen v0.1 source. See SHA256SUMS.txt for distribution hashes. Private audit text, Windows logs and handoff material are not distributed.

Preliminary context: Klavžar–Tan (2023), DOI 10.1007/s40840-023-01517-y, studies ordinary Fibonacci/Lucas cubes; Wei–Yang, arXiv:2601.17273, and Mollard, arXiv:2507.16387, study higher-order counting. This is not an exhaustive prior-art assessment.
