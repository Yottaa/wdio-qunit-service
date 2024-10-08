# Changelog

## [1.0.0](https://github.com/Yottaa/wdio-qunit-service/compare/v0.2.0...v1.0.0) (2024-08-12)


### ⚠ BREAKING CHANGES

* To avoid losing test context, removes the ability to collect test results if the tests are already completed in the browser when the service is inserted. Instead, a recommendation is made to disable test auto-start in QUnit and allow the service to start the tests itself. If this is infeasible, adding a manual delay in the tests will also serve to give the service time to enter the browser context prior to test completion.

### Features

* adds ability to autostart QUnit tests ([a55f94d](https://github.com/Yottaa/wdio-qunit-service/commit/a55f94de2bc521aeb8c5e2582b82e85fba3b45ae))
* Auto generate tests for QUnit ([#15](https://github.com/Yottaa/wdio-qunit-service/issues/15)) ([0b60bf5](https://github.com/Yottaa/wdio-qunit-service/commit/0b60bf5348305062f90a85b35fbfef3697b4d5c2))
* QUnit completed ([704a63d](https://github.com/Yottaa/wdio-qunit-service/commit/704a63d834fb301f18c436caa702a860608d127a))
* wdio qunit service ([d31b4d7](https://github.com/Yottaa/wdio-qunit-service/commit/d31b4d7ef9f4765833a41a876cbb25901bbd20f7))


### Bug Fixes

* fix issue with tests potentially being double-started, or started before being ready ([#2](https://github.com/Yottaa/wdio-qunit-service/issues/2)) ([da687d3](https://github.com/Yottaa/wdio-qunit-service/commit/da687d3bab537545a78872b907d016ad107c62e1))
* Get QUnit tests not included in a module ([fcecb15](https://github.com/Yottaa/wdio-qunit-service/commit/fcecb15bc46c1c45895a69d34eb6f8f496734083))
* Nested QUnit Modules ([6fa35d6](https://github.com/Yottaa/wdio-qunit-service/commit/6fa35d6d1ea2c72379acfc0ff7d9658e047e4c90))
* Version ([#1](https://github.com/Yottaa/wdio-qunit-service/issues/1)) ([b793c55](https://github.com/Yottaa/wdio-qunit-service/commit/b793c55ca99057a5674e4cf12c72b956e9904b5a))

## [0.2.0](https://github.com/mauriciolauffer/wdio-qunit-service/compare/v0.1.2...v0.2.0) (2024-06-14)


### Features

* Auto generate tests for QUnit ([#15](https://github.com/mauriciolauffer/wdio-qunit-service/issues/15)) ([0b60bf5](https://github.com/mauriciolauffer/wdio-qunit-service/commit/0b60bf5348305062f90a85b35fbfef3697b4d5c2))

## [0.1.2](https://github.com/mauriciolauffer/wdio-qunit-service/compare/v0.1.1...v0.1.2) (2024-06-06)


### Bug Fixes

* Get QUnit tests not included in a module ([fcecb15](https://github.com/mauriciolauffer/wdio-qunit-service/commit/fcecb15bc46c1c45895a69d34eb6f8f496734083))

## [0.1.1](https://github.com/mauriciolauffer/wdio-qunit-service/compare/v0.1.0...v0.1.1) (2023-11-30)

### Bug Fixes

- Nested QUnit Modules ([6fa35d6](https://github.com/mauriciolauffer/wdio-qunit-service/commit/6fa35d6d1ea2c72379acfc0ff7d9658e047e4c90))

## 0.1.0 (2023-10-13)

### Features

- QUnit completed ([704a63d](https://github.com/mauriciolauffer/wdio-qunit-service/commit/704a63d834fb301f18c436caa702a860608d127a))
- wdio qunit service ([d31b4d7](https://github.com/mauriciolauffer/wdio-qunit-service/commit/d31b4d7ef9f4765833a41a876cbb25901bbd20f7))

### Bug Fixes

- Version ([#1](https://github.com/mauriciolauffer/wdio-qunit-service/issues/1)) ([b793c55](https://github.com/mauriciolauffer/wdio-qunit-service/commit/b793c55ca99057a5674e4cf12c72b956e9904b5a))
