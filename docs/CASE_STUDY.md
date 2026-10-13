# Bilingual team time clock

## Problem and contribution

A small team needed an English/Khmer workflow for clocking time, reviewing weekly hours and correcting mistakes. I built the original tool with AI assistance and iterated on interval, correction and deletion behavior. This is an operations/product example; AI assistance is not a claim that the application contains an AI model.

## Product decisions

- Cambodia dates and overnight intervals follow the team's context.
- A correction affects the edited day while preserving raw events.
- Workers can request corrections; a separate admin view reviews them.
- English/Khmer labels make the same workflow available in both languages.
- Fictional view selection and reset let a reviewer explore both roles without credentials.

## Portfolio migration

The demonstration replaces operational integration with synthetic data and an explicit browser-only boundary. A fresh repository avoids copying original operational Git history. Preserving the original privately does not erase earlier third-party copies or caches.

## Evidence and limits

I have retired the original tool; its source and operational records remain private. The demo has regression and browser workflow evidence recorded in `VERIFICATION.md`. Actual team adoption, measured time savings, accessibility acceptance, physical-device installation and full production-security assurance are not established here. The open admin view is intentional in this fictional demo and unsuitable as production authorization.

## Lessons

Local presentation gates are not a database authorization boundary. Public demos should ship only the files they need and should be separated from operational data, credentials and history. Focused tests are useful for time calculations and malformed saved state; live access control requires its own deployment evidence.
