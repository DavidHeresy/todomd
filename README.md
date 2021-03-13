# TODO.md

*Track TODO comments of any git repository in a TODO.md file.*

## Usage

Copy the script [`todo.sh`](todo.sh) to your git repository.
Generate the [TODO.md](TODO.md) file with:

```bash
bash todo.sh
```

## Development

Run `source workspace` to enter the development environment.

## TODOs

- TODO: Use strict mode and default system shell.
- TODO: Add README section how to add todo.sh as post-commit hook.
- FEATURE: Add support for `<file>#L<linenumber>` entries in `.todoignore`.
- FEATURE: Add support for `NOTE`, `XXX`, `HACK`, `FIXME`, `BUG` tags.
- FEATURE: Add support for `.todorc` file with custom search patterns.

