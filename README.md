# curl-8.22.0_1-win64-mingw

Prebuilt curl 8.22.0 libraries and headers for Windows x64, used as an
immutable pinned fallback dependency by Kurlyk.

## Provenance

```text
Upstream:             curl-for-win, curl project
Version:              8.22.0 (build 8.22.0_1)
Original filename:    curl-8.22.0_1-win64-mingw.zip
Original download URL: https://curl.se/windows/dl-8.22.0_1/curl-8.22.0_1-win64-mingw.zip
SHA256:               7f23b039f6ea4197362d4468e1a0e71428201222e1bef3b680d5ef7b2aefb714
Retrieved on:         2026-09-21
Architecture:         Windows x64
Toolchain / package type: LLVM-MinGW / curl-for-win shared DLL + MinGW import library
```

The SHA256 value is the checksum published on the official curl for Windows
download page. The repository contains the extracted development files needed
by the Kurlyk CMake fallback; the original ZIP is not stored here.

Checksum source: <https://curl.se/windows/>

## Contents

```text
include/curl/...
bin/libcurl-x64.dll
lib/libcurl.dll.a
COPYING.txt
```

The snapshot is intentionally kept at a fixed commit. Update it by importing a
new upstream archive into a new commit and recording its provenance above.
