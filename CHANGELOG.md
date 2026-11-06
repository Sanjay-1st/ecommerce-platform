# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
_Nothing yet._

## [0.1.1] - 2026-11-06
### Fixed
- `ecommerce/src/App.js`: added missing `import React from 'react'`, which was causing a hard build failure ("Failed to compile") under this project's ESLint config.

## [0.1.0] - 2023-01-09
### Added
- Storefront (`ecommerce`) combined with the admin panel into this single monorepo. Product browsing, login page.

## [0.0.1] - 2022-08-20
### Added
- Admin panel (`myadmin`): sign in, customer list/add, product list/add.
