## What & why


## Pre-merge checklist

- [ ] `bash scripts/checks.sh` passed locally on this exact branch head — merges are gated on it
- [ ] Agent review (`pr-review` workflow) ran on this exact head; every confirmed finding fixed or owner-waived — merges are gated on it
- [ ] Bug fixes come with a test that covers the bug
- [ ] Plans/specs this work followed are committed under `docs/`
- [ ] Diff is focused (roughly under 1000 lines); bigger means split it
- [ ] No AI attribution anywhere in commits or this PR

<!-- CI note: GitHub Actions is manual-only while monthly minutes are
     exhausted (since 2026-08). The local gate above replaces it. -->
