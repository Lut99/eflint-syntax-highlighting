# Change Log

All notable changes to the "eflint-syntax-highlighting" extension will be documented in this file.

## [1.2.0] - 2023-01-21
### Added
- Support for more keywords, such as `Enabled`, `Current Time`, `Obfuscated by` or `Union`.
- Support for directives, i.e., `#include` and `#require`.

## [1.1.1] - 2022-12-15
### Fixed
- Comments not being recognized and properly highlighted
- Some links not working in the README.

## [1.1.0] - 2022-12-13
### Added
- Hightlighting for keywords `Recipient`, `Holder`, `Claimant`, `Terminated by` and `Violated when`.
- `true`, `True`, `false` and `False` as additional constants.
  - Note that to do this, constants are now priorized over buildins, variables, strings and implicit strings.
- Identifiers (including `[ ... ]`).
- `Boolean` as a proper builtin.
- An icon for the eFLINT language.
- Special-character operators (`+`, `?`, `.`, `==`, `>`, ...).

### Changed
- `Not`, `Foreach`, `Exists`, `Forall`, `Sum`, `Count`, `Max` and `Min` are now parsed as operators.

## [1.0.0] - 2022-08-13
### Added
- Initial release.
