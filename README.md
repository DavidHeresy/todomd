# Git Issues

*Collect all issue comments (e.g. `TODO`, `FIXME`, ...) in one file.*

## Usage

Copy the script [`issues.sh`](issues.sh) to your git repository, for example via:

```bash
wget https://raw.githubusercontent.com/DavidHeresy/git-issues/main/issues.sh
```

Generate the [Issues.md](Issues.md) file with:

```bash
bash issues.sh
```

You can also set an alias like:

```bash
alias issues="bash issues.sh"
```

TODO: Setup a Git Hook

## Development

Run `source workspace` to enter the development environment.

## Roadmap

- TODO: Generate `Issues.md` with a GitHub Job.
- TODO: Test `issues.sh` as a system-wide script / program.
- TODO: Test `issues.sh` with big public projects.
- FEATURE: Make `issues.sh` work for projects, that aren't a git repository.

