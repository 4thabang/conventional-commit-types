# Conventional Commit Types

| Commit Type | Title                    | Description                                                                                                 |
|-------------|--------------------------|-------------------------------------------------------------------------------------------------------------|
| `feat`      | Features                 | A new feature                                                                                               |
| `fix`       | Bug Fixes                | A bug Fix                                                                                                   |
| `docs`      | Documentation            | Documentation only changes                                                                                  |
| `style`     | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `refactor`  | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                   |
| `perf`      | Performance Improvements | A code change that improves performance                                                                     |
| `test`      | Tests                    | Adding missing tests or correcting existing tests                                                           |
| `build`     | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`        | Continuous Integration   | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| `chore`     | Chores                   | Other changes that don't modify src or test files                                                           |
| `revert`    | Reverts                  | Reverts a previous commit                                                                                   |

## Commit aliases

| Commit Type        | Maps to | Title             | Description                     |
|--------------------|---------|-------------------|---------------------------------|
| `initial`          | `feat`  | Initial           | Initial commit                  |
| `dependencies`     | `fix`   | Dependencies      | Update dependencies             |
| `peerDependencies` | `fix`   | Peer Dependencies | Update peer dependencies        |
| `devDependencies`  | `chore` | Dev Dependencies  | Update development dependencies |
| `metadata`         | `fix`   | Metadata          | Update metadata (package.json)  |
