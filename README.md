# CASE Implementation XRY
[![CASE Examples](https://github.com/casework/CASE-Implementation-XRY/actions/workflows/validate.yml/badge.svg)](https://github.com/casework/CASE-Implementation-XRY/actions/workflows/validate.yml/badge.svg)
![CASE Version](https://img.shields.io/badge/CASE%20Version-1.3.0-green)

### Overview

Implementation scripts and examples for converting MSAB XRY reports into CASE.

### Usage

All files in the `examples/` directory with the extension `.jsonld` will automatically be validated using a GitHub Action that confirms their conformance to CASE v1.3.0.

### Contributing

This project uses [the `pre-commit` tool](https://pre-commit.com/) for linting the JSON files and ensuring consistent formatting. It can be installed with `pip`:
```bash
pip install pre-commit
pre-commit --version
```

The `pre-commit` tool hooks into Git's commit machinery to run a set of linters and static analyzers over each change. To install `pre-commit` into Git's hooks, run:
```bash
pre-commit install
```

To uninstall `pre-commit`, run either `pre-commit uninstall` or `rm .git/hooks/pre-commit`.
