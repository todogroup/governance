# TODO Group Repository Access Model

This document describes the current GitHub access model for TODO Group repositories

## Permission Levels

### Admin

Admin access should be limited to people or teams responsible for overall repository governance, security, and organization-level coordination.

Admin access should be granted to:

- Linux Foundation staff
- TODO Group Steering Committee team members

Admin access should not normally be granted to working group chairs, reviewers, or contributors.

## Maintain

Maintain access is intended for people or teams who help manage repository activity but do not need full administrative control.

Maintain access may be granted to:

- Working group chair teams
- TODO General Member representatives
- Specialized working group teams, when applicable, such as:
  - Review teams
  - Infra teams
  - Maintainer teams
  - Content teams

## Write

Write access is intended for active contributors who need to push branches, open pull requests, help review work, or contribute directly to repository content

Write access may be granted to:

- Any contributors who support a TODO group’s repository work

## Branch Rulesets and Pull Request Reviews

TODO Group repositories should use branch rulesets or branch protection rules for the default branch.

Recommended branch rules:

- Require a pull request before merging
- Require at least one approval before merging.
- Require review from CODEOWNERS when CODEOWNERS is configured
- Allow repository admins to bypass rules only when necessary
