## Maldua's pimbra-config

## Introduction

This repo will have tags equivalent to the upstream Zimbra tags (starting from 10.1.5, 10.0.13 and 9.0.0.p44 versions).

These tags let you download a `config.build` file to ease your Zimbra build.

This is intended to be integrated in your Zimbra build.

## Usage example

```
mkdir installer-build
cd installer-build
git clone --depth 1 --branch 10.1.5 git@github.com:Zimbra/zm-build.git
cd zm-build
# Use the version you want to build (Example: 10.1.5) in the new line
wget 'https://github.com/maldua-pimbra/maldua-pimbra-config/raw/refs/tags/10.1.5/config.build' -O config.build_pimbra
# If download fails check Issues to either complain or check if the new tag is actually not needed.
cat config.build_pimbra >> config.build
# Other of your changes (Optional)
# Your ./build.pl command
```
