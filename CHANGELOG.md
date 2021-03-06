# Change Log

All notable changes to the "test-runner" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

# 1.2.0 [unreleased]

enhancement:

- **Converted** to typescript [#16]https://github.com/EricTurf/vscode-test-runner/pull/16

# 1.1.1 [2019-09-21]

enhancement

- **Created** logger class that will log messages to the Output tab [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)
- **Abstracted** logic to get test file path [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)
- **Refactored** logic to get the relative file path from the cwd [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)
- **Refactored** logic to get cwd by scanning every single directory for a package.json [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)

bug fix

- **Fixed** an issue where you could not test files in a project nested 2+ directories deep [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)

# 1.1.0 [2019-09-03]

enhancement

- **Added** the ability to use typescript test files [#15](https://github.com/EricTurf/vscode-test-runner/pull/15)
- **Added** logging in case of errors (see in Output > Test Runner tab) [#14](https://github.com/EricTurf/vscode-test-runner/pull/14)
- **Improved** test file resolution logic [#14](https://github.com/EricTurf/vscode-test-runner/pull/14)

# 1.0.5 [2019-05-09]

enhancement

- **Added** the ability to set your preferred package manager with settings "test-runner.packageManager" [#10](https://github.com/EricTurf/vscode-test-runner/pull/10)

## 1.0.4 [2018-12-10]

enhancement

- **Added** the ability to attempt to run tests from respective file [#6](https://github.com/EricTurf/vscode-test-runner/pull/6)

## 1.0.3 [2018-11-29]

enhancement

- **Added** the ability to run tests in directories with nested `package.json` [#4](https://github.com/EricTurf/vscode-test-runner/pull/4)

## 1.0.2 [2018-11-19]

:bug:

- **Fixed** bug preventing to start a new terminal if the first one was closed [#3](https://github.com/EricTurf/vscode-test-runner/pull/3)

## 1.0.1 [2018-11-12]

:bug:

- **Fixed** bug where the wrong workspace root folder was being selected

## [1.0.0]

- Initial release
