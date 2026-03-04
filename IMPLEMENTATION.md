I can do this, but I need one thing first: I don’t have live access to that GitHub repo from here, so I can’t inspect the current codebase or create a real PR URL directly.

To give you **complete, compile-ready full files** in your exact format (without guessing and breaking tests), paste these current files:

1. `Scarb.toml`
2. `src/lib.cairo`
3. `src/models.cairo` (or all files under `src/models/` if split)
4. `src/systems/actions.cairo`
5. `src/systems/commit_reveal.cairo`
6. `src/systems/resolution.cairo`
7. Existing test files (`src/tests/**` or wherever `sozo test` tests live)

Once you paste them, I’ll return:
- all modified/new files in the exact `=== FILE: ... ===` format,
- 5 `#[dojo::event]` structs,
- emissions at the exact points you listed,
- at least 2 new event-emission tests aligned to your current harness,
- and the exact git commands/PR body for Issue #10.

If you want, I can also include a ready-to-paste PR description with “Closes #10”.