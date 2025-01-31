# LosslessCut Winget Release
![Latest Release](https://img.shields.io/github/v/release/chrishuan9/losslesscut-winget-rls
)
![GitHub License](https://img.shields.io/github/license/chrishuan9/losslesscut-winget-rls)
![Build](https://github.com/chrishuan9/losslesscut-winget-rls/actions/workflows/create_release.yaml/badge.svg)

## Overview

This repository is designed to repack the latest release of **Lossless Cut** from [mifi/lossless-cut](https://github.com/mifi/lossless-cut) and package it as a ZIP file for installation on Windows using **winget**. 

## Important Notes

- This repository is **not affiliated** with the developers of [Lossless Cut](https://github.com/mifi/lossless-cut).
- I do **not provide any support** for the software.
- The code is **not modified** in any way.
- All logic for the repackaging process is implemented in the GitHub Action located at [create_release.yaml](.github/workflows/create_release.yaml).

## Installation

To install Lossless Cut using winget, you can use the following command:

```bash
winget install ch.LosslessCut
```
## Repository Structure

- `.github/workflows/create_release.yaml`: Contains the GitHub Action logic for repackaging the latest release.
- `README.md`: This documentation file.

## License

This project is licensed under the LGPL-2.1. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Lossless Cut](https://github.com/mifi/lossless-cut) for the original software.
- [winget](https://winget.run/) for the Windows package manager.

Feel free to explore the repository and contribute if you wish!