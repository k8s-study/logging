# Logging Convention


## Rules

### Specify the log `level` according to following the `level` definitions.

| Level | Description |
| :---: | :--- |
| `TRACE` | Logging from external libraries used by your app or very detailed application logging. |
| `DEBUG` | Anything else, i.e. too verbose to be included in "info" level. Report calls of important functions along with results they return and values of specific variables, or parameters. |
| `INFO` | Detail on regular operation. Informative messages should not be reported too frequently because they can quickly become noise. |
| `WARN` | A note on something that should probably be looked at by an operator eventually. |
| `ERROR` | Fatal for a particular request, but the service/app continues servicing other requests. An operator should look at this soon. |
| `FATAL` | The service/app is going to stop or become unusable now. An operator should definitely look into this soon. |


## Examples
