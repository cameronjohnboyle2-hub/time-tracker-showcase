# Verification

The source is derived from the already tested fictional snapshot at original repository commit `bd8617d0e2ad9e65758beb163f590de09a15e406`. The fresh release uses the existing `Website` branch convention, adds documentation and a fictional screenshot, and introduces no runtime changes.

The application suite contains 23 Node tests covering intervals, overrides, saved-state projection, malicious names, blocked storage, local server boundaries, startup and the scoped deployment artifact. Run `npm test` with Node 24. There are no installed package dependencies. All 23 tests passed locally on October 10, 2026. Exact public deployment and hosted checks are recorded in the local migration report after execution.

The earlier hosted snapshot was checked for worker selection, clock-in/out, approval changing a seeded seven-hour day to eight hours, reset, English/Khmer and a 390-pixel phone viewport. This is prior browser evidence; the new public URL requires its own release check. Physical-device/PWA installation and full accessibility acceptance are unverified.

Current-source scanning checks known original identifying fixtures and operational configuration plus bounded credential patterns. A fresh history contains only the reviewed initial snapshot and subsequent release changes. This is not an exhaustive security certification, incident investigation or deletion of copies retained elsewhere.
