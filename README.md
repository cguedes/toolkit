[![Circle CI](https://circleci.com/gh/sky-uk/toolkit/tree/master.svg?style=svg&circle-token=6b7a4f1adf2fb7fad8c0942b8d4d8386afb681f4)](https://circleci.com/gh/sky-uk/toolkit/tree/master)

# Toolkit

Sky's web Toolkit.

## Goals

- Enable teams across tribes to share common styles
- Provide a modular approach to handling CSS/Sass components
- Provide example use cases with a generated style guide

## Structure

The project consists of 3 repositories: 

- _this repo_: consumes the UI and Core layers and serves static pages
- [Toolkit Core](https://github.com/sky-uk/toolkit-core): Global styles and defaults for all projects
- [Toolkit UI](https://github.com/sky-uk/toolkit-ui): Aesthetic components following Polaris brand guidelines

## Versioning

The Toolkit follows [Semantic Versioning](http://semver.org) to help manage the impact of releasing new library versions

## Getting Started & Documentation

**Note**: The Toolkit is still in active development and not yet 100% stable. This means breaking updates may occur, minor issues and quirks may be present, and full browser support is not guaranteed.

Currently available Toolkit components are available at: http://sky-uk.github.io/toolkit/

See the wiki for:
- how to [implement the Toolkit in your project](https://github.com/sky-uk/toolkit/wiki/Getting-started).
- how to [get started working on GitHub pages](https://github.com/sky-uk/toolkit/wiki/GitHub-Pages).

## Requirements

Because of how the Toolkit loads third party dependencies such as `sass-mq`, NPM >3.0.0 is required (included in Node >v5.0.0).

Also note that if you're using Webpack and sass-loader you also require sass-loader >3.1.0.

## Maintainers

- [Aaron Thomas](https://github.com/aaronthomas) - aaron.thomas@sky.uk
- [Joe Bell](https://github.com/joebell93) - joseph.bell@sky.uk

## Contributors

- [Harry Roberts](https://github.com/csswizardry) - [@csswizardry](https://twitter.com/csswizardry)
- [Callum Barratt](https://github.com/cbarratt) - callum.barratt@sky.uk
- [Luke Barratt](https://github.com/lbarratt) - luke.barratt@sky.uk

Feel free to open a pull request to include yourself in this list. 

## Contributing

We appreciate any contribution to the Toolkit. Check out [CONTRIBUTING.md](CONTRIBUTING.md).
We keep a list of features and bugs [in the issue tracker](https://github.com/sky-uk/toolkit/issues).