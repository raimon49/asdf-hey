# asdf-hey

[![plugin test](https://github.com/raimon49/asdf-hey/workflows/plugin%20test/badge.svg)](https://github.com/raimon49/asdf-hey/actions/workflows/asdf.yml)
[![Build Status](https://travis-ci.org/raimon49/asdf-hey.svg?branch=master)](https://travis-ci.org/raimon49/asdf-hey)

[hey](https://github.com/rakyll/hey) as a tiny program that sends some load tool plugin for [asdf version manager](https://asdf-vm.com/)

## Installation

```bash
$ asdf plugin add hey https://github.com/raimon49/asdf-hey.git
```

## Usage

```bash
# Install any version of hey
$ asdf install hey v0.1.4

# Set the version of hey you want
$ asdf global hey v0.1.4
$ hey --version
hey version v0.1.4
```

## License

[MIT License](LICENSE)
