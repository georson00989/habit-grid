# habit-grid

Habit tracker grid built with Vue 3 composition API

Started as a weekend hack, grew on me.

## Examples

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Installation

```bash
npm install
npm run dev
```

## What it does

- GitHub-style contribution grid per habit
- Vite dev setup with hot reload
- Composition API + script setup
- State persisted to localStorage

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version

## License

MIT licensed, see LICENSE.
