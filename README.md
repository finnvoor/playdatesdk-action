# playdatesdk-action

A Github Action for installing the [Playdate SDK](https://play.date/dev/) on macOS and Linux with automatic caching.

### Usage

```yaml
jobs:
  test:
    steps:
      - uses: actions/checkout@v4
      - uses: finnvoor/playdatesdk-action@main
        with:
          version: 2.7.3 # optional, default: latest
```
