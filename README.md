# travis-ci

Repository used for [sharing Travis CI build configs](https://docs.travis-ci.com/user/build-config-imports/) across repositories.

## How to use

1. Enable [Build Config Validation](https://docs.travis-ci.com/user/build-config-validation) by adding `version: ~> 1.0` at the beginning of `.travis.yml`.
2. Add imports statements.

Example:
```yml
version: ~> 1.0
import:
  - nbbrd/travis-ci:config/java8_library_with_binaries.yml@main
```
