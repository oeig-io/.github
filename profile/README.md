# Welcome to oeig-io

## Prerequisites

- [GitHub CLI (`gh`)](https://cli.github.com/) installed and authenticated to support maintaining repositories
- [Incus](https://linuxcontainers.org/incus/docs/main/tutorial/first_steps/) - to run containers

## Quick Start for New Users

Install and authorize the github cli `gh` command. This will be used below to clone all repositories you have access to.

Create an `~/code/oeig/` directory and `cd` to it.

Clone the following repository:

```
git clone https://github.com/oeig-io/repo-utils/
```

Use the following command to clone all organization repositories and pull latest updates:

```bash
./repo-utils/git-clone-and-pull-all.sh
```

Subsequently, you can pull updates on existing repositories using:

```bash
./repo-utils/git-pull-all.sh
```

You can also get the status of all repositories using:

```bash
./repo-utils/git-status-all.sh
```
