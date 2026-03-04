Got it — I can implement this cleanly, but to give you **exact, full-file, compile-ready outputs** (and not hallucinate your repo structure), I need the current contents of these files first:

1. `Scarb.toml`
2. `src/lib.cairo`
3. `src/models.cairo` (or wherever models/events are currently declared)
4. `src/systems/actions.cairo`
5. `src/systems/commit_reveal.cairo`
6. `src/systems/resolution.cairo`
7. All test files under `src/tests/` (or your actual test directory)

Also: I can’t create a real GitHub PR URL from inside this chat session. I can give you the exact code + commit message + PR title/body so you can paste and open it in one shot.

If you paste those files, I’ll return:
- every modified/new file in your exact required format,
- 5 `#[dojo::event]` structs,
- event emissions at the exact system points,
- at least 2 new event-emission tests,
- and changes aligned to your existing Dojo patterns so `sozo test` passes.