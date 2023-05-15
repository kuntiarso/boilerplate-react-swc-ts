# Boilerplate React-ts Project

:zap: vite  
:sparkles: react + swc  
:sparkles: typescript  
:sparkles: husky + commitlint + nano-staged  
:sparkles: eslint + prettier  

### Prerequisites

##### Node.js

Install `Node.js` version. This project has `.nvmrc` file contains specific `node.js` version to use. To install its specific version we recommend to use `nvm` package, that way please install it [here](https://github.com/nvm-sh/nvm).

install node.js based on `.nvmrc` file:

```
nvm install
nvm use
```

to check used node.js version:

```
nvm which
```

##### PNPM Package Manager

install pnpm:

```
corepack enable
corepack prepare pnpm@latest --activate
pnpm -v
```

##### VS Code (recommended)

Please install `eslint` and `prettier` plugins on VS Code to apply code consistency and autoformatting.

### Running Project

install project:

```
pnpm install
```

running project:

```
pnpm run dev
```
