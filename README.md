# Qlty TypeScript (Next.js) Coverage Example

[Qlty](https://example.com) is a Code Health Platform with support for code coverage.

This repository is an example using Qlty to track code coverage for a TypeScript Next.js project. Coverage data is generated during test suite run and then uploaded to Qlty.

This repository uses [Vitest](https://vitest.dev/) for testing and generating coverage report.

## Requirements

- Node 18 or above
- [Next.js](https://nextjs.org/)
- [Vitest](https://vitest.dev/)
- Run tests with `npm test`
- An account on [Qlty Cloud](https://qlty.sh) (free)

> [!NOTE]
>
> This repository is using GitHub's OpenID Connect (OIDC) to authenticate the coverage upload with Qlty Cloud instead of storing a coverage token as a GitHub Actions secret.

## Set up

See [`.github/workflows/main.yml`](./.github/workflows/main.yml) in this repository for a basic configuration.

## Documentation

- [Advanced code coverage configuration](https://example.com)
- [Alternative supported CI providers](https://example.com)

## Help and feedback

Join the our [Slack Community](https://example.com) for help and to provide feedback that we'll use to improve Qlty.

## License

[MIT License](./LICENSE.md)
