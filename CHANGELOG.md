# [1.1.0](https://github.com/karan-cd/terraform-hcloud-dns/compare/v1.0.0...v1.1.0) (2026-06-30)


### Features

* added the workflow yml ([8e614b6](https://github.com/karan-cd/terraform-hcloud-dns/commit/8e614b68d1c3bab299a8b063fd24cf05a87068bf))

# 1.0.0 (2026-06-30)


### Bug Fixes

* examples now use root module with source = ../../ ([95a2854](https://github.com/karan-cd/terraform-hcloud-dns/commit/95a2854f2e03ef38435f5947a5dec0773eadb6c5))
* remove unused variables from examples ([212a73a](https://github.com/karan-cd/terraform-hcloud-dns/commit/212a73a0e2ceb0a74341691de3b143fe82c8d594))
* updated the ci.yml ([d3f5d17](https://github.com/karan-cd/terraform-hcloud-dns/commit/d3f5d1737ecccb46f562287e6e4560500f4a2b45))
* use correct hcloud_zone and hcloud_zone_record resources ([7180805](https://github.com/karan-cd/terraform-hcloud-dns/commit/71808053293d640a69d16b24ea1fad23cd162ace))
* use correct zone argument for hcloud_zone_record ([905575e](https://github.com/karan-cd/terraform-hcloud-dns/commit/905575e2e87d80c0601fc90758dadae596dab0f8))


### Features

* add pre-commit, semantic-release, and improve examples ([325c32f](https://github.com/karan-cd/terraform-hcloud-dns/commit/325c32f6ff1c65a27fc375a954caec0acd173fa3))
* **ci:** migrate module to use smurf and add pr checks workflows ([#1](https://github.com/karan-cd/terraform-hcloud-dns/issues/1)) ([c0745de](https://github.com/karan-cd/terraform-hcloud-dns/commit/c0745de6dfbc158ad724d9636c900a34497809c1))
* improve DNS module maturity ([8392f44](https://github.com/karan-cd/terraform-hcloud-dns/commit/8392f449ca6d005ebe29c60691e27413302f82e3))
* initial terraform-hcloud-dns module with zone and records submodules ([84fffb8](https://github.com/karan-cd/terraform-hcloud-dns/commit/84fffb830cde09a596d413851d9b311e1331cb7d))

# [0.4.0](https://github.com/terraform-hc-modules/terraform-hcloud-dns/compare/v0.3.0...v0.4.0) (2026-04-22)


### Features

* **ci:** migrate module to use smurf and add pr checks workflows ([#1](https://github.com/terraform-hc-modules/terraform-hcloud-dns/issues/1)) ([c0745de](https://github.com/terraform-hc-modules/terraform-hcloud-dns/commit/c0745de6dfbc158ad724d9636c900a34497809c1))

# [0.3.0](https://github.com/terraform-hc-modules/terraform-hcloud-dns/compare/v0.2.1...v0.3.0) (2026-04-20)


### Features

* improve DNS module maturity ([8392f44](https://github.com/terraform-hc-modules/terraform-hcloud-dns/commit/8392f449ca6d005ebe29c60691e27413302f82e3))

## [0.2.1](https://github.com/terraform-hc-modules/terraform-hcloud-dns/compare/v0.2.0...v0.2.1) (2026-04-20)


### Bug Fixes

* examples now use root module with source = ../../ ([95a2854](https://github.com/terraform-hc-modules/terraform-hcloud-dns/commit/95a2854f2e03ef38435f5947a5dec0773eadb6c5))

# [0.2.0](https://github.com/terraform-hc-modules/terraform-hcloud-dns/compare/v0.1.0...v0.2.0) (2026-04-20)


### Features

* add pre-commit, semantic-release, and improve examples ([325c32f](https://github.com/terraform-hc-modules/terraform-hcloud-dns/commit/325c32f6ff1c65a27fc375a954caec0acd173fa3))

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-04-20

### Added

- Initial release
- Core module functionality
- Basic and complete examples
- CI/CD with terraform validation, tflint, tfsec, checkov
- Wrappers for for_each usage

[0.1.0]: https://github.com/terraform-hc-modules/terraform-hcloud-dns/releases/tag/v0.1.0
