# @tane-lang/cli

Command-line tool for the [tane-lang](https://github.com/tane-lang) project. It installs the `tane` command.

Status: placeholder. The CLI is not functional yet.

```sh
npx @tane-lang/cli      # one-off run
npx tane-lang           # same, through the tane-lang alias package
npm i -D @tane-lang/cli # then: npx tane
```

Install only one of `@tane-lang/cli` and `tane-lang` globally; both provide the `tane` command.

## Packages

| Package | Source | Purpose |
| --- | --- | --- |
| `@tane-lang/cli` | repository root | the CLI |
| `tane-lang` | `alias/` | depends on `@tane-lang/cli` and runs its `tane` command |

Publish `@tane-lang/cli` first, then `alias/` with the same version.

## License

MIT
