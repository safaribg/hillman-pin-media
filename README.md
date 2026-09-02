# hillman-pin-media

Public image host for HillmanGear / Hillman Deutschland Pinterest creative.

It exists for one reason: Pinterest's bulk importer and API v5 both take a **`Media URL`,
not a file**, so a render sitting on a laptop cannot be scheduled. Everything here is
artwork that is intended to be public on Pinterest anyway.

- `samples/` — creative put up for approval, one dated folder per round.
- Paths are **versioned and never overwritten**. A published Pin's image URL must not
  change under it when a template is re-rendered.

No account data, analytics, queue files or credentials belong in this repository.
