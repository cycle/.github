# Contributing

Feel free to contribute to the development of Cycle ORM and its components.

- Bugs and feature requests go to the issues of the package they concern. Questions are welcome in [GitHub Discussions](https://github.com/cycle/orm/discussions) and on [Discord](https://discord.gg/spiralphp).
- Security issues are reported privately, never in public issues: see the [security policy](SECURITY.md).
- Commit messages and pull request titles follow [Conventional Commits](https://www.conventionalcommits.org) (`feat:`, `fix:`, `docs:`, …): release-please builds the changelog and the next version from them.
- Before opening a pull request, run the tests and the QA scripts of the package: `composer cs:fix` and `composer psalm`. Packages with database tests ship a `docker-compose.yml` in `tests/` that starts MySQL, PostgreSQL and SQL Server.

More details are in the [documentation](https://cycle-orm.dev/docs/contributing).
