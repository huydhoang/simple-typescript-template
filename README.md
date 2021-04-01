# Simple TypeScript Template with Auto Code Formatting

Simply turn on `Format On Save` feature within VSCode and start using.

Prettier extension is required.

## Installed dependencies

```bash
pnpm i -D typescript eslint prettier @types/node @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier
```

## Scripts

To use pre-created scripts, run the following:

```bash
pnpm [script]
```

Available scripts:

```json
{
  "build": "cd node_modules/.bin && tsc ../../main.ts",
  "test": "node main.js",
  "dev": "pnpm build && pnpm test"
}
```

The `build` script didn't directly make use of `./node_modules/.bin/tsc` to avoid `'.' is not recognized as an internal or external command.` on Windows.
