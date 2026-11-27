# Agent instructions

- Write committed content in English.
- Packs contain JSON data only. The CI workflow is the only code in this repository.
- Keep Study values and digits out of station and lesson text.
- Do not write a lesson for the held-out station.
- Write lessons from scratch. Do not copy the old tool's text.
- Every pull request runs `hypotrail lesson check` at the Hypotrail commit in `hypotrail.pin`.
- Keep packs in `packs/<id>/`.
