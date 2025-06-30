# Bazel Rules for Transmission

This repository provides Bazel rules for building the [Transmission](https://transmissionbt.com/) BitTorrent client.

## Usage

To use these rules, add the following to your `MODULE.bazel` file:

```starlark
bazel_dep(name = "rules_transmission", version = "0.0.1")
```

## Building Transmission

To build Transmission, you can use the provided rules in your `BUILD.bazel` file. For example:

```starlark
load("@rules_transmission//third_party/transmission:transmission.bzl", "transmission")

transmission(
    name = "my_transmission",
)
```

This will build the Transmission client and all of its dependencies.
