[![Minimal node version](https://img.shields.io/static/v1?label=node&message=%3E=14.16&logo=node.js&color)](https://nodejs.org/about/releases/)
[![Minimal npm version](https://img.shields.io/static/v1?label=npm&message=%3E=6.14.12&logo=npm&color)](https://github.com/npm/cli/releases)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)
[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)

# NODEJS template: typescript compatibility

## Description

Template for [nodejs/browser/es6/typescript] with ESLint configuration

## Contributing

1. npm run build - Build library.
2. npm run start - start project
3. npm run test - Run test with jest.
4. npm run lint - Lint your code.
5. npm run lint:fix - Lint fix your code.
6. npm run typecheck - Run typescript check.
7. npm run doc - Generate html doc.
8. npm run release - Release library
9. npm run fix - Fix library

## Production

```bash
npm i --production
npm start
```

## CLI

```bash
npm install --global .
```

**launch:**

```bash
node-www
```

## Docs

### Summary

- [Apprendre nodejs](https://github.com/stephendltg/nodebook)
- [Apprendre typescript](https://www.typescriptlang.org/fr/)
- [Typescript config](https://github.com/tsconfig/bases)
- [Reference javascript](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference)
- [ECMA-262](https://www.ecma-international.org/publications-and-standards/standards/ecma-262/)
- [summary of the new ES version by example](https://github.com/gautemo/ES-Intro)
- [Nodejs best practices](https://github.com/goldbergyoni/nodebestpractices)
- [Nodejs testing best practices](https://github.com/goldbergyoni/javascript-testing-best-practices)
- [Structure nodejs project](https://github.com/elsewhencode/project-guidelines)
- [NPM documentation](https://docs.npmjs.com/cli/v8/commands)
- [Package.json documentation](https://docs.npmjs.com/cli/v8/configuring-npm/package-json)
- [Apprendre Git](https://www.atlassian.com/fr/git/tutorials/setting-up-a-repository)
- [Git conventions](conventions.md)
- [library & tools](tools.md)

**ESLINT:**

- [Typescript ESLint](https://typescript-eslint.io)
- [ESLint configuration](https://eslint.org/docs/user-guide/configuring/)
- [ESLint rules](https://eslint.org/docs/rules/)
- [ESLint standard](https://www.npmjs.com/package/eslint-config-standard)
- [ESLint unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)
- [ESLint comments](https://mysticatea.github.io/eslint-plugin-eslint-comments/)
- [ESLint import](https://github.com/import-js/eslint-plugin-import)
- [ESLint json](https://www.npmjs.com/package/eslint-plugin-jsonc)
- [ESLint promise](https://www.npmjs.com/package/eslint-plugin-promise)
- [ESLint yaml](https://www.npmjs.com/package/eslint-plugin-yml) (for CI)
- [ESLint prettier](https://github.com/prettier/eslint-config-prettier)
- [ESLint node](https://www.npmjs.com/package/eslint-plugin-n)
- [ESLint jest](https://www.npmjs.com/package/eslint-plugin-jest)
- [ESLint parser json](https://www.npmjs.com/package/jsonc-eslint-parser)
- [ESLint parser yaml](https://www.npmjs.com/package/yaml-eslint-parser)

### VSCODE Addons

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [jest runner](https://marketplace.visualstudio.com/items?itemName=firsttris.vscode-jest-runner)
- [thunder client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
- [git lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Edit csv](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv)

### Package maintenance

A modern cli tool that keeps your deps fresh

```bash
npx taze
```

