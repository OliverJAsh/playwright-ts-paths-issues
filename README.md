```console
$ yarn
$ rm -rf .cache && tsc
$ rm -rf .cache && playwright test
Error: Cannot find module 'Foo'
Require stack:
- /Users/oliverash/Development/playwright-ts-paths-issues/tests/example.spec.ts
```
