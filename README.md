<!-- TITLE_START -->

# [Sqlpm workspace](https://github.com/erichosick/sqlpm-workspace)

<!-- TITLE_END -->

<!-- BADGES_START -->
[![tool](https://img.shields.io/badge/github-blue?logo=typescript&label=tool)](https://github.com) [![langauge](https://img.shields.io/badge/javascript-blue?logo=javascript&label=langauge)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![pkg manager](https://img.shields.io/badge/pnpm-blue?logo=pnpm&label=pkg+manager)](https://pnpm.io) [![workspaces](https://img.shields.io/badge/pnpm-blue?logo=pnpm&label=workspaces)](https://pnpm.io/workspaces) [![license](https://img.shields.io/badge/GPL--3.0--or--later-blue?label=license)](https://raw.githubusercontent.com/spdx/license-list-data/main/text/GPL-3.0-or-later.txt) [![language](https://img.shields.io/badge/typescript-blue?logo=typescript&label=language)](https://www.typescriptlang.org) [![ci](https://img.shields.io/badge/nx-blue?label=ci)](https://nx.dev/) [![linting](https://img.shields.io/badge/eslint-blue?label=linting)](https://eslint.org/) [![code style](https://img.shields.io/badge/prettier-blue?label=code+style)](https://prettier.io/) [![testing](https://img.shields.io/badge/jest-blue?label=testing)](https://jestjs.io/) [![ci/cd](https://img.shields.io/badge/commitlint-blue?label=ci%2Fcd)](https://commitlint.js.org/)
<!-- BADGES_END -->

<!-- DESCRIPTION_START -->

**sqlpm-workspace**: The pnpm workspace that contains all of our packages, projects, and utilities.

<!-- DESCRIPTION_END -->

<!-- DETAILS_START -->

<!-- DETAILS_END -->

<!-- QUICK_SETUP_START -->
# Quick Start

Using a terminal, clone and install the project:

```bash
# clone the project
git clone https://github.com/erichosick/sqlpm-workspace.git

# install all dependencies
cd sqlpm-workspace && pnpm install
```
Build all projects:

```bash
# build all packages
pnpm build

# continuous development
pnpm build:watch
```

**NOTE:** to assure any changes to code are applied during development, be sure to run `pnpm build:watch`.



<!-- QUICK_SETUP_END -->

<!-- FEATURES_START -->

## Features

* single repository for all of our packages, projects, and utilities written in node
* uses pnpm workspaces to manage dependencies

<!-- FEATURES_END -->

<!-- TABLE_OF_CONTENTS_START -->

<!-- TABLE_OF_CONTENTS_END -->

<!-- INSTALLATION USAGE_START_START -->

<!-- INSTALLATION USAGE_START_END -->

<!-- DEPENDENCIES_START -->
## Dependencies
* [git](https://www.git-scm.com): version control system
* [github](https://www.github.com): git repository hosting service
* [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version): semantic versioning, changelogs
* [conventional commits](https://www.conventionalcommits.org/): a specification for adding human and machine readable meaning to commit messages
* [pnpm](https://pnpm.io): effecient package manager for node.js
* [pnpm workspace](https://pnpm.io/workspaces): support workspaces and mono-repos
* [typescript](https://www.npmjs.com/package/typescript): typescript programming language
* [nx](https://nx.dev): fast, maintainable CI for monorepos
* [eslint](https://eslint.org/): find and fix problems in your JavaScript code
* [prettier](https://prettier.io/): opinionated code formatter
* [jest](https://jestjs.io/): javascript testing framework with a focus on simplicity
* [commitlint](https://commitlint.js.org/): lint conventional commits

<!-- DEPENDENCIES_END -->

<!-- CONFIGURATION_START -->

<!-- CONFIGURATION_END -->

<!-- DOCUMENTATION_START -->

<!-- DOCUMENTATION_END -->

<!-- EXAMPLES_START -->

<!-- EXAMPLES_END -->

<!-- FAQ_START -->
## FAQ
### Why aren't changes to the code base being applied?

Did you run `pnpm build:watch`?

<!-- FAQ_END -->

<!-- LICENSE_START -->

# Software License

This software is licensed under GPL-3.0-or-later. For more details, see [LICENSE](./LICENSE).

Since this is a workspace, other packages within it may be licensed under different terms. In such cases, the package will contain its own licensing terms.

<!-- LICENSE_END -->

<!-- ADDITIONAL_NOTES_START -->

<!-- ADDITIONAL_NOTES_END -->


<!-- WORKSPACES_START -->

## Workspaces

* [utilities](utilities/README.md): highly reusable packages, that provide utility, libraries, components and modules.
* [packages](packages/README.md): libraries, toolchainthat provide higher order functionality.
* [projects](projects/README.md): command line tools, documentation and services.
* [products](products/README.md): complete applications, services and websites
* [sqlpm-packages](sqlpm-packages/README.md): contains sqlpm installable packages


<!-- WORKSPACES_END -->