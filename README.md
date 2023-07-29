# Conventional Commit Types

## Commit aliases

| Commit Type | Title                    | Description                                                                                                 |
|-------------|--------------------------|-------------------------------------------------------------------------------------------------------------|
| `init`      | Inital Commit            | The projects first commit                                                                                   |
| `feat`      | Features                 | A new feature                                                                                               |
| `fix`       | Bug Fixes                | A bug Fix                                                                                                   |
| `docs`      | Documentation            | Documentation changes                                                                                       |
| `style`     | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `refactor`  | Code Refactoring         | A code change or improvement that neither fixes a bug nor adds a feature                                    |
| `perf`      | Performance Improvements | A code optimisation that improves performance                                                               |
| `test`      | Tests                    | Adding tests or correcting existing tests                                                                   |
| `build`     | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`        | Continuous Integration   | Changes to our CI configuration files and scripts (example scopes: Github Actions, Terraform, Docker, K8s)  |
| `revert`    | Reverts                  | Reverts a previous commit                                                                                   |
| `chore`     | Chores                   | Other changes that don't modify code or test files                                                          |

## Commit aliases

| Commit Alias       | Maps to | Title             | Description                                                                       |
|--------------------|---------|-------------------|-----------------------------------------------------------------------------------|
| `dependencies`     | `deps`  | Dependencies      | Update dependencies (`go.mod`, `cargo.toml`, `node_modules`, `requirements.txt`)  |
| `devDependencies`  | `deps`  | Dev Dependencies  | Update development dependencies                                                   |
| `readme`           | `md`    | README            | Update to the README file                                                         |

## Examples
Each commit will follow the following format:
```
commitType(commitAlias): commit message
```
If a commit does not warrant a commit alias, it can be omitted, as such:
```
commitType: commit message
```
```
feat(init): the beginning of new things
```
```
chore(deps): add go-chi router to project
```
```
docs(md): give examples on how to use proxy with builtin cli commands
```
