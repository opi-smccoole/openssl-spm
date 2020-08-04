# openssl-spm

## DO NOT USE THIS REPOSITORY FOR PRODUCTION PROJECTS!

**NOTICE:** This repository was created as part of bug reports for the Swift Package Manager.  It is not warrantied or guaranteed in any way and should not be used in any sort of product or project.

This repository provides a copy of [OpenSSL](https://www.openssl.org/) 1.1.1g built as a static [xcframework](https://developer.apple.com/videos/play/wwdc2020/10147) for iOS and wrapped for use via [Swift Package Manager](https://swift.org/package-manager/) (SPM).

The OpenSSL xcframework was built using the scripts from this [github repository](https://github.com/balthisar/openssl-xcframeworks) with some slight modifications due to errors building for Catalyst.  Since only the iOS targets were needed the changes and configuration options used were just to build them.

