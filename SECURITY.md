# Security policy

This policy covers every repository in the MillenniumMachines organisation that doesn't have its own.

## Reporting a problem

Please report security problems privately. Don't open a public issue or pull request, or post about it on Discord, until it's fixed.

1. Open the **Security** tab of the affected repository and click **Report a vulnerability**.
2. If that button isn't there, [report it through the .github repository](https://github.com/MillenniumMachines/.github/security/advisories/new) instead, and say which repository it's about.

Your report stays private between you and the maintainers.

## What to report privately

- Passwords, tokens or keys committed to a repository.
- A way to change or replace a published release, or the files attached to it.
- A GitHub Actions workflow that could be misused, for example by a pull request from a fork.
- A maintainer account that looks compromised.

If you're not sure, report it privately anyway.

## Machine safety problems

A bug that makes a machine move unexpectedly, or that skips a safety check, is usually best reported as a normal issue, so other users hear about it quickly. If you think someone could trigger it on purpose, report it privately instead.

## What happens next

This is a volunteer project, so it may take a few days to reply. We'll confirm the problem, work on a fix and publish it in a new release. Once it's fixed, we'll publish a security advisory and credit you, unless you'd rather not be named.

## Supported versions

Fixes go into the latest release of each project.
