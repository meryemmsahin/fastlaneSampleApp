fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios ci_tests

```sh
[bundle exec] fastlane ios ci_tests
```

Pull Request açıldığında unit testleri çalıştırır

### ios deploy_to_firebase

```sh
[bundle exec] fastlane ios deploy_to_firebase
```

Develop branch'ine pushlandığında Firebase'e deploy eder

### ios deploy_to_testflight

```sh
[bundle exec] fastlane ios deploy_to_testflight
```

Main branch'ine pushlandığında TestFlight'a gönderir

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
