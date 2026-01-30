# ai-coverage-boost

[![npm version](https://img.shields.io/npm/v/ai-coverage-boost.svg)](https://www.npmjs.com/package/ai-coverage-boost)
[![npm downloads](https://img.shields.io/npm/dm/ai-coverage-boost.svg)](https://www.npmjs.com/package/ai-coverage-boost)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-coverage-boost)](https://github.com/lxgic-studios/ai-coverage-boost/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Find untested code paths and auto-generate tests. Point it at a file and get instant coverage improvements.

## Install

```bash
npm install -g ai-coverage-boost
```

## Usage

```bash
npx ai-coverage-boost ./src/utils.ts
# → Found 4 untested paths
# → Tests written to ./src/utils.test.ts

npx ai-coverage-boost ./src/utils.ts --dry-run
# → Shows uncovered paths without writing files

npx ai-coverage-boost ./src/utils.ts -o ./tests/utils.test.ts
# → Custom output path
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
