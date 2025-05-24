# Contributing

First off, thank you for considering contributing to ITisOpen! It's people like you that make our community great.

## Code of Conduct

ITisOpen has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## What Should I Know Before I Get Started?

### ITisOpen Projects

Each ITisOpen project is hosted in its own repository on GitHub. Before contributing, familiarize yourself with the specific project you are interested in. Each repository typically contains a [`README.md`](README.md) with an overview of the project, and instructions for setting up your development environment and running tests.

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

Before creating bug reports, please check the Github Issues as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible. Fill out issue template as the information it asks for helps us resolve issues faster.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for ITisOpen, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

### Your First Code Contribution

Unsure where to begin contributing to ITisOpen? You can start by looking through issues with the following labels:

| Label                                                                                 | Usage                                                                    |
| :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------- |
| ![`help-wanted`](https://img.shields.io/badge/help_wanted-388bfd?style=for-the-badge) | issues which should only require a few lines of code, and a test or two. |
| ![`beginner`](https://img.shields.io/badge/beginner-388bfd?style=for-the-badge)       | issues which should be relatively easy to address.                       |

### Pull Requests

The process described here has several goals:

- Maintain ITisOpen's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible ITisOpen
- Enable a sustainable system for ITisOpen's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [Pull Request template](.github/PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all status checks are passing
4. If you need to request a review on your PR, please do so in the #pr-reviews Slack channel

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.


#### Versioning

The release automation relies on labels to increment the semantic versioning tag. Labels are applied manually by maintainers.
If no label is applied, "minor" is assumed.

As a reference, the following is a mapping between labels and [semver](https://semver.org/):

1. `Patch`: A minor, backward compatible change. Increments patch version, e.g. 1.0.**1**
2. `Minor`: New features that do not break anything, e.g. 1.**1**.1
3. `Major`: Breaking changes (or first stable release), e.g. **2**.0.0
4. `No-release`: Do not release a new version

Typically when a module is pre-release, e.g. 0.x.x, each new feature will be a minor release. Once the module hits 1.x, simpler features, which fit the definition of patch, will be labelled as such.

Only ITisOpen engineers should move a module from v0 to v1, and usually we prefer that it not be a breaking change. In fact, it's not uncommon for v1 to be just a new label for the current release, prompted by the desire to release a v2 that has a breaking change.

## Styleguides

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move resource to..." not "Moves resource to...")
- Limit the first line to 72 characters or less

### Pull Requests
- Reference GitHub Issues and Pull Requests liberally in a `## References` section. 
- Use `Closes #1234` to indicate when a PR fixes an issue.
