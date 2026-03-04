I can do this, but I need one thing first to give you **compile-safe, full-file replacements** in your exact format.

I don’t have direct repo access from here, so I can’t read current file contents or open/push a PR URL myself.  
To avoid breaking your existing 18 tests by guessing your current code, paste these files (current contents) and I’ll return complete modified versions immediately:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. `src/lib.cairo` (or wherever modules are exported)
5. your test entry/module file (e.g. `src/tests.cairo` or `src/tests/mod.cairo`)
6. any existing test setup helper used by current tests

If you want, I can also proceed with a **best-effort inferred patch** right now (without seeing current files), but that won’t be production-safe.