# Boilerplate React-ts Project

:zap: vite  
:sparkles: react + swc  
:sparkles: typescript  
:sparkles: husky + commitlint + nano-staged  
:sparkles: eslint + prettier  
:sparkles: storybook  

### Prerequisites

##### Node.js

Install `node.js` version. This project has `.nvmrc` file contains specific node.js version to use.  
We recommend to use [nvm](https://github.com/nvm-sh/nvm) to install specific version, that way don't forget to install it first.

install node.js with nvm based on .nvmrc file:

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
