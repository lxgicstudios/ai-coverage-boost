# ai-coverage-boost

![npm](https://img.shields.io/npm/v/ai-coverage-boost) ![Node.js](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen) ![License](https://img.shields.io/npm/l/ai-coverage-boost)

AI-powered code coverage booster. Identifies untested paths and generates missing tests.

## Install

```bash
npm install ai-coverage-boost
```

Or run directly:

```bash
npx ai-coverage-boost
```

## Usage

```javascript
const coverageBoost = require('ai-coverage-boost');

// Basic usage
coverageBoost.main();
```

See the `examples/` directory for more detailed usage examples.

## What It Does

- Scans your codebase for untested branches and functions
- Generates test cases to fill coverage gaps
- Works with Jest, Vitest, and Mocha

## Options

| Flag | Description |
|------|-------------|
| `--dir <path>` | Target directory to analyze |
| `--framework <name>` | Test framework: jest, vitest, mocha |
| `--output <path>` | Write generated tests to directory |
| `--dry-run` | Preview without writing files |
| `--help` | Show help message |

## License

MIT

---

**Built by [LXGIC Studios](https://lxgicstudios.com)**

🔗 [GitHub](https://github.com/lxgicstudios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
