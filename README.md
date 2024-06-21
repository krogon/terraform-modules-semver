# terraform-modules-semver

Example Github Actions workflow that managed terraform modules in monorepo.

This uses `label` workflow to check and enforce PR labeling (patch/minor/major).

This uses `release` workflow to discover changed directories and release new terraform modules tags.

This uses `syntax` workflow to validate terraform syntax.
