## Maldua's pimbra-config

## Introduction

Please learn about Pimbra project and its patches policies at [main Pimbra repo](https://github.com/maldua-pimbra/maldua-pimbra).

This pimbra-config repo will have tags equivalent to the upstream Zimbra tags (starting from 10.1.5, 10.0.13 and 9.0.0.p44 versions).

These tags let you download a `config.build` file to ease your Zimbra build.

This is intended to be integrated in your Zimbra build.

## Usage examples

### 10.1.6 version

```
mkdir installer-build
cd installer-build
git clone --depth 1 --branch 10.1.6 git@github.com:Zimbra/zm-build.git
cd zm-build
# Use the version you want to build (Example: 10.1.6) in the new line
wget 'https://github.com/maldua-pimbra/maldua-pimbra-config/raw/refs/tags/10.1.6/config.build' -O config.build_pimbra
# If download fails check Issues to either complain or check if the new tag is actually not needed.
cat config.build_pimbra >> config.build
# Other of your changes (Optional)
# Your ./build.pl command
```

### 10.1.5 version

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

### 10.0.13 version

```
mkdir installer-build
cd installer-build
git clone --depth 1 --branch 10.0.13 git@github.com:Zimbra/zm-build.git
cd zm-build
# Use the version you want to build (Example: 10.0.13) in the new line
wget 'https://github.com/maldua-pimbra/maldua-pimbra-config/raw/refs/tags/10.0.13/config.build' -O config.build_pimbra
# If download fails check Issues to either complain or check if the new tag is actually not needed.
cat config.build_pimbra >> config.build
# Other of your changes (Optional)
# Your ./build.pl command
```

### 9.0.0.p44 version

```
mkdir installer-build
cd installer-build
git clone --depth 1 --branch 9.0.0.p44 git@github.com:Zimbra/zm-build.git
cd zm-build
# Use the version you want to build (Example: 9.0.0.p44) in the new line
wget 'https://github.com/maldua-pimbra/maldua-pimbra-config/raw/refs/tags/9.0.0.p44/config.build' -O config.build_pimbra
# If download fails check Issues to either complain or check if the new tag is actually not needed.
cat config.build_pimbra >> config.build
# Other of your changes (Optional)
# Your ./build.pl command
```
