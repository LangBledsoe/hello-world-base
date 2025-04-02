# Hello World Base

This is the base project that provides a simple greeting message. It is part of a build chain example that demonstrates project dependencies using GitHub Actions Build Chain.

## Build Chain

This project is part of a build chain with:
- This project (`hello-world-base`)
- Downstream: [`hello-world-dependent`](https://github.com/LangBledsoe/hello-world-dependent)

## Building

```bash
mvn clean install
```

The build chain will automatically ensure that when this project is built, any downstream projects that depend on it will also be built in the correct order.
