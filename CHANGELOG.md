# Changelog

All notable changes to this project will be documented in this file.

## [2.5.0](https://github.com/jthegedus/forok-asdf-actions/compare/v2.4.0...v2.5.0) (2023-03-14)


### Miscellaneous Chores

* release 2.5.0 ([52e4745](https://github.com/jthegedus/forok-asdf-actions/commit/52e47450f5a44c1cf46998fa48ed95f2b8610d4a))

## [2.4.0](https://github.com/jthegedus/forok-asdf-actions/compare/v2.3.0...v2.4.0) (2023-03-14)


### Miscellaneous Chores

* release 2.4.0 ([8b0d743](https://github.com/jthegedus/forok-asdf-actions/commit/8b0d7435bbedb6ab4c51b11cfe274bf5600e723d))

## [2.3.0](https://github.com/jthegedus/forok-asdf-actions/compare/v2.2.0...v2.3.0) (2023-03-14)


### Miscellaneous Chores

* release 2.3.0 ([91d1888](https://github.com/jthegedus/forok-asdf-actions/commit/91d18885dfff0051a883b536c744d9a562ba3f24))

## [2.2.0](https://github.com/jthegedus/forok-asdf-actions/compare/v2.0.0...v2.2.0) (2023-03-13)


### ⚠ BREAKING CHANGES

* Update actions to use node16 ([#488](https://github.com/jthegedus/forok-asdf-actions/issues/488))

### Features

* Update actions to use node16 ([#488](https://github.com/jthegedus/forok-asdf-actions/issues/488)) ([6844d09](https://github.com/jthegedus/forok-asdf-actions/commit/6844d09b13209e7d2ce3b63d2b089a2acef581ec))


### Bug Fixes

* update codeql for dependabot compat ([3f6d713](https://github.com/jthegedus/forok-asdf-actions/commit/3f6d71382fe4c7807936733d72aef7ee6e56e7a9))
* use correct trigger type ([d464031](https://github.com/jthegedus/forok-asdf-actions/commit/d4640312f060abdd98823bf6bd9a2758851133c2))


### Miscellaneous Chores

* release 2.1.0 ([5314156](https://github.com/jthegedus/forok-asdf-actions/commit/5314156089f46494f980d865468084adf0d141ef))
* release 2.2.0 ([42b3f29](https://github.com/jthegedus/forok-asdf-actions/commit/42b3f295eccef06c81c298c5248d36d4a0cf0a72))
* Update actions to use node16 ([#488](https://github.com/jthegedus/forok-asdf-actions/issues/488)) ([2f61da5](https://github.com/jthegedus/forok-asdf-actions/commit/2f61da5af7da0a1216219da51d0718c25e159a77))

## [2.0.0](https://github.com/asdf-vm/actions/compare/v1.1.0...v2.0.0) (2023-03-09)

### ⚠ BREAKING CHANGES

- Update actions to use node16
  ([#488](https://github.com/asdf-vm/actions/issues/488))
  ([6844d09](https://github.com/asdf-vm/actions/commit/6844d09b13209e7d2ce3b63d2b089a2acef581ec))
  - released by
    ([2f61da5](https://github.com/asdf-vm/actions/commit/2f61da5af7da0a1216219da51d0718c25e159a77))

### Bug Fixes

- update codeql for dependabot compat
  ([3f6d713](https://github.com/asdf-vm/actions/commit/3f6d71382fe4c7807936733d72aef7ee6e56e7a9))
- use correct trigger type
  ([d464031](https://github.com/asdf-vm/actions/commit/d4640312f060abdd98823bf6bd9a2758851133c2))

## [1.1.0] - 2020-12-22

### Added

- Add the `github_token` input and set by default a token with only the
  necessary and sufficient privileges available only to the running job. In
  other words, users do not need to set this themselves except in exceptional
  cases. It's automatically exported in the runners as `GITHUB_API_TOKEN`.

## [1.0.1] - 2020-10-10

### Changed

- Port entire action to TypeScript from a runner plugin so it's easier to
  collaborate and accept contributions

## [1.0.0] - 2020-05-16

- Initial version

[unreleased]: https://github.com//asdf-vm/actions/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/asdf-vm/actions/compare/v1.0.0...v1.1.0
[1.0.1]: https://github.com/asdf-vm/actions/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/asdf-vm/actions/releases/tag/v1.0.0
