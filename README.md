# use-fluent

A handful of React hooks I keep copy-pasting between projects

Small but I use it weekly.

## Installation

```bash
npm install
npm test
```

## Features

- Tiny: no dependencies besides React
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization
- useMediaQuery SSR-safe

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
