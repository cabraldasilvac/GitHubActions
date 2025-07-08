# Studying about Github Actions

## 🧪 GitHub Actions with TypeScript

> A practical playground to learn and experiment with GitHub Actions, TypeScript, testing, linting, and dead code detection.

## ✅ Features

- TypeScript with strict configuration
- Unit tests with Jest
- Dead code detection with `ts-prune`
- Code quality with ESLint (flat config)
- Continuous Integration via GitHub Actions

---

## ⚙️ Setup Instructions

---

1. Clone the repository

```bash
git clone https://github.com/cabraldasilvac/GitHubActions.git
cd GitHubActions
```

2. Install dependencies

```bash
      yarn install
```

3. Run the development server

```bash
      yarn dev
```

4. Run unit tests

```bash
        yarn jest
```

5. Run linter

```bash
yarn lint
```

6. Run type checker

```bash
yarn typecheck
```

🛠️ GitHub Actions Workflow

This project includes a CI workflow that automatically:

Installs dependencies
Runs ESLint and ts-prune to detect dead code
Runs unit tests using Jest
Check the .github/workflows/pull_request.yml file for more details.

🎯 Roadmap

[✓] Initial project structure
[✓] Install dependencies
[✓] Dead code analysis (ts-prune)
[✓] Unit testing (jest)
[✓] Add Prettier for code formatting
[✓] Add coverage report

Inspired by [dogcode's GitHub Actions tutorial](https://www.youtube.com/watch?v=MIVx1qniNKY&ab_channel=dogcode)
