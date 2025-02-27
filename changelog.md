# Changelog
This file contains all the notable changes done to the Ballerina java.jdbc package through the releases.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed
- [Improve API documentation to reflect query usages](https://github.com/ballerina-platform/ballerina-standard-library/issues/2524)

## [1.3.0] - 2022-01-29

### Changed
- [Fix Compiler plugin crash when variable is passed for `sql:ConnectionPool`](https://github.com/ballerina-platform/ballerina-standard-library/issues/2536)

## [1.2.1] - 2022-02-03

### Changed
- [Fix Compiler plugin crash when variable is passed for `sql:ConnectionPool`](https://github.com/ballerina-platform/ballerina-standard-library/issues/2536)

## [1.2.0] - 2021-12-13

### Changed
- Release module on top of Swan Lake Beta6 distribution

## [1.1.0] - 2021-11-20

### Added
- [Tooling support for JDBC client](https://github.com/ballerina-platform/ballerina-standard-library/issues/2280)

### Changed
- [Change queryRow return type to anydata](https://github.com/ballerina-platform/ballerina-standard-library/issues/2390)

## [1.0.0] - 2021-10-09

### Changed
- [Add completion type as nil in SQL query return stream type](https://github.com/ballerina-platform/ballerina-standard-library/issues/1654)

### Added
- [Add support for queryRow](https://github.com/ballerina-platform/ballerina-standard-library/issues/1604)
- [Add support for configuring the retrieval of auto generated keys on query execution](https://github.com/ballerina-platform/ballerina-standard-library/issues/1804)

## [0.6.0-beta.2] - 2021-06-22

### Changed
- [Change default rowType of the query remote method from `nil` to `<>`](https://github.com/ballerina-platform/ballerina-standard-library/issues/1445)
- [Remove support for string parameter in SQL APIs](https://github.com/ballerina-platform/ballerina-standard-library/issues/2010)

## [0.6.0-beta.1] - 2021-06-02

### Changed
- Make JDBC Client class isolated
