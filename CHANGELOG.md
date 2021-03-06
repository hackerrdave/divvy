# Divvy Changelog

## v1.3.0 (2018-06-06)

* Feature: Add support for JSON-based configuration.

## v1.2.0 (2018-04-27)

* Protocol Documentation: Clarify the valid range of values for `creditLimit` and `resetSeconds`.
* Validation: Moved validation of `resetSeconds` from rule evaluation time to configuration parse time, and added validation for `creditLimit`.

## v1.1.0 (2017-08-15)

* Feature: Enable Prometheus metric scraping by exporting `HTTP_SERVICE_PORT` and `PROMETHEUS_METRICS_PATH` environment variables.

## v1.0.1 (2017-05-03)

* Bugfix: If an operation contained a glob value, any operations after it were ignored when testing the operation.
* Bumped recommended Node version to v6.10.x or greater.
* Switched code linter to eslint.

## v1.0.0 (2016-10-10)

* Initial release.
