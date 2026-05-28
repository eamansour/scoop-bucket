# Galasa Scoop Bucket

This repository contains Scoop manifests for the Galasa Command-Line interface (galasactl) for Windows.

## Copyright

Copyright contributors to the Galasa project  
SPDX-License-Identifier: EPL-2.0

## Prerequisites

Before installing galasactl, you need to have Scoop installed on your Windows system.

### Installing Scoop

See Scoop's [installation instructions](https://scoop.sh/).

## How do I install galasactl?

Firstly add the galasa bucket:
```powershell
scoop bucket add galasa https://github.com/galasa-dev/scoop-bucket
```

To install galasactl on the latest version:

```powershell
scoop install galasactl
```

To install galasactl on a specific version:

```powershell
scoop install galasactl@<version> # e.g. galasactl@0.43.0
```

## Updating galasactl

If you installed `galasactl` with the latest version:

```powershell
scoop update galasactl
```

Otherwise, if you installed `galasactl` with a specific version, you'll have to uninstall and re-install:

```powershell
scoop uninstall galasactl
scoop cache rm galasactl
scoop install galasactl
```

## Uninstalling galasactl

To remove galasactl:

```powershell
scoop uninstall galasactl
```

## Supported Architecture

The Galasa Command-Line interface supports:
- Windows x86_64 (64-bit)
