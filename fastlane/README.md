fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

### buildAndDistribute

```sh
[bundle exec] fastlane buildAndDistribute
```

Lane for Incrementing versionCode, Firebase app distribution, Play store upload & Git commit

### incrementVersionCodeInProjectGradle

```sh
[bundle exec] fastlane incrementVersionCodeInProjectGradle
```

Lane for fetching version code from play console and incrementing version code.

### distributeReleaseBuildToFirebase

```sh
[bundle exec] fastlane distributeReleaseBuildToFirebase
```

Lane for distributing Release app using Firebase App Distributions.

### buildApk

```sh
[bundle exec] fastlane buildApk
```

Lane for building the .apk file.

### buildBundle

```sh
[bundle exec] fastlane buildBundle
```

Lane for building the .aab file.

### distributeToPlayStore

```sh
[bundle exec] fastlane distributeToPlayStore
```

Lane for uploading .aab to play store.

### commitCodeToGit

```sh
[bundle exec] fastlane commitCodeToGit
```

Lane for git commit.

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
