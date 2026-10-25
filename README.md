# Local Manifests for Xiaomi Redmi 13 5G / POCO M6 Plus 5G (breeze)

This repository provides the local manifest (`breeze.xml`) for building **Project Infinity-X 4.1 (Android 17)** for `breeze`.

## Usage
Clone this repository directly into `.repo/local_manifests` of your Infinity-X source tree:

```bash
git clone https://github.com/nithishlabs08/android_local_manifests.git .repo/local_manifests
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune -j$(nproc)
```
