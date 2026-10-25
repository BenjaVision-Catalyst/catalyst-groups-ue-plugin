# Catalyst Groups for Unreal Engine

Catalyst Groups for Unreal Engine is the planned integration for games that
need parties, teams, or organisations backed by the Catalyst Groups service.
It is intended to keep membership and governance rules on the server while
giving game code a native client interface. This repository is currently a
placeholder, with no Unreal module or working Groups client yet.

## Planned role

- Unreal-facing group and membership values and operations.
- Server-authoritative invitations, applications, and membership changes.
- Communication through Catalyst Connect.

The server has an experimental GT/Pharo core; network integration, client APIs,
Blueprint conveniences, and Unreal packaging remain future work.

## Installation and development

Install the Catalyst development environment through
[BVC](https://github.com/BenjaVisionPro/bvc#install). There is no functional
package from this repository to install yet.

Read the [component design](https://github.com/BenjaVisionPro/catalyst-workspace/blob/main/Groups/Catalyst-Groups-Design.md)
for the intended scope and remaining integration work. Design documents describe
the direction; they do not establish a released implementation.

## License

This repository is licensed under the [Catalyst Developer License](LICENSE).

Each developer using Catalyst for development needs an active
BenjaVision-Catalyst subscription: **$5 per month, billed annually at $60 per
developer**, including access to the BenjaVision-Catalyst repository. New products,
updates, bug fixes, and recompilation require active developer subscriptions.
Automated build machines do not need separate subscriptions.

Products lawfully built during active subscriptions may continue to be used,
hosted, sold, and distributed indefinitely without runtime royalties. Customers
and operators do not need subscriptions solely to use or distribute those builds.
Commercial and proprietary products are permitted; this license does not require
you to publish your own source code.

Existing license grants and separately licensed third-party material remain
unaffected. See [LICENSE](LICENSE) for the complete terms.
