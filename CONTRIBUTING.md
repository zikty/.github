# Contributing

Thanks for contributing to a zikty project. These defaults apply to every `zikty`
repository (inherited from the `.github` repo).

## Workflow (GitFlow)

- Branch off `develop` for features (`feature/...`) and fixes (`fix/...`).
- Open a PR into `develop`. `main` and `develop` are protected (PR required, no
  force-push).
- Releases go `develop` → `main`; label the PR `release-candidate` to cut an RC.

## Commits & PRs

- Conventional-style messages help automated versioning: `feat:`, `fix:`, `docs:`,
  `refactor:`, `chore:`, `test:`.
- Keep PRs focused; fill in the PR template; link the issue it closes.
- Apply the standard labels (`type:`, `priority:`, `area:`, …) — see
  [zikty-ops/labels](https://github.com/zikty/zikty-ops/tree/main/labels).

## Local checks

Run the project's build/test before pushing (e.g. `./gradlew test` for Android/KMP).
