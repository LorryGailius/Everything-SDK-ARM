# Everything SDK — ARM Edition

[![Build ARM & ARM64](../../actions/workflows/build.yml/badge.svg)](../../actions/workflows/build.yml)
[![Release](../../actions/workflows/release.yml/badge.svg)](../../actions/workflows/release.yml)

The original [voidtools Everything SDK](https://www.voidtools.com/support/everything/sdk/) with additional **ARM** and **ARM64** DLLs, built from the unmodified SDK source code.

## What's included

The release package contains the complete, unmodified Everything SDK plus two additional binaries:

| File | Architecture | Type |
|------|-------------|------|
| `dll/Everything32.dll` | x86 | Original |
| `lib/Everything32.lib` | x86 | Original |
| `dll/Everything64.dll` | x64 | Original |
| `lib/Everything64.lib` | x64 | Original |
| `dll/EverythingARM.dll` | ARM | **Added** |
| `lib/EverythingARM.lib` | ARM | **Added** |
| `dll/EverythingARM64.dll` | ARM64 | **Added** |
| `lib/EverythingARM64.lib` | ARM64 | **Added** |

All ARM binaries export the same functions as the original x86/x64 DLLs.

## Downloads

Grab the latest release from the [Releases](../../releases) page. Each release zip contains the full SDK (headers, source, examples, and all DLLs/LIBs for x86, x64, ARM, and ARM64).

## License

The Everything SDK is copyright © David Carpenter and licensed under the MIT License.

The build scripts and CI configuration in this repository are provided under the same MIT License.
