# The Contrast Security Integrations CLI
A CLI tool for adding Contrast Integrations via rule customizations.

Adapted from [Contrast-Security-OSS/integrations-scw](https://github.com/Contrast-Security-OSS/integrations-scw) to include a CLI tool, and also to include Secure Flag, Secure Code Warrior and possibly other integrations in the future.

## Installation
The quickest and easiest way to get started would be to install the CLI tool using pipx directly from the latest GitHub release:
```sh
pipx install https://github.com/Contrast-Security-OSS/contrast-integrations-cli/releases/download/v2.0.0/contrast_integrations_cli-2.0.0-py3-none-any.whl

contrast-integrations --help
```

Or clone this repo and run the CLI tool with Poetry 
* `poetry install` to install dependencies
* `poetry run contrast-integrations --help` to run the CLI tool
* `poetry build` to build a wheel file

## Usage
```sh
contrast-integrations --help
contrast-integrations auth init
contrast-integrations secure-code-warrior enable-for-rule sql-injection
contrast-integrations secure-code-warrior disable-for-rule sql-injection

contrast-integrations secure-flag enable-for-all 
contrast-integrations secure-flag disable-for-all


```
