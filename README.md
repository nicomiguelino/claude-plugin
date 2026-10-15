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

## Try it locally

```sh
claude --plugin-dir ./claude-plugin
```

The plugin loads for that session only.

## Validate

```sh
claude plugin validate .
```
