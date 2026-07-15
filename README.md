# One Holy Bible Assets

This repository is the immutable public image layer for
[`Siqiho/one-holy-bible`](https://github.com/Siqiho/one-holy-bible).

## Storage contract

- Every file is stored as `assets/<sha256>.png`.
- The filename is the SHA-256 digest of the exact PNG bytes.
- Published application releases reference a fixed commit, never a moving branch.
- Existing asset filenames are immutable. Corrections create a new digest instead of replacing old bytes.
- Application code, Bible text, and explanatory card data remain in the main repository.

## Current asset set

- Unique PNG files: 2,515
- Total PNG bytes: 2,968,182,132
- Sorted `sha256 bytes` record digest: `4d18f0d35b9d53d4a6d3b7e760d24c1f1f163b881b5b323d824e3ddb4825e4f3`

These files are published for use by the One Holy Bible project. Source and
provenance information for public cards remains with the corresponding
application release.
