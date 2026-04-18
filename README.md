# External Utils

Utility helper module used by `main-project` as a Git submodule dependency.

## Exported Function

- `Get-UtilsMessage` -> returns a sample utility message

## Usage

```powershell
Import-Module .\utils.psm1 -Force
Get-UtilsMessage
```

## Purpose

This repository demonstrates how auxiliary helper modules can be maintained
separately and integrated into a primary project through submodules.
