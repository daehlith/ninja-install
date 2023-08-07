# ninja-install

This composite action installs the Ninja build system for use in a GitHub Actions workflow. By default, it downloads 
version 1.11.1 from [Ninja's GitHub Repository](https://github.com/ninja-build/ninja).
However, the version can be explicitly overridden; see `Usage` below.

## Usage

To install the default version of ninja, simply add this step to your GitHub Actions workflow:
```yaml
- uses: daehlith/ninja-install@v1
```

To override the version, use the following step in your GitHub Actions workflow:
```yaml
- uses: daehlith/ninja-install@v1
  with:
    version: 1.10.2
```
