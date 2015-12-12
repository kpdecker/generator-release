# Release Notes

## Development

[Commits](https://github.com/kpdecker/generator-release/compare/v2.6.1...master)

## v2.6.1 - December 12th, 2015
- Update for new maintained repository location - 873c598
- Fix increment handling when performing dry run - a5e9bfc
- Add better error for missing release tags - 925fe4c

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.6.0...v2.6.1)

## v2.6.0 - January 23rd, 2015
- [#29](https://github.com/walmartlabs/generator-release/pull/29) - Use more reliable url to fetch pull commits ([@Candid](https://api.github.com/users/Candid))
- Add support for gulp version update command - 0a5b201

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.5.0...v2.6.0)

## v2.5.0 - January 9th, 2015
- Add enterprise github support for publish command - b9f3aec

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.4.0...v2.5.0)

## v2.4.0 - January 6th, 2015
- [#28](https://github.com/walmartlabs/generator-release/issues/28) - GitHub Enterprise Installation ([@pantocrator27](https://api.github.com/users/pantocrator27))
- [#23](https://github.com/walmartlabs/generator-release/issues/23) - Warn when TODO entry is still listed in the release message ([@kpdecker](https://api.github.com/users/kpdecker))
- [#20](https://github.com/walmartlabs/generator-release/issues/20) - Error: commitTime: stdout maxBuffer exceeded. ([@calmdev](https://api.github.com/users/calmdev))
- Include previous message in notes if failed - 7810669

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.6...v2.4.0)

## v2.3.6 - December 15th, 2014
- Handle github subversion urls for fetch url lookup - ddfe493

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.5...v2.3.6)

## v2.3.5 - October 30th, 2014
- [#27](https://github.com/walmartlabs/generator-release/pull/27) - Fix missing PRs and duplicate links ([@Candid](https://api.github.com/users/Candid))
- [#26](https://github.com/walmartlabs/generator-release/pull/26) - Use github API to get pull commits ([@Candid](https://api.github.com/users/Candid))
- Match release notes tags with master - b39ae73

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.4...v2.3.5)

## v2.3.4 - August 26th, 2014
- [#21](https://github.com/walmartlabs/generator-release/pull/21) - Adding additional options for release/notes commands ([@DeTeam](https://api.github.com/users/DeTeam))
- Prevent duplicate v error on custom version - 0723d53

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.3...v2.3.4)

## v2.3.3 - March 12th, 2014
- Fix process argument passing for EDITOR command - fe9c8c9

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.2...v2.3.3)

## v2.3.2 - March 12th, 2014
- [#19](https://github.com/walmartlabs/generator-release/pull/19) - use spawn instead of exec to start $EDITOR, to support terminal editors ([@patrickkettner](https://api.github.com/users/patrickkettner))
- Resolves paths when exec EDITOR - 95ea097
- Add log statement to make editor action obvious - 526c081
- Protect from duplicated v in version - 0843ff5
- Improve logging of git operation errors - 589e596

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.1...v2.3.2)

## v2.3.1 - March 5th, 2014
- Add check for $EDITOR in release:app mode - 99b3976
- Strip v version prefix in publish generator - 2976061
- Handle custom versions in release generator - a1935d2
- Allow for custom version entry - a8cadf5

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.3.0...v2.3.1)

## v2.3.0 - January 22nd, 2014
- Define skip-tests flag in app generator - 1257d78

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.2.0...v2.3.0)

## v2.2.0 - January 21st, 2014
- [#17](https://github.com/walmartlabs/generator-release/pull/17) - Improve test error recovery ([@kpdecker](https://api.github.com/users/kpdecker))

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.1.1...v2.2.0)

## v2.1.1 - January 21st, 2014
- [#14](https://github.com/walmartlabs/generator-release/pull/14) - Add a Bitdeli Badge to README ([@bitdeli-chef](https://api.github.com/users/bitdeli-chef))

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.1.0...v2.1.1)

