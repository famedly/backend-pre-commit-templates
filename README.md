<!--
SPDX-FileCopyrightText: 2025 Famedly GmbH (info@famedly.com)

SPDX-License-Identifier: Apache-2.0
-->

# Pre-commit templates

This holds precommit-hook definitions for [pre-commit](https://pre-commit.com/), that we can use in all our repositories.
Install pre-commit with `pip install pre-commit`

## Usage

Add the pre-commit configuration example (`.pre-commit-config-example.yaml`) as `.pre-commit-config.yaml` to your project.
Then run `pre-commit autoupdate` to automatically use the newest revision on the main branch (branches in the config are invalid) and run `pre-commit install` to install the pre-commit hooks locally.
The configured hooks are then run before commits and check your commit for validity.
