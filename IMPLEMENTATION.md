I can do this, but I need one missing piece to give you **compile-safe full-file outputs** in your exact format:

I don’t have direct access to clone/push that GitHub repo from this environment, so I need you to paste the current contents of these files (or share a tarball/tree dump), then I’ll return **ready-to-commit full replacements**:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/lib.cairo`
5. `src/models/mod.cairo` (or `src/models.cairo`, whichever exists)
6. Existing test files under `src/tests/**` (or wherever the 18 tests live)

If you want, I can also include:
- one new `src/models/events.cairo`
- one new test file (or edits to existing tests) with at least 2 event-emission assertions
- exact git commands + PR body text for “Closes #10”

Send those files and I’ll reply with the final output in your required:

`=== FILE: ... ===`  
`...full content...`  
`=== END FILE ===`