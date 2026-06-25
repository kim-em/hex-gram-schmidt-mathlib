# hex-gram-schmidt-mathlib

Mathlib correspondence proofs for
[`hex-gram-schmidt`](https://github.com/kim-em/hex-gram-schmidt): the executable
integer Gram-Schmidt is shown to agree with Mathlib's `gramSchmidt`. Proof-only.

```
require HexGramSchmidtMathlib from git "https://github.com/kim-em/hex-gram-schmidt-mathlib.git" @ "<rev>"
```

Depends on `hex-gram-schmidt`, `hex-matrix-mathlib`, `hex-matrix`, and Mathlib
(all pinned). Development happens in [`hex-dev`](https://github.com/kim-em/hex-dev).

The pins above must stay consistent: when you bump `hex-gram-schmidt`, bump this
repo to match in the same step. Lake does not reconcile mismatched revisions of
a package required at more than one point in the dependency graph, so an
out-of-sync pin fails to resolve.
