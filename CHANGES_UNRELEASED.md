**See [the release process docs](docs/howtos/cut-a-new-release.md) for the steps to take when cutting a new release.**

# Unreleased Changes

[Full Changelog](https://github.com/mozilla/application-services/compare/v0.52.0...master)

## Sync

### What's fixed

- Rust sync code should be more robust in the face of corrupt meta/global
  records. ([#2688](https://github.com/mozilla/application-services/pull/2688))

## FxA Client

### What's changed

- The `ensureCapabilities` method will not perform any network requests if the
  given capabilities are already registered with the server.
  ([#2681](https://github.com/mozilla/application-services/pull/2681)).