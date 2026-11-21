<div align="center">
    <a href="https://cycle-orm.dev" target="_blank">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://github.com/cycle/.github/blob/main/logo/words-vector-dark.svg?raw=true">
            <img width="50%" align="center" src="https://github.com/cycle/.github/blob/main/logo/words-vector-light.svg?raw=true" alt="CycleORM Logo">
        </picture>
    </a>
</div>

<br>
<br>

<div align="center">

[![Documentation](https://img.shields.io/badge/Documentation-blue?style=for-the-badge&logo=gitbook&logoColor=white)](https://cycle-orm.dev/docs)
[![Sponsor](https://img.shields.io/static/v1?style=for-the-badge&label=&message=Sponsor&logo=githubsponsors&logoColor=white&color=%23EA4AAA)](https://github.com/sponsors/cycle)
[![Discord](https://img.shields.io/discord/538114875570913290?style=for-the-badge&logo=discord&labelColor=7289d9&logoColor=white&color=39456d)](https://discord.gg/spiralphp)

</div>

# Welcome to Cycle Organization! 👋

**Cycle ORM** is a modern data mapper for PHP 8.2+, designed to be intuitive and flexible. It offers a high-performance database access layer that simplifies working with databases in PHP applications.

## 💬 Join Our Community

Join our [Discord server](https://discord.gg/spiralphp) to connect with other Cycle ORM users and contributors!

## 🗺️ Explore the Cycle Ecosystem

### Core

- [**ORM**](https://github.com/cycle/orm): Core of our project — Data mapper layer.
- [**Database**](https://github.com/cycle/database): Database abstraction layer with query builders and schema introspection for MySQL, PostgreSQL, SQL Server and SQLite.
- [**Transaction**](https://github.com/cycle/transaction): Runs raw database queries and a scoped Entity Manager inside one database transaction.

### Schema

- [**Annotated**](https://github.com/cycle/annotated): Defines entities, columns and relations with PHP attributes.
- [**Schema Builder**](https://github.com/cycle/schema-builder): Compiles entity declarations into the ORM schema and syncs database tables.
- [**Schema Provider**](https://github.com/cycle/schema-provider): Builds the ORM schema from different sources, with caching.
- [**Schema Renderer**](https://github.com/cycle/schema-renderer): Renders ORM schemas into various formats, including PHP code, console output and [Mermaid](https://mermaid.js.org/).

### Migrations

- [**Migrations**](https://github.com/cycle/migrations): Migration runner and repository for Cycle Database.
- [**Schema Migrations Generator**](https://github.com/cycle/schema-migrations-generator): Generates migration files from the difference between the ORM schema and the database.

### Extensions

- [**Entity Behavior**](https://github.com/cycle/entity-behavior): Entity behaviors like auto timestamps, soft deletes, optimistic locking, hooks and event listeners.
- [**Entity Behavior UUID**](https://github.com/cycle/entity-behavior-uuid): [UUID](https://cycle-orm.dev/docs/entity-behaviors-uuid) primary keys and columns.
- [**Entity Behavior Identifier**](https://github.com/cycle/entity-behavior-identifier): [`ramsey/identifier`](https://github.com/ramsey/identifier) types as entity columns.
- [**Active Record**](https://github.com/cycle/active-record): The [Active Record](https://cycle-orm.dev/docs/active-record-introduction) pattern on top of Cycle ORM.
- [**ORM Promise Mapper**](https://github.com/cycle/orm-promise-mapper): A mapper that loads relations through promise objects instead of proxies.

### Tooling

- [**Testing**](https://github.com/cycle/testing): Shared [Testo](https://github.com/php-testo/testo) test harness for Cycle ORM packages: per-driver suites and test databases in Docker.
- [**Skills**](https://github.com/cycle/skills): Agent skills that teach AI coding assistants to work with Cycle ORM and its attributes.

## 👩‍💻 Resources for Developers

- [Documentation](https://cycle-orm.dev/docs): Official documentation, built from the [docs repository](https://github.com/cycle/docs).
- [Cycle Blog](https://spiral.dev/blog): Stay updated with the latest news and insights directly from our team.

## 🌍 Cycle ORM Integrations

Cycle ORM can be integrated seamlessly with various PHP frameworks, enhancing productivity across different development environments:

- **Spiral**: Official ORM, supported by [`spiral/cycle-bridge`](https://github.com/spiral/cycle-bridge). [Documentation](https://spiral.dev/docs/basics-orm/current/en)
- **Yii 3**: Supported by [`yiisoft/yii-cycle`](https://github.com/yiisoft/yii-cycle), enriching Yii framework applications. [Documentation](https://github.com/yiisoft/yii-cycle)
- **Laravel**: Integrate using [`wayofdev/laravel-cycle-orm-adapter`](https://github.com/wayofdev/laravel-cycle-orm-adapter) for a robust DataMapper ORM solution. [Documentation](https://laravel-cycle-orm-adapter.wayof.dev)

## 🚀 Key Projects

- [**RoadRunner**](https://roadrunner.dev/): High-performance PHP server and process manager.
- [**Spiral Framework**](https://spiral.dev/): Secure and modular PHP framework.

## 🤗 Support Cycle ORM

Consider supporting us by becoming a sponsor on GitHub: [Become a Sponsor](https://github.com/sponsors/cycle)

## 📄 Contributing to Cycle ORM

We welcome contributions of all forms, from code improvements to documentation. Dive into our [Contributing Guidelines](https://github.com/cycle/.github/blob/main/.github/CONTRIBUTING.md) for more details on how you can contribute.
