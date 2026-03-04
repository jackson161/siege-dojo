I can do this, but I need one missing piece to do it correctly in the exact format you requested:

I don’t have direct read/write access to that GitHub repo from here, so I can’t:
1. read the current file contents reliably, or  
2. create/push a branch and return a real PR URL.

To give you **complete, compile-ready full files** (not guesswork), please paste these current files (or a tarball/snippets), and I’ll return fully updated versions in your exact `=== FILE: ... ===` format:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/models.cairo` (or wherever models/events are declared)
5. `src/lib.cairo` (module wiring)
6. existing test files and test module index (`src/tests/...`, `src/tests.cairo` or equivalent)
7. `Scarb.toml` (to confirm Dojo/Cairo versions and imports)

Also confirm one thing:
- Are you on Dojo v1 event API with `world.emit_event(@Event { ... })` and `#[dojo::event]` in model modules?

Once you share that, I’ll produce the exact full-file output and include at least 2 new event-emission tests.