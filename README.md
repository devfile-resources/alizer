# Alizer

**Note: This repo is an archive of [Alizer](https://github.com/redhat-developer/alizer) for the Javascript and Java implementations.**

## Overview

Alizer (which stands for Application Analyzer) is a utilily whose goal is to extract informations about an application source code.
Such informations are:

- Programming languages.
- Frameworks.
- Tools used to build the application.

Additionaly, Alizer can also select one devfile (cloud workspace file) from a list of available devfiles and/or
detect components (the concept of component is taken from Odo and its definition can be read on [odo.dev](https://odo.dev/docs/getting-started/basics/#component)).

In order to be easily intergrated in other projects, comes in 3 different implementations:

- Go library & CLI
- **[Deprecated]** Java library & CLI
- **[Deprecated]** NPM package

_NOTE: Not all implementations support the same features. Please check the table at [alizer-spec](docs/public/alizer-spec.md#feature-table) for a detailed overview._

## Usage

As mentioned above Alizer comes with 3 different implementations. Each one has a different usage guide:

- [Go library & CLI](go/README.md#Usage)
- **[Deprecated]** [Java library & CLI](java/README.md#Usage)
- **[Deprecated]** [NPM package](js/README.md#Usage)

## Contributing

This is an open source project open to anyone. This project welcomes contributions and suggestions!

For information on getting started, refer to the [CONTRIBUTING instructions](CONTRIBUTING.md).

## Release process

The release process of `alizer` is very straightforward. You can create a new release [here](https://github.com/redhat-developer/alizer/releases/new).

- The _title_ of the release has to be the new version. `Alizer` follows the `{major}.{minor}.{bugfix}` format (e.g `0.1.0`)
- The _description_ of the release is optional. You may add a description if there were outstanding updates in the project, not mentioned in the issues or PRs of this release.

## Feedback & Questions

If you discover an issue please file a bug and we will fix it as soon as possible.

- File a bug in [GitHub Issues](https://github.com/redhat-developer/alizer/issues).

## License

EPL 2.0, See [LICENSE](LICENSE) for more information.
