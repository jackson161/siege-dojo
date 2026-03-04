Got it — I can implement this, but I need one thing first to do it **correctly and compile-ready**: I don’t have direct filesystem/GitHub access in this chat, so I can’t read the current repo state or open a real PR from here.

Please paste the current contents of these files (or share a zip/tree dump), and I’ll return the **full modified files** in your exact `=== FILE: ... ===` format:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/lib.cairo` (or wherever modules are declared)
5. Existing model/event files (likely under `src/models/`)
6. Test files directory contents (the 18 existing tests)
7. `Scarb.toml` (to match Dojo/Cairo version and APIs)

Once you send that, I’ll provide:
- all 5 `#[dojo::event]` definitions,
- correct emission points in each system,
- at least 2 new event-emission tests,
- complete file outputs only (no truncation),
- and a PR-ready commit set (you can paste directly).  

I can’t generate a real PR URL myself from this environment, but I’ll give you everything needed to create it immediately.