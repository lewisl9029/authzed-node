# Authzed Node Client

[![npm version](https://img.shields.io/npm/v/@authzed/authzed-node.svg?style=flat)](https://www.npmjs.com/package/@authzed/authzed-node)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Build Status](https://github.com/authzed/authzed-node/workflows/authzed-node-ci/badge.svg)](https://github.com/authzed/authzed-node/actions)
[![Discord Server](https://img.shields.io/discord/844600078504951838?color=7289da&logo=discord "Discord Server")](https://discord.gg/jTysUaxXzM)
[![Twitter](https://img.shields.io/twitter/follow/authzed?color=%23179CF0&logo=twitter&style=flat-square)](https://twitter.com/authzed)

This repository houses the Node client library for Authzed.

The library maintains various versions the Authzed gRPC APIs.
You can find more info on each API on the [Authzed API reference documentation].
Additionally, Protobuf API documentation can be found on the [Buf Registry Authzed API repository].

Supported API versions:
- v1alpha1
- v0

[Authzed API Reference documentation]: https://docs.authzed.com/reference/api
[Buf Registry Authzed API repository]: https://buf.build/authzed/api/docs/main

## Installation

The library can be installed from NPM:

```bash
npm install @authzed/authzed-node
```

or

```bash
yarn add @authzed/authzed-node
```

## Examples

You can follow the [Protecting Your First App] guide to see the latest best practice for using Authzed client libraries.

If you're interested in examples of a specific version of the API, they can be found in their respective folders in the [examples directory].

[Protecting Your First App]: https://docs.authzed.com/guides/first-app
[examples directory]: /examples
