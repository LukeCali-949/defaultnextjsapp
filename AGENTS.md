# AGENTS.md — Project Rules

## Package Manager

This project uses **pnpm** exclusively. All agents and contributors must follow these rules:

- **Use pnpm only.** Never run `npm install`, `npm i`, `npx`, or `yarn`.
- Use `pnpm add <package>` to add dependencies.
- Use `pnpm remove <package>` to remove dependencies.
- Use `pnpm run <script>` to run scripts.
- Use `pnpm dlx` instead of `npx` for one-off package execution.
- The `packageManager` field in `package.json` enforces the correct version.
- Do **not** create or commit a `package-lock.json` or `yarn.lock` file.
