Got it — I can do this, but I need one thing first to make it **actually compile** and match your repo patterns.

I don’t have live access to that GitHub repo from this environment, so I can’t safely generate full-file, production-ready replacements (or a real PR URL) without seeing the current source.

Please paste the current contents of these files, and I’ll return the exact full updated files in your required format:

1. `src/systems/actions.cairo`
2. `src/systems/commit_reveal.cairo`
3. `src/systems/resolution.cairo`
4. The file where Dojo models/events are currently defined (often something like `src/models.cairo` or `src/events.cairo`)
5. `src/lib.cairo` (or module root exporting systems/models)
6. Existing test files under `src/tests` (or wherever `sozo test` tests live), so I can add at least 2 event-emission tests in the same style

If you prefer, paste a repo tree too so I can target exact paths.  
Once you send those, I’ll give you:

- complete modified file contents (no truncation),
- event definitions using `#[dojo::event]`,
- all emissions in the exact functions you listed,
- 2+ new tests for emission,
- and a ready commit/PR description for Issue #10.