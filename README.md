# Random RPG — public updates

This repository contains only compiled game/launcher release packages and update manifests. The game source code remains in the private [Random-RPG repository](https://github.com/wexi567/Random-RPG).

Players should download the launcher from a release asset or use an existing supported launcher. The launcher checks these stable manifests:

- Game: https://github.com/wexi567/Random-RPG-Updates/releases/latest/download/version.json
- Launcher: https://github.com/wexi567/Random-RPG-Updates/releases/latest/download/launcher_version.json

Each release contains versioned ZIPs and both manifests. Do not commit source files, credentials, local saves, or development configuration here.

Releases are published automatically by the private source repository's GitHub Actions workflow. That workflow requires the `RELEASES_REPO_TOKEN` secret with Contents read/write access to this public repository.
