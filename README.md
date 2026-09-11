# crios-crowecode

A monorepo scaffold for an algorithm-writing code editor; it holds a root package.json and no application code.

## Status

archived

One commit, dated 2025-09-02. Development stopped the same day. The commit added a root `package.json` (pnpm workspaces for `apps/*`, `services/*`, `packages/*`, with turbo, prettier and typescript as dev dependencies), a `.gitignore`, and a README. None of the workspace directories exist. There is no lockfile and no source file. The repository is kept for reference.

## Install and first run

Not maintained. No supported install path.

The scripts in `package.json` (`pnpm dev`, `pnpm build`) call `turbo run` across workspaces that were never added, so they have nothing to run.

## What runs today

Nothing is maintained.

## Limits

This is not an editor, an IDE, or a code generator. The earlier README listed features (algorithm generation, ghost text completions, test generation, complexity analysis, sandboxed execution) and a stack (React, Monaco, Express). None of that code is in this repository. Do not depend on it.

## License and contact

No license file.

Contact: michael@crowelogic.com
