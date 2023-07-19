# Primittive ESLint config

## Included?

- Prettier;
- React Hooks plugin;
- React plugin;
- Standard config base;
- JSX a11y plugin;

Install dependencies:
```
npm i -D eslint @primittive/eslint-config
```
or

```
pnpm i -D eslint @primittive/eslint-config
```
or

```
yarn i -D eslint @primittive/eslint-config
```

## Setup

### React (with Next.js)

Inside `.eslintrc.json`
```
{
  "extends": [
    "@primittive/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Inside `.eslintrc.json`
```
{
  "extends": "@primittive/eslint-config/react"
}
```

### Node.js

Inside `.eslintrc.json`
```
{
  "extends": "@primittive/eslint-config/node"
}
```
> You can also use a `.eslintrc.js` instead of JSON if you prefer.