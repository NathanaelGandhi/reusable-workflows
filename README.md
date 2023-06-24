# reusable-workflows

Nathanael Gandhi | github.com/NathanaelGandhi

## Clang Format Check

This workflow can run Clang-Format on your repo using the style listed in a .clang-format file. Configure the caller as required.

See [https://github.com/NathanaelGandhi/clang-format-check-reusable-workflow](https://github.com/NathanaelGandhi/clang-format-check-reusable-workflow) for the latest version.

1. Copy the [clang-format-check-caller.yaml](.github/workflows/clang-format-check-caller.yaml) into your own ```.github/workflows``` folder

## release-drafter-reusable-workflow

This workflow can auto-label PRs, create draft releases and publish the release. Configure the caller as required.

See [https://github.com/NathanaelGandhi/release-drafter-reusable-workflow](https://github.com/NathanaelGandhi/release-drafter-reusable-workflow) for the latest version.

1. Copy the [release-drafter-caller.yaml](.github/workflows/release-drafter-caller.yaml) into your own ```.github/workflows``` folder
2. Copy the [release-drafter.yml](.github/release-drafter.yml) into your own ```.github/``` folder

## Stale

This workflow can auto-label PRs and Issues as stale. Configure the caller as required.

See [https://github.com/NathanaelGandhi/stale-reusable-workflow](https://github.com/NathanaelGandhi/stale-reusable-workflow) for the latest version.

1. Copy the [stale-caller.yaml](.github/workflows/stale-caller.yaml) into your own ```.github/workflows``` folder
