I can do this, but I can’t actually access/pull that GitHub repo or open a PR from this chat environment, so I can’t truthfully give you a real PR URL yet.

To give you exactly what you asked for (full-file, compile-ready outputs in your required format), please paste these current files from your repo:

1. `Scarb.toml`
2. `src/lib.cairo`
3. `src/systems/actions.cairo`
4. `src/systems/commit_reveal.cairo`
5. `src/systems/resolution.cairo`
6. Any existing event/model module files (for example `src/models/*.cairo` or `src/events.cairo`)
7. Existing test files (likely under `src/tests/*`)

Once you paste them, I’ll return:
- Full updated file contents (no truncation) in your exact `=== FILE: ... ===` format
- 5 `#[dojo::event]` structs
- Event emissions at each required call site
- At least 2 new event-emission tests aligned to your current test harness
- A final commit-ready patch you can apply directly

If you want, I can also give you a **best-effort patch right now** based on typical Dojo structure—but it won’t be guaranteed to compile against your exact codebase without seeing those files.