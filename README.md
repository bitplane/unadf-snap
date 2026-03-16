# unadf-snap

Snap package for [unadf](https://github.com/adflib/ADFlib), a command-line
utility for extracting files from Amiga Disk File (.adf) dumps.

The Debian/Ubuntu package is stuck at version 0.7.11a from 2007 and segfaults
on many real-world ADF files. This snap packages the current upstream release.

## Install

```bash
snap install unadf --classic
```

## Usage

```bash
unadf -d output_dir/ disk.adf
unadf -l disk.adf              # list contents
unadf -r disk.adf              # list directory tree
```

## Build

```bash
snapcraft
```
