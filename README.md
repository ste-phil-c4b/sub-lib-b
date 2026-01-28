# Sub-Lib-B

A demonstration submodule library for the git submodule workflow demo.

## Purpose

This repository serves as **Submodule B** in the `main-project` demo. It demonstrates how feature development works when using git submodules with GitHub Flow.

## Usage

This library is intended to be used as a git submodule:

```bash
git submodule add https://github.com/ste-phil-c4b/sub-lib-b.git libs/sub-lib-b
```

## Development Workflow

When making changes to this submodule:

1. Create a feature branch: `git checkout -b feature/my-feature`
2. Make your changes and commit
3. Push and create a PR in this repository
4. After merge, update the submodule reference in the parent project

See the [WORKFLOW.md](https://github.com/ste-phil-c4b/main-project/blob/main/WORKFLOW.md) in the main project for detailed instructions.

## Contents

- `lib-b.md` - Sample library documentation/content
