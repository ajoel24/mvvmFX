# Changelog

## [2.0.0] - Unreleased

### Breaking Changes
- Migrated namespace from `de.saxsys` to `io.github.ajoel24`.
- Minimum Java version is now 25.
- Migrated CDI/Spring Boot modules to Jakarta EE namespace.
- Replaced `mvvmfx-easydi` with new `mvvmfx-micronaut` module.

### Changed
- Updated all dependencies to Java 25-compatible versions.
- Replaced Travis CI with GitHub Actions.
- Migrated tests from JUnit 4 to JUnit 5.
- Replaced `eu.lestard:advanced-bindings` with standard JavaFX bindings.
- Inlined `eu.lestard:doc-annotations` and `eu.lestard:assertj-javafx` functionality.

### Removed
- Support for Java 8.
- `mvvmfx-easydi` module (use `mvvmfx-micronaut` instead).
- All `eu.lestard` dependencies.