# Access to Millennium Machines repositories

This page explains who can change what in the MillenniumMachines GitHub organisation, and how to get access.

## Roles

| Role | What it allows |
| --- | --- |
| Owner | Organisation settings, membership and repository rules. We keep this to a few people, because an owner account can change anything. |
| Maintainer (`devs` team) | Maintain access to every repository: review and merge pull requests, publish releases, and manage issues and most repository settings. |
| Member | Read access to every repository, including private ones. |
| Anyone | Open issues on any public repository, and pull requests from a fork. |

There are currently five owners and eight maintainers. Organisation members can see who they are on the [People](https://github.com/orgs/MillenniumMachines/people) and [devs team](https://github.com/orgs/MillenniumMachines/teams/devs) pages.

## How changes are made

- **Default branches:** every change goes through a pull request with one approval. Maintainers can merge their own pull requests, but nobody can push straight to a default branch, force-push it or delete it.
- **`development` branches:** can't be deleted.
- **Release tags:** in MillenniumOS, MOS-nxt, RRF-Configs and ArborCTL, only maintainers can create, move or delete tags, because pushing a `v*` tag publishes a release.
- **Reviews:** anyone is welcome to review a pull request, but only a maintainer's approval counts towards the one that's required.

Some repositories add their own rules, for example to protect version branches.

## Reviews of access

The owners review access every six months, in May and November.

- Access that hasn't been used for 18 months is removed: owners step down to member, and maintainers leave the `devs` team. It's restored on request.
- Outside collaborators are only added when someone needs access to a private repository, and are reviewed at the same time.

## Security

Everyone in the organisation must use two-factor authentication. To report a security problem, see [SECURITY.md](SECURITY.md).
