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

| Commit Type        | Maps to | Title             | Description                                               |
|--------------------|---------|-------------------|-----------------------------------------------------------|
| `initial`          | `init`  | Initial           | Initial commit                                            |
| `dependencies`     | `deps`  | Dependencies      | Update dependencies                                       |
| `peerDependencies` | `deps`  | Peer Dependencies | Update peer dependencies                                  |
| `devDependencies`  | `deps`  | Dev Dependencies  | Update development dependencies                           |
| `metadata`         | `fix`   | Metadata          | Update metadata (`package.json`, `go.mod`, `cargo.toml`)  |
| `readme`           | `md`    | README            | Update README documents                                   |

## Examples

```
feat(init): the beginning of new things
```
```
fix(deps): add go-chi router to project
```
```
docs(md): give examples on how to use proxy with builtin cli commands
```
