# claude-plugin

A collection of common, general-purpose skills intended for personal use

## Skills

- `/nicomiguelino:commit`: create a conventional commit
- `/nicomiguelino:open-pr`: open a pull request

## Install

```sh
/plugin install nicomiguelino --marketplace nicomiguelino/claude-plugin
```

Or add the marketplace first, then install:

```sh
/plugin marketplace add nicomiguelino/claude-plugin
/plugin install nicomiguelino@nicomiguelino
```

## Use it in a single session

```sh
claude --plugin-dir /path/to/claude-plugin
```

The plugin loads for that session only. Nothing is installed.

## Install in a single repo

Run from inside the repo, after adding the marketplace:

```sh
claude plugin marketplace add nicomiguelino/claude-plugin
claude plugin install nicomiguelino@nicomiguelino --scope project
```

- `--scope project`: written to `.claude/settings.json`, shared with anyone who clones the repo.
- `--scope local`: written to `.claude/settings.local.json`, only for you in that repo.
- `--scope user` (default): available in every repo.

## Validate

```sh
claude plugin validate .
```
