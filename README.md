# 🎬 Actions

Reusable GitGub Actions for Antribute Workflows

## List of Actions

| Name                | Description                                                                         |
| ------------------- | ----------------------------------------------------------------------------------- |
| `check-tag-release` | `Grabs the version from a pushed git tag and compares it to a package.json version` |
| `setup`             | `Clones Repo and sets up Node.js, PNPM, and Caching`                                |

## Local Testing

GitHub provides no official way to test GitHub actions locally. Luckily, an open source CLI app
called [Act](https://github.com/nektos/act) allows us to run our workflows locally. To install Act,
simply run `brew install act`. Other installation instructions can be found in their official
documentation.
