# Parity Technologies

Parity Technologies develops open-source software that advances Polkadot and decentralised infrastructure.

Our work spans protocol engineering, blockchain development, smart-contract tooling and new ways to make decentralised applications easier to build and use.

This GitHub organisation contains projects spanning core Polkadot infrastructure, developer tooling, application development and emerging decentralised technologies.

## Start here

Not sure which repository you need?

| I want to… | Start with |
|---|---|
| Build a runtime, chain or parachain | [`paritytech/polkadot-sdk`](https://github.com/paritytech/polkadot-sdk) |
| Build an application with TypeScript | [`paritytech/product-sdk`](https://github.com/paritytech/product-sdk) |
| Create, build and deploy a Playground application | [`paritytech/playground-cli`](https://github.com/paritytech/playground-cli) |
| Build with Solidity on Polkadot | [`paritytech/revive`](https://github.com/paritytech/revive) |
| Query a Polkadot SDK-based network through REST | [`paritytech/polkadot-rest-api`](https://github.com/paritytech/polkadot-rest-api) |
| Explore decentralised data storage | [`paritytech/polkadot-bulletin-chain`](https://github.com/paritytech/polkadot-bulletin-chain) |
| Explore emerging storage infrastructure | [`paritytech/web3-storage`](https://github.com/paritytech/web3-storage) |
| Integrate applications with desktop, mobile or browser hosts | [`paritytech/host-rust-core`](https://github.com/paritytech/host-rust-core) |
| Explore trustless application discovery and access | [`paritytech/dotli-community`](https://github.com/paritytech/dotli-community) |

## Core Polkadot engineering

### [`polkadot-sdk`](https://github.com/paritytech/polkadot-sdk)

The Polkadot SDK contains the components used to build Polkadot runtimes, chains, parachains and supporting infrastructure.

Start here if you are working on runtime development, protocol engineering or blockchain infrastructure.

## Application development

### [`product-sdk`](https://github.com/paritytech/product-sdk)

A TypeScript SDK for building applications that interact with Polkadot infrastructure.

Product SDK provides typed APIs for chain access, transactions, signing, contracts, storage and host environments.

### [`playground-cli`](https://github.com/paritytech/playground-cli)

Command-line tooling for creating, building and deploying applications through the Polkadot Playground development environment.

It provides a guided path from initial setup through project creation, development and publication.

### [`polkadot-rest-api`](https://github.com/paritytech/polkadot-rest-api)

A REST interface for querying and interacting with Polkadot SDK-based networks.

It provides a familiar HTTP-based route for web, backend and integration developers who do not need to work directly with lower-level blockchain APIs.

### [`revive`](https://github.com/paritytech/revive)

Compiler tooling that enables Solidity contracts to target PolkaVM through Polkadot's smart-contract environment.

Start here if you are exploring Solidity development on Polkadot or building tooling around the Solidity-to-PolkaVM compilation path.

## Storage and emerging infrastructure

### [`polkadot-bulletin-chain`](https://github.com/paritytech/polkadot-bulletin-chain)

A Polkadot SDK-based chain exploring distributed data storage and retrieval infrastructure.

The repository includes the chain implementation, SDK tooling and examples for working with Bulletin.

### [`web3-storage`](https://github.com/paritytech/web3-storage)

An architecture exploring decentralised storage with independent providers, on-chain coordination and accountability.

## Application environments

### [`host-rust-core`](https://github.com/paritytech/host-rust-core)

Core infrastructure for communication between Polkadot applications and desktop, mobile and browser host environments.

Application developers will normally interact with these capabilities through Product SDK. Developers building hosts, SDK integrations or protocol implementations can work with the underlying host and protocol components directly.

### [`dotli-community`](https://github.com/paritytech/dotli-community)

A browser-based client for resolving and running Polkadot applications without depending on a central application server for application resolution.

## How the pieces fit together

Parity's repositories operate at different layers of the developer stack.

### Protocol and chain infrastructure

[`polkadot-sdk`](https://github.com/paritytech/polkadot-sdk)

Provides the underlying components for building runtimes, chains and protocol infrastructure.

### Developer interfaces and capabilities

[`product-sdk`](https://github.com/paritytech/product-sdk) · [`polkadot-rest-api`](https://github.com/paritytech/polkadot-rest-api) · [`revive`](https://github.com/paritytech/revive) · [`polkadot-bulletin-chain`](https://github.com/paritytech/polkadot-bulletin-chain) · [`web3-storage`](https://github.com/paritytech/web3-storage)

Provide different ways for developers to interact with chains, contracts, storage and other decentralised infrastructure.

### Development and application environments

[`playground-cli`](https://github.com/paritytech/playground-cli) · [`host-rust-core`](https://github.com/paritytech/host-rust-core) · [`dotli-community`](https://github.com/paritytech/dotli-community)

Support how applications are created, connected to host capabilities, published and accessed.

Projects across the Parity organisation are at different stages of development. Check the README and documentation in the relevant repository for current support, compatibility and production-use guidance.

## Working with AI coding assistants

Several Parity repositories include project-specific guidance for AI coding assistants alongside conventional documentation.

Depending on the repository, this may include files such as:

`AGENTS.md` · `CLAUDE.md` · repository-specific skills and development instructions

These files provide additional context about repository architecture, commands, development workflows and common tasks.

AI-generated code should still be validated against the current repository documentation, tests and supported versions.

## Contributing

Parity develops in the open and contributions are welcome across many of our repositories.

Contribution processes differ between projects. Before opening a pull request:

1. Read the repository README.
2. Check its contributing guidelines.
3. Review existing issues and pull requests.
4. Follow the testing and formatting requirements for that project.

For large or architectural changes, start with the discussion process described by the relevant repository rather than opening an implementation pull request without prior coordination.

## Security

Please do not report security vulnerabilities through public GitHub issues.

If you believe you have discovered a security issue, follow the security reporting instructions provided in the relevant repository.

## About Parity

Parity Technologies is an open-source software company and a core technical contributor to Polkadot.

We build infrastructure, developer tooling and emerging technologies designed to advance a more decentralised web.

Find out more at [parity.io](https://www.parity.io/).
