# vulkan-sdk-arm

This repository contains a Github Action workflow, which builds the Vulkan SDK for ARM runners.

The released packages are used by [jakoch/install-vulkan-sdk-action](https://github.com/jakoch/install-vulkan-sdk-action).

## Availability of Vulkan SDK ARM64 Prebuilt Binaries for Linux

Currently, KHRONOS has no plans to modify the official tarball to include prebuilt ARM binaries or to update the Ubuntu packages for ARM.

This repository automates the process by downloading the official Vulkan SDK tarball, building it for ARM, and repackaging the necessary binaries into the SDK.
