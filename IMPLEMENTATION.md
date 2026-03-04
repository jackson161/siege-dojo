I can do this, but I need one thing first to avoid hallucinating broken Cairo/Dojo code.

I **don’t have direct repo read/write access** in this environment, so I can’t inspect your current file contents or create a real PR URL yet.  
To produce exactly what you asked (full files, compile-ready, tests updated, no truncation), please paste these current files:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/models/mod.cairo` (and any existing model/event files it references)
5. `src/lib.cairo`
6. Existing test files (the 18-test suite locations, especially any system tests)

Once you paste them, I’ll return:
- complete modified/new files in your exact `=== FILE: ... ===` format,
- at least 2 event-emission tests,
- and a ready-to-apply patch.

Also: I can’t directly push branches or open GitHub PRs from here, so I can’t generate a real PR URL myself—but I can give you the exact commit-ready file set to paste/apply locally and open PR `Closes #10`.