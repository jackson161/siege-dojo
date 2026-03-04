I can do this, but to give you **compile-ready full-file outputs** in your exact format (and avoid breaking existing logic/tests), I need the current contents of these files first:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/models` module files (likely `src/models.cairo` and/or `src/models/*.cairo`)
5. test entry/module files (likely `src/tests.cairo` and existing test files)

I also can’t directly create/push a GitHub branch from here, so I can’t provide a real PR URL myself.  
Once you paste those files, I’ll return:

- all modified/new files in your exact `=== FILE: ... ===` format,
- 5 `#[dojo::event]` structs,
- emissions in all required system functions,
- at least 2 event-emission tests aligned with your existing test harness,
- and a ready-to-commit patch set that should pass `sozo test`.