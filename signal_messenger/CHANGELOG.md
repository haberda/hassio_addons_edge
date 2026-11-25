# Changelog since 0.101.0
- Merge pull request #263 from haberda/dependabot/github_actions/frenck/action-addon-linter-2.21.2

build(deps): bump frenck/action-addon-linter from 2.21.1 to 2.21.2 
- build(deps): bump frenck/action-addon-linter from 2.21.1 to 2.21.2

Bumps [frenck/action-addon-linter](https://github.com/frenck/action-addon-linter) from 2.21.1 to 2.21.2.
- [Release notes](https://github.com/frenck/action-addon-linter/releases)
- [Commits](https://github.com/frenck/action-addon-linter/compare/v2.21.1...v2.21.2)

---
updated-dependencies:
- dependency-name: frenck/action-addon-linter
  dependency-version: 2.21.2
  dependency-type: direct:production
  update-type: version-update:semver-patch
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #262 from haberda/fix/rootless-cleanup-and-features

fix: clean up rootless runtime and add health, backup, and receive op… 
- fix: keep Connected backend metric and show health as a detail

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com> 
- fix: replace obsolete watchdog with Docker HEALTHCHECK

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com> 
- fix: clean up rootless runtime and add health, backup, and receive options

- Simplify options.sh, default mode to normal, and chown /config only when needed
- Drop privileges for the idle JSON-RPC service and fix Dockerfile ordering/labels
- Serve a 503 notice through ingress when WEBUI_ENABLED is false
- Add Supervisor watchdog on /v1/health and show health in the Overview
- Add AUTO_RECEIVE_SCHEDULE and RECEIVE_WEBHOOK_URL; default AUTO_RECEIVE to false
- Exclude re-downloadable media from backups and add option translations
- Ask agents to use the humanizer skill for docs and console output

Co-Authored-By: Claude Opus 5.5 <noreply@anthropic.com> 
- Create AGENTS.md 
- Merge pull request #261 from haberda/dependabot/github_actions/docker/login-action-4.7.0

build(deps): bump docker/login-action from 4.6.0 to 4.7.0 
- build(deps): bump docker/login-action from 4.6.0 to 4.7.0

Bumps [docker/login-action](https://github.com/docker/login-action) from 4.6.0 to 4.7.0.
- [Release notes](https://github.com/docker/login-action/releases)
- [Commits](https://github.com/docker/login-action/compare/v4.6.0...v4.7.0)

---
updated-dependencies:
- dependency-name: docker/login-action
  dependency-version: 4.7.0
  dependency-type: direct:production
  update-type: version-update:semver-minor
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Simplify docs 
