# asdf-troubleshoot-live

[![Build Status](https://travis-ci.com/adyatlov/asdf-troubleshoot-live.svg?branch=master)](https://travis-ci.com/adyatlov/asdf-troubleshoot-live)

This is an [ASDF](https://github.com/asdf-vm/asdf) plugin for the [troubleshoot-live](https://github.com/mhrabovcin/troubleshoot-live) CLI tool.

## Prerequisites

- ASDF version management tool - [installation instructions](https://asdf-vm.com/guide/getting-started.html)
- Go 1.20 or newer - [installation instructions](https://golang.org/doc/install)

## Installation

To install the plugin, run the following command:

```
asdf plugin add troubleshoot-live https://github.com/adyatlov/asdf-troubleshoot-live.git
```

## Usage

1. Install a specific version of troubleshoot-live:

   ```
   asdf install troubleshoot-live <version>
   ```

   Replace `<version>` with the desired version number (e.g., `v1.0.0`) or with `latest` for the latest version.

   To list all the available versions launch the following command:

   ```
   asdf list all troubleshoot-live
   ```

1. Choose a version of the tool you are going to use:

   Set a defaul version that will be used globally

   ```
   asdf global troubleshoot-live <version>
   ```

   Set a specific version only for a current directory and all subdirectories:

   ```
   asdf global troubleshoot-live <version>
   ```

1. Use troubleshoot-live:

   ```
   troubleshoot-live --help
   ```

For more information on how to use ASDF, check the [official documentation](https://asdf-vm.com/#/core-commands).

## Contributing

If you find any issues or would like to contribute to this plugin, please feel free to open an issue or create a pull request in this repository.

## License

This project is licensed under the [Apache License, Version 2.0](LICENSE).
