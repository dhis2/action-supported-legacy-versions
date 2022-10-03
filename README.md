# action-supported-legacy-versions

Get the backend versions the app will run on except the latest one

## Inputs

### `instance-url-latest`

The URL to the instance with the latest version. Required if maxDHIS2Version is not specified in d2.config

### `username`

The DHIS2 username for authentication. Required if maxDHIS2Version is not specified in d2.config

### `password`

The DHIS2 password for authentication. Required if maxDHIS2Version is not specified in d2.config

### `config-dir``

Optionally specifiy a relative directory for the d2.config file

## Outputs

### `versions`

An array containing the supported legacy versions

## Example

```
uses: dhis2/action-supported-legacy-versions@v1
with:
```
