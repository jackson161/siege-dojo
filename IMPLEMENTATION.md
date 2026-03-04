I can do this, but I need one thing first to make it **actually compile** and satisfy your “full file content” requirement:

I don’t have direct read/write access to that GitHub repo from this chat, so I can’t reliably reconstruct existing Cairo files (or generate a real PR URL) without seeing the current source.

Please paste these files (full contents), and I’ll return the exact modified/new files in your required format:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/lib.cairo` (or module root where models/events are exported)
5. Any existing models/events file(s), e.g. `src/models/*.cairo`
6. Current test files under `src/tests/**` (or wherever `sozo test` tests live)
7. `Scarb.toml`

Once you paste those, I’ll give you:
- All modified/created files with full content in exactly:
  `=== FILE: ... ===` / `=== END FILE ===`
- 5 `#[dojo::event]` structs
- Event emissions wired into the exact functions you listed
- At least 2 new event-emission tests aligned to your existing test style
- A ready-to-commit patch (and the exact git commands to open the PR that closes #10)