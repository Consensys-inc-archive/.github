# Consensys-inc-archive/.github

This repository holds the public organization profile and the default community health files for the
`Consensys-inc-archive` organization, where Consensys keeps the repositories it no longer actively maintains.
GitHub applies these defaults to every repository in the organization that does not provide its own copy.

## What this repository provides

| File | Where it applies |
| --- | --- |
| [`SECURITY.md`](SECURITY.md) | Default security policy. Shown on the **Security** tab of every repository in the organization that has no `SECURITY.md` of its own, regardless of visibility. |
| [`profile/README.md`](profile/README.md) | Rendered on the [organization page](https://github.com/Consensys-inc-archive). |
| [`CODEOWNERS`](CODEOWNERS) | Review routing for this repository only. |

## Adding a repository

Organization administrators move a repository here once it is no longer actively maintained:

1. Update its `README` and description to say that it is no longer maintained.
2. Transfer it to this organization and keep its visibility, so public projects stay available to the ecosystem.
3. Archive it.

## Precedence

GitHub shows a repository's own community health file instead of the default kept here. It looks in the
repository's `.github/` directory, then in its root, then in its `docs/` directory, and falls back to this
repository only when none is found. `LICENSE` and `README` files are never inherited and must live in each
repository.

## Making changes

- Open a pull request. The code owners listed in [`CODEOWNERS`](CODEOWNERS) review every change.
- Keep the content evergreen: no personal names, dates, repository counts, or per-project contact channels, and
  link to stable landing pages rather than deep links.
- Sign your commits and add a `Signed-off-by` trailer with `git commit -s`.
- Repository access is managed by the organization administrators.

## Security

To report a vulnerability in any repository of this organization, email
[Security-Report@Consensys.com](mailto:Security-Report@Consensys.com) or follow the steps in
[`SECURITY.md`](SECURITY.md).
