# VL.FsNotify
VL wrapper for [FsNotify](https://github.com/sjp/FsNotify), improved filesystem notification events for .NET

## What's inside

Wraps FsNotify's `EnhancedObservableFileSystemWatcher` in a convenient node that gives access to the following events :

- `Changed`
- `Created`
- `Deleted`
- `Renamed`
- `Error`
- `AttributeChanged`
- `CreationTimeChanged`
- `LastAccessChanged`
- `LastWriteChanged`
- `SecurityChanged`
- `SizeChanged`

If you enable the _Advanced_ tag, you'll also get access to the full library that's realy easy to patch with.

## Installation

```
nuget install VL.FsNotify
```