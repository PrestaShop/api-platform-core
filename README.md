# PrestaShop fork of API Platform Core 3.4

This fork keeps the `3.4` branch of [api-platform/core](https://github.com/api-platform/core) alive for PrestaShop 9, which supports PHP 8.1 and cannot move to API Platform 4.x (PHP 8.2 minimum) in its patch releases. Upstream 3.x is end of life.

It is published as `prestashop/api-platform-core` and replaces `api-platform/core`. Releases are tagged on the `3.4` branch:

| Version | Changes on top of api-platform/core v3.4.17 |
|---|---|
| v3.4.18 | Backports of [GHSA-9rjg-x2p2-h68h](https://github.com/advisories/GHSA-9rjg-x2p2-h68h) (CVE-2026-54164) and [GHSA-pjhx-3c3w-9v23](https://github.com/advisories/GHSA-pjhx-3c3w-9v23) (CVE-2026-49858) |

**Security follow-up:** as the package is renamed, `composer audit` no longer reports the advisories published for `api-platform/core`. Watch the [api-platform/core advisories](https://github.com/api-platform/core/security/advisories) and backport every fix that affects 3.x to this branch.

# API Platform Core

API Platform Core is an easy-to-use and powerful system to create [hypermedia-driven REST](https://en.wikipedia.org/wiki/HATEOAS) and [GraphQL](https://graphql.org/) APIs.
It is a component of the [API Platform framework](https://api-platform.com) and it can be integrated
with [the Symfony framework](https://symfony.com) using the bundle distributed with the library.

It natively supports popular open formats including [JSON for Linked Data (JSON-LD)](https://json-ld.org), [Hydra Core Vocabulary](https://www.hydra-cg.com), [OpenAPI v2 (formerly Swagger) and v3](https://www.openapis.org), [JSON:API](https://jsonapi.org/), [HAL](https://tools.ietf.org/html/draft-kelly-json-hal-08) and [Problem Details](https://tools.ietf.org/html/rfc7807).

Build a working and fully-featured web API in minutes. Leverage the awesome features of the tool to develop complex and
high-performance API-first projects. Extend or override everything you want.

[![GitHub Actions](https://github.com/api-platform/core/workflows/CI/badge.svg?branch=main)](https://github.com/api-platform/core/actions?query=workflow%3ACI+branch%3Amain)

## Documentation

The documentation of API Platform Core Library can be browsed [on the official website](https://api-platform.com/docs/core).
