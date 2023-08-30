# The Contrast Security Integrations CLI
A CLI tool for adding Contrast Integrations via rule customizations.

Adapted from [Contrast-Security-OSS/integrations-scw](https://github.com/Contrast-Security-OSS/integrations-scw) to include a CLI tool, and also to include Secure Flag, Secure Code Warrior and possibly other integrations in the future.

## Usage
```sh
contrast-integrations --help
contrast-integrations auth init
contrast-integrations secure-code-warrior enable-for-rule sql-injection
contrast-integrations secure-code-warrior disable-for-rule sql-injection

contrast-integrations secure-flag enable-for-all 
contrast-integrations secure-flag disable-for-all


```
