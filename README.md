```console
$ yarn
$ rm -rf .cache && tsc --build tsconfig.json --verbose
$ rm -rf .cache && playwright test
Error: Cannot find module 'helpers/other'
Require stack:
- /Users/oliverash/Development/playwright-ts-paths-issues/app/app.ts
```
