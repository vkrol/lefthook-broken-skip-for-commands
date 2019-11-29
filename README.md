# lefthook-broken-skip-for-commands
https://github.com/Arkweid/lefthook/issues/93
## Steps
1. Run `lefthook install`
2. Run `lefthook run pre-commit`
3. `123` was printed, but it wasn't supposed to:
```
RUNNING HOOKS GROUP: pre-commit
EXECUTE > foo
(SKIP BY SETTINGS)
SUMMARY: (SKIP EMPTY)
123       
```

