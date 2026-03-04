I can do this, but I need one thing first to make it **actually compile and pass `sozo test`** in your repo:

I don’t have direct write/access to your GitHub repo from here, so I can’t fetch exact current file contents or open a real PR URL myself.

Please paste these current files (or a `git diff` baseline), and I’ll return the **exact full-file replacements** in your required format:

1. `src/lib.cairo`
2. `src/systems/actions.cairo`
3. `src/systems/commit_reveal.cairo`
4. `src/systems/resolution.cairo`
5. Any existing test entrypoint files (commonly `src/tests.cairo`, `src/tests/*.cairo`)
6. `Scarb.toml`

Once you send those, I’ll give you:
- all 5 `#[dojo::event]` structs,
- emissions wired at the exact points,
- at least 2 event-emission tests,
- full file outputs in the exact `=== FILE: ... ===` format,
- and a ready-to-commit patch (plus PR title/body text for Issue #10).