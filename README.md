# Bazel Rules for Transmission

[![Build](https://github.com/filmil/bazel_rules_transmission/actions/workflows/build.yml/badge.svg)](https://github.com/filmil/bazel_rules_transmission/actions/workflows/build.yml)

This repository provides Bazel rules for building the
[Transmission](https://transmissionbt.com/) BitTorrent client.

# Maintenance

## Build

```
bazel build //third_party/transmission/...
```

This will build the Transmission client and all of its dependencies.