## v2.1.0 - December 22nd, 2013
- Add default task chaining notes and release tasks - a69667f

[Commits](https://github.com/walmartlabs/generator-release/compare/v2.0.0...v2.1.0)

## v2.0.0 - December 17th, 2013
- [#11](https://github.com/walmartlabs/generator-release/issues/11) - Add "[author]" to titles of PRs to CDNJS ([@eastridge](https://api.github.com/users/eastridge))
- [#10](https://github.com/walmartlabs/generator-release/issues/10) - Unify the notes and release tasks ([@kpdecker](https://api.github.com/users/kpdecker))

Compatibility notes:
`release:notes` now utilizes `$EDITOR` if specified and prompts for the increment value. `release:release` now utilizes the increment value specified in the notes command automatically.

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.5.0...v2.0.0)

## v1.5.0 - November 7th, 2013

- [#2](https://github.com/walmartlabs/generator-release/pull/2) - Add support to release to a separate component repo ([@kpdecker](https://api.github.com/users/kpdecker))

- Do not require config module as global - a2f8d30
- Add error logging to npm and bower collectors - 5655691

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.4.0...v1.5.0)

## v1.4.0 - November 1st, 2013

- [#9](https://github.com/walmartlabs/generator-release/issues/9) - Diff npm tree in the diff generator ([@kpdecker](https://api.github.com/users/kpdecker))

- Allow for link collection when generating notes - 14380ee
- Allow rebuilding the current release docs - bb7f40c
- Allow config file to be passed as a cli argument - ccec4fc
- Allow for bower and npm aggregate diffing with collect-version and diff generators

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.3.0...v1.4.0)

## v1.3.0 - October 3rd, 2013

- [#6](https://github.com/walmartlabs/generator-release/pull/6) - add missing paren ([@patrickkettner](https://api.github.com/users/patrickkettner))
- [#8](https://github.com/walmartlabs/generator-release/issues/8) - Add skip-tests option ([@kpdecker](https://api.github.com/users/kpdecker))
- [#7](https://github.com/walmartlabs/generator-release/issues/7) - Add instructions to notes task ([@kpdecker](https://api.github.com/users/kpdecker))

- Update README.md - ad244e2

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.2.2...v1.3.0)

## v1.2.2 - September 11th, 2013

- [#5](https://github.com/walmartlabs/generator-release/issues/5) - Issue pingback fails when attempting to comment on fixed issues ([@kpdecker](https://api.github.com/users/kpdecker)

- Use last commit for issue tag checking - a7cb10a
- Remove dead code - 3dc4e44

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.2.1...v1.2.2)

## v1.2.1 - September 11th, 2013

- [#5](https://github.com/walmartlabs/generator-release/issues/5) - Issue pingback fails when attempting to comment on fixed issues ([@kpdecker](https://api.github.com/users/kpdecker)

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.2.0...v1.2.1)

## v1.2.0 - September 11th, 2013

- [#4](https://github.com/walmartlabs/generator-release/issues/4) - Handle Fixes comments in commits ([@kpdecker](https://api.github.com/users/kpdecker)

- Update to use chalk rathern than colors - da9b86c
- Support output to CHANGELOG.md - a7b8c9e
- Add log regarding status and npm publish - 20ce4e2
- Handle first version release - 85870ea
- Fix release notes - 42a7f18

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.1.0...v1.2.0)

## v1.1.0 - September 3rd, 2013

- [#3](https://github.com/walmartlabs/generator-release/issues/3) - Add dry-run support to notes generator
- [#1](https://github.com/walmartlabs/generator-release/issues/1) - Ping back on associated pull requests when a release is made

- Always overwrite release notes - d4021fb

[Commits](https://github.com/walmartlabs/generator-release/compare/v1.0.0...v1.1.0)

## v1.0.0 - August 30th, 2013

- Initial release

[Commits](https://github.com/walmartlabs/generator-release/compare/e2046c3...v1.0.0)
