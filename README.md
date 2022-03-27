[![jpdmgen](https://jpdmgen.janhendrikewers.uk/_static/banner_nobg.png)](https://github.com/iwishiwasaneagle/jpdmgen)

[![CI](https://github.com/iwishiwasaneagle/jpdmgen/actions/workflows/CI.yml/badge.svg)](https://github.com/iwishiwasaneagle/jpdmgen/actions/workflows/CI.yml)
[![codecov](https://codecov.io/gh/iwishiwasaneagle/jpdmgen/branch/master/graph/badge.svg?token=UHOQ3AXSF0)](https://codecov.io/gh/iwishiwasaneagle/jpdmgen)

SAR is a unique design problem for path planning with little exposure to research. The search planning is highly dependent on the environment, and what it contains. Many papers use Probability Distribution Maps (PDMs) to inform the algorithms to make better paths since less time taken to find a missing person means higher chance of survivability.

This simulation environment is built to accommodate my research into this topic but anyone interested is more than welcome to help me build it.

## Installation

```bash
pip install git+https://github.com/iwishiwasaneagle/jpdmgen.git
```

## Docs

Build yourself with `tox -e docs` or visit the [hosted docs][docs]

## Making Changes & Contributing

This project uses `pre-commit`, please make sure to install it before making any changes:

```bash
pip install pre-commit
cd jpdmgen
pre-commit install
```

It is a good idea to update the hooks to the latest version:

```bash
pre-commit autoupdate
```

[docs]: https://http://jpdmgen.janhendrikewers.uk/
