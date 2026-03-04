I can do this, but I can’t reliably produce **compile-safe full file rewrites** (or a real PR URL) without seeing the current repo contents.

To deliver exactly what you asked (full files in the required format, tests preserved, no regressions), paste these files here:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/models.cairo` **or** `src/models/mod.cairo` (whichever exists)
5. `src/lib.cairo`
6. Current test entrypoint: `src/tests.cairo` **or** `src/tests/mod.cairo`
7. Any existing test helpers used by the 18 tests (setup/world deploy utilities)

Once you share those, I’ll return:
- all modified/new files in your exact `=== FILE: ... ===` format,
- the 5 `#[dojo::event]` structs,
- emission wiring in all required systems,
- at least 2 new event-emission tests integrated with your current harness.

If you want, I can also include a ready commit message and PR body text for Issue #10.