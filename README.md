# LibertyLens downloads

This repository contains signed public desktop releases of LibertyLens.

LibertyLens safeguards a phone's live video by recording it directly on the
user's personal Mac. Source code and development work are maintained in a
private repository; this public repository contains release binaries only.

Download the latest production build from the
[Releases](https://github.com/Dobbs3313/LibertyLens-releases/releases/latest)
page.

Each desktop download is published with a matching `.sha256` file. Verify the
archive before opening it:

```sh
shasum -a 256 -c LibertyLens-*-macOS-arm64.sha256
```

Production macOS builds are signed with an Apple Developer ID certificate and
notarized by Apple before publication. If no release appears on the Releases
page, a production build has not been published yet.

## Platform availability

- macOS arm64 (Apple silicon): automated release target
- Windows: planned
- Android: distributed through Google Play, not from this repository

Read the [LibertyLens Privacy Policy](https://arisparty.org/libertylens/privacy)
for details about recordings, personal-relay connections, purchases, and ads.

Copyright 2026 Aris Party. All rights reserved. No source-code license is
granted by this downloads repository.
