# Record of the work — hash manifests

This directory is a dated, independently timestamped record of the EXISTENCE and
CONTENT of works that are **not published here**.

`TRILOGY-HASH-MANIFEST.json` lists, for every file of the TYGARIA™ trilogy, its
path, byte count, word count and **sha256 over the raw file bytes**. It contains no
prose. At 42 KB it is 0.187% the size of the 22.9 MB it describes.

## What it proves, and what it does not

**Proves:** that each listed file existed, byte-for-byte unchanged, on or before the
timestamp GitHub applied to the release containing this manifest. Produce the file,
hash it, and compare. A single byte of difference changes the hash.

**Does not prove, and is not claimed to:** anything notarised. The strength here rests
entirely on GitHub timestamping its releases independently of the Owner — which is the
basis the `COPYRIGHT` RECORD OF USE clause already relies on. This is not a
timestamping authority and is not offered as one.

## Why the work itself is not here

Copyright subsists automatically on creation under Article 5(2) of the Berne
Convention, with no registration, deposit or publication required. A public record
therefore needs a provable **date**, not the text. Publishing the manuscripts would add
nothing to that and would place 500,000+ words of unpublished prose permanently in
public — against the reservation in `COPYRIGHT` concerning reproduction in or as
training data for machine learning or generative systems.

## Verifying a file

```
shasum -a 256 <file>
```

Compare with the `sha256` recorded for that path in the manifest.

---

© 2026 Tyga.Cloud Ltd. All rights reserved. TYGARIA™ is an unregistered trade mark of
Tyga.Cloud Ltd. See `../COPYRIGHT`.
