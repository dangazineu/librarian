# Librarian CLI

Librarian is a command-line tool for managing the lifecycle of Google Cloud SDK client libraries. It provides a unified interface for configuration, generation, and release management.

## Getting Started

To get started with Librarian, please read the following documentation:

*   [**Onboarding to Librarian**](./doc/onboarding.md): A guide to getting started with the Librarian project and contributing effectively.
*   [**How We Write Go**](./doc/howwewritego.md): Project-specific guidance on writing idiomatic, consistent Go code.

## Commands

The following commands are available:

*   `configure`: Configure a new client library.
*   `generate`: Generate a client library.
*   `update-apis`: Update the APIs for a client library.
*   `create-release-pr`: Create a new release pull request.
*   `update-image-tag`: Update the image tag for a client library.
*   `merge-release-pr`: Merge a release pull request.
*   `create-release-artifacts`: Create the release artifacts.
*   `publish-release-artifacts`: Publish the release artifacts.
*   `version`: Print the version of the Librarian CLI.

For more information on a specific command, run `librarian <command> --help`.

## License

Apache 2.0 - See [LICENSE](./LICENSE) for more information.