# Todo API NodeJS

## Project Setup

Check `node` and `npm` version
```shell
node -v
npm -v
```

Initialize empty `node` project

```shell
npm init -y
```

Set project to use `Modele` syntax

`package.json`
```json
{
    "type": "module"
}
```

Install dependencies for TypeScript project

```shell
npm i -D typescript @types/node tsx
```

Initialize TypeScript

```shell
npx tsc --init
```

Add some scripts in `package.json` file

`package.json`
```json
{
    "scripts": {
        "dev": "tsx src/index.ts",
        "dev2": "tsc && node dist/index.js",
        "build": "tsc",
        "start": "node dist/index.js"
    }
}
```
