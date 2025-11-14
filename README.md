# 9xcongit Installer

## Overview

The 9xcongit Installer is a shell script designed to automate the installation of 9xcongit, a lightweight Ubuntu environment running on Proot. This allows users to easily set up and run a customized Ubuntu system on various architectures.

## Prerequisites

Before you begin, ensure that the following are available on your system:

- A Bash shell environment
- Internet connectivity
- `wget` installed
- Supported CPU architectures:
  - x86_64 (amd64)
  - aarch64 (arm64)

## Installation

Follow these steps to install 9xcongit:

1. Clone the repository:
    ```bash
    git clone https://github.com/9xcongit/freeroot.git
    cd freeroot
    ```

2. Run the installer script:
    ```bash
    ./root.sh
    ```
    or
    ```bash
    bash root.sh
    ```

## Supported Architectures

- x86_64 (amd64)
- aarch64 (arm64)

## License

This project is licensed under the MIT License.

## Credits

- 9xcongit Installer is developed and maintained by [9xcongit.com](https://9xcongit.com).
- Special thanks to [dxomg](https://github.com/dxomg) for the Proot code that powers this installer.

## Disclaimer

This script is intended for educational and experimental purposes only. Use it responsibly and at your own risk.
