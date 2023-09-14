# Changelog

All notable changes to doltcli will be documented in this file.

This document follows the conventions laid out in [Keep a CHANGELOG](https://keepachangelog.com/en/1.0.0/).

[//]: # "The process to update the changelog for a new release is as follows:"
[//]: # "1. Add a header for the new release with the proper formatting"
[//]: # "   with a link to the corresponding Github release."
[//]: # "2. Make a new blank section for the next unreleased features"
[//]: # "   with the 6 empty sections."
[//]: # "3. Remove the unused sections from the new release."
[//]: # "4. Update the comparison link for the unreleased header to the new tag."

## [Unreleased](https://github.com/lumicks/doltcli/compare/v0.2.0...HEAD)

### Added
- Add CODEOWNERS file. [#24](https://github.com/lumicks/doltcli/pull/24)

### Changed
- Update tests to work with dolt 1.15.0. [#22](https://github.com/lumicks/doltcli/pull/22)
- Bump dolt version to 1.15.0. [#22](https://github.com/lumicks/doltcli/pull/22)

## [v0.2.0](https://github.com/lumicks/doltcli/releases/tag/v0.1.18) - 2023-09-13

### Added
- Add remote and branch to BranchT class to handle updated version of dolt

### Changed
- Bump dolt version to 1.7.5

## [v0.1.18](https://github.com/lumicks/doltcli/releases/tag/v0.1.18) - 2023-01-24

### Added
- Add `track` option to checkout command to checkout upstream branches.
- Add optional `branch` argument to `pull` operation.

### Changed
- Changed the Github actions to our standard ones
