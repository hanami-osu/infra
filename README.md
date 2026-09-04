<div align="center">

# Hanami Infrastructure

**Organization-wide planning and shared infrastructure for the Hanami ecosystem.**

</div>

## Purpose

This repository is the coordination home for work that spans multiple Hanami projects.

It currently serves primarily as the organization-wide planning tracker. Shared configuration, deployment tooling, environment templates, and operational runbooks belong here when they are used by more than one project. Project-specific infrastructure should stay with the project that owns it.

## Use this repository for

- cross-project proposals and integrations
- shared accounts, authentication, and supporter systems
- shared database, cache, deployment, or backup changes
- organization-wide operational documentation
- work where the correct project repository is unclear

Project-specific bugs and features should be submitted to the relevant repository:

- [Hanami Bot](https://github.com/hanami-osu/bot)
- [Hanami Web](https://github.com/hanami-osu/web)
- [osu!guessr](https://github.com/hanami-osu/osu-guessr)
- [Hanami Companion](https://github.com/hanami-osu/companion)

## Opening an issue

Use the [issue tracker](https://github.com/hanami-osu/infra/issues) for organization-wide planning. Include the affected projects, the desired outcome, migration or deployment concerns, and any evidence that helps explain the current behavior.

## Security

Never commit production credentials, tokens, private keys, database dumps, or real environment files. Do not disclose vulnerabilities or sensitive details in a public issue. Follow the organization [security policy](https://github.com/hanami-osu/.github/security/policy) instead.

## License

Copyright © 2026 Hanami contributors.

This repository is licensed under the GNU Affero General Public License version 3 only (`AGPL-3.0-only`). See [LICENSE](LICENSE).

---

Hanami is an independent community project and is not affiliated with or endorsed by osu! or ppy Pty Ltd.
