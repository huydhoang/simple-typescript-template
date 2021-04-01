# Simple TypeScript Template with Auto Code Formatting

## Installed dependencies

```bash
pnpm i -D typescript eslint prettier @types/node @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier
```

## Scripts that can be used

```json
{
  "build": "cd node_modules/.bin && tsc ../../main.ts", // to avoid '.' is not recognized as an internal or external command
  "test": "node main.js",
  "dev": "pnpm build && pnpm test"
}
```
