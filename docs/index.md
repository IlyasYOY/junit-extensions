---
layout: default
---

Introduction
======

Provides the following features, implemented using [JUnit Jupiter's Extension Model](http://junit.org/junit5/docs/current/user-guide/#extensions): 

- `BenchmarkExtension`: publishes test elapsed time to the console, by default, but also available via the `EngineExecutionListener` for customised reporting

- `ExpectedExceptionExtension`: allows you to run a test method with an expected exception and (optionally) exception message, delegating responsibility for making the assertion to the extension

- `RandomBeansExtension`: allows you to inject random instances of classes into your tests, useful when you need a class instance to test with but you don't care about its contents

- `SystemPropertyExtension`: allows you to set system properties before test execution and reverts these changes on test completion

- `TemporaryFolderExtension`: allows you to create temporary files and directories in your tests, any such files or directories created in your tests are removed for you when the tests complete

- `TestNameExtension`: makes the current test name available inside test methods

- `WatcherExtension`: logs test execution flow including entry, exit and elapsed time in milliseconds

#### Further Reading

Follow the links in the side bar to read about each of these extensions.

