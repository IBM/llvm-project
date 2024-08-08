# The LLVM Project on PowerPC

This repository is the host website for the release of the [LLVM Compiler](https://github.com/llvm/llvm-project) for PowerPC architecture.

This is a third-party release of llvm on PowerPC and is not an official part of the [llvm-project's release](https://github.com/llvm/llvm-project/releases),
its purpose is to provide tested and pre-built binaries for the PowerPC target.

This repository _**does not**_ contain any of the source code used to build the binaries present under https://github.com/IBM/llvm-project/releases,
the files in each release named `Source code(zip / tar.gz)` are automated packaging of the lisencing info in this repository.

The tags and releases versions in [this repository](https://github.com/IBM/llvm-project/releases) mirror the [official llvm-project release](https://github.com/llvm/llvm-project/releases).
The source code for a release should be downloaded from the corresponding release tagged on the official page.

Pre-built binaries for each release should be verified against the sha1 checksum value posted on release to the official llvm-project discourse threads: https://discourse.llvm.org/tag/release

This repository is controlled and maintained by the community of LLVM committers that support the PowerPC Target in the llvm-project,
issues for the PowerPC backend should be filed under the PowerPC label in the official llvm-project website: https://github.com/llvm/llvm-project/labels/backend%3APowerPC
