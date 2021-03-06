# Changelog

## Version 0.2.1

- Now everything is tested inside the `docker`-containers and `OSX` images on `travis`.
- Added autodeploy to `bintray` in `.travis.yml`.
- Added `.ci/` folder for continuous integration, refactored `utils/` folder.
- Added `CONTRIBUTING.md` and `LICENSE.md`.
- New brand logo in the `README.md`.
- Everything is `shellcheck`ed (except `tests/`).

## Version 0.2.0

- Added `changes` command to see the difference between current version of the hidden files and the commited one
- Added `-f` option to the `reveal` command to remove prompts
- Changed the way files were decrypted, now it is a separate function
- Some bugs are fixed
- New installation instructions

## Version 0.1.2

- Added `-i` option to the `git-secret-add` command, which auto adds unignored files to the `.gitignore`
- Documentation improved with `Configuration` section
- Added extra tests: for custom filenames and new features
- `Makefile` improvements with `.PHONY` and `install` target
- `.github` templates added

## Version 0.1.1

- Added `--dry-run` option to the `git secret` command, which prevents any actions.
- Now `install_full_fixture()` returns a fingerprint
- Now `uninstall_full_fixture()` receives two args
- Fixed bug, when tests were failing with `gpg2`
- New travis strategy: testing both `gpg` and `gpg2`
- Removed animation from docs, now using `asciinema.org`

## Version 0.1.0

- Initial release
