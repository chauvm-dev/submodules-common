# Submodules Common

This submodule serves as a centralized repository for commonly used components across various projects. It includes types, constants, assets, libraries, and utilities, which can be shared and reused to ensure consistency and reduce duplication.

## Contents

- **Types**: Shared TypeScript types and interfaces.
- **Constants**: Common constants used across different modules and applications.
- **Assets**: Shared assets such as images, fonts, and other static files.
- **Libraries**: Utility libraries and functions that provide common functionalities.
- **Utilities**: Helper functions and utilities to simplify and streamline development.

## Usage

To use the common components in your project, add and update the submodule:

```js
git submodule add 'absolute or relative URL'
```

Example:

```js
git submodule add git@github.com:chauvm-dev/submodules-common.git
```

Then:

```js
git submodule update --init --recursive --remote
```

## Directory Structure

```
submodules-common/
├── assets/
│   ├── images/
│   ├── fonts/
│   └── ...
├── constants/
│   ├── index.ts
│   └── ...
├── libs/
│   ├── index.ts
│   └── ...
├── types/
│   ├── index.ts
│   └── ...
├── utils/
│   ├── index.ts
│   └── ...
```