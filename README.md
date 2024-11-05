# Ormera

**Ormera** is a complete project for building type-safe models, relationships, and database interactions using a custom domain-specific language (DSL). This main repository connects and organizes the various submodules that make up the Ormera ecosystem.

## Overview

Ormera is divided into multiple repositories, each with its own responsibility:

1. **[Ormera Core](https://github.com/ORMEra/ormera-core)**: Contains the custom DSL parser and AST generator.
2. **[Ormera Code Generator](https://github.com/ORMEra/ormera-codegen)**: Generates TypeScript models with type-safe methods.
3. **[Ormera CLI](https://github.com/ORMEra/ormera-cli)**: Command-line tool for managing Ormera projects, generating models, and creating migrations.
4. **[Ormera Migrations Manager](https://github.com/ORMEra/ormera-migrations)**: Handles migration creation, tracking, and application.
5. **[Ormera Documentation](https://github.com/ORMEra/ormera-docs)**: Provides comprehensive documentation and examples.

## Installation and Usage

Ormera is designed to be modular, allowing you to use only the parts you need or integrate the full suite for a complete development experience.

### Installation
Install the CLI globally to start using Ormera:
```bash
npm install -g ormera-cli
```

### Getting Started
Initialize an Ormera project:
```bash
ormera init
```

Generate TypeScript models:
```bash
ormera generate
```

Create and run migrations:
```bash
ormera migrate
```

## License
MIT License
