# Contributing to the Polhem projects

This guide applies to every repository of the polhem-dev organization. GitHub shows it for a repository that has no
`CONTRIBUTING.md` of its own; a repository that has one links here and adds how to build and test it, and the
conventions specific to it.

## Workflow

1. Fork the repository and create a branch from the latest `main` in your fork.
2. Make the change, with tests.
3. Build and test locally, as the repository's own `CONTRIBUTING.md` or `README.md` describes.
4. Open a pull request against `main`. `main` only accepts changes through pull requests, and the repository's
   required checks must pass before one can merge.

For a larger change (a new feature, a change to public API, a new dependency), open an issue first so the approach can
be agreed on before you spend time on it.

## Who merges

Each repository has one maintainer, [@jeff377](https://github.com/jeff377). Other contributors are not given write
access: they work from a fork, and the maintainer reviews every pull request from a fork before merging it. The
maintainer's own pull requests merge once the required checks pass, because GitHub does not let an author approve
their own pull request.

## Repository settings

Every repository is set up the same way, from [`repo-baseline.json`](repo-baseline.json) in this repository: the merge
methods, the protection of `main`, its required checks, and the code owner. A repository that differs is either listed
there as an exception, with the reason, or brought back in line.
