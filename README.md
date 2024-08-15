# My OSX Setup

[![Continuous integration](https://github.com/sumyat/my-osx-setup/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/sumyat/my-osx-setup/actions/workflows/main.yml)

## Building

### Including Bootstrapping

```
./prepare.sh && ./build.sh
```

Above sets up `brew`, `python`, `pipx` and `ansible` before running the `playbook.yml`.

### Ansible Only

```
./build.sh
```
