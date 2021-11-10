# yocto-manifests

[![ci](https://github.com/jhnc-oss/yocto-manifests/actions/workflows/ci.yml/badge.svg)](https://github.com/jhnc-oss/yocto-manifests/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

Repository manifests for Yocto build.

## Example

```sh
# Install dependencies
pip install -U gitrepo

repo init -u https://github.com/jhnc-oss/yocto-manifests.git -b dunfell
repo sync
```
