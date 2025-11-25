# Fork Information

This repository is a fork of [dependabot/cli](https://github.com/dependabot/cli).

## Purpose

This fork is maintained to:
- Track and merge updates from the upstream repository
- Apply custom modifications as needed
- Provide a testing ground for new features before contributing upstream

## Keeping in Sync

This fork includes an automated workflow that:
1. Runs daily to check for upstream updates
2. Creates pull requests when new changes are available
3. Can be manually triggered via GitHub Actions

To manually sync:
1. Go to Actions → "Sync with Upstream"
2. Click "Run workflow"
3. Review and merge the created PR

## Contributing

### To this fork
- Open a PR against this repository
- Follow the standard [contributing guidelines](.github/CONTRIBUTING.md)

### To upstream
- If your changes are generally useful, consider contributing them to the [upstream repository](https://github.com/dependabot/cli)
- Follow the upstream's contribution guidelines

## Differences from Upstream

This section documents any fork-specific changes:

- Added `sync-upstream.yml` workflow for automated syncing
- Enhanced CI workflow with concurrency settings and timeouts

## Upstream Repository

- **URL**: https://github.com/dependabot/cli
- **Documentation**: See [upstream README](https://github.com/dependabot/cli/blob/main/README.md)
- **Issues**: https://github.com/dependabot/cli/issues
