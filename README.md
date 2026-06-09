# rift-snapshot

Personal patched Rift snapshot for `jparklev/codex-sdk-runner`.

This package is generated from [`jparklev/rift`](https://github.com/jparklev/rift), branch `dev`, commit `772d080`.

It currently ships patched `darwin-arm64` prebuilds for Josh's Codex workflow runner:

- `bin/rift.js`
- `prebuilds/darwin-arm64/rift`
- `prebuilds/darwin-arm64/librift_ffi.dylib`

The package is intentionally platform-scoped to `darwin/arm64` so another platform does not install a stale or unpatched binary by accident.
