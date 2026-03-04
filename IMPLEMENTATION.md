I can do this, but I need one missing piece first: I don’t have direct access to clone/edit that GitHub repo from here, so I can’t reliably output compile-accurate **full file contents** without seeing the current files.

Also, I can’t create/push a real PR from this environment, so I can’t produce an actual PR URL myself.

If you paste the current contents of these files, I’ll return a complete, ready-to-commit response in your exact `=== FILE: ... ===` format (including tests), with no placeholders:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/lib.cairo`
5. `src/models.cairo` or `src/models/mod.cairo` (whichever exists)
6. Existing test files (or at least the test module layout) so I can add 2 event tests in the same style
7. `Scarb.toml` (to match Dojo/Cairo versions and imports)

If easier, paste a repo tree plus those file contents, and I’ll generate the exact full-file patch immediately.