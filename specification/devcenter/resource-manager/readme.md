# devcenter

> see https://aka.ms/autorest

This is the AutoRest configuration file for devcenter.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for devcenter.

```yaml
openapi-type: arm
openapi-subtype: rpaas
tag: package-2022-09-01-preview
```

### Tag: package-2022-08-01-preview

These settings apply only when `--tag=package-2022-08-01-preview` is specified on the command line.

```yaml $(tag) == 'package-2022-08-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2022-08-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-08-01-preview/vdi.json
```

### Tag: package-2022-09-01-preview

These settings apply only when `--tag=package-2022-09-01-preview` is specified on the command line.

```yaml $(tag) == 'package-2022-09-01-preview'
input-file:
  - Microsoft.DevCenter/preview/2022-09-01-preview/devcenter.json
  - Microsoft.DevCenter/preview/2022-09-01-preview/vdi.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

```yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-js
  - repo: azure-cli-extensions
```
## Az

See configuration in [readme.az.md](./readme.az.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)

## Go

See configuration in [readme.go.md](./readme.go.md)
