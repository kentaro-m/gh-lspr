# gh-lspr
`gh lspr` is GitHub CLI extension. It helps you to check pull requests which you need to respond.

![Show pull request list](./demo.gif)

## Usage
- `gh lspr`
  - Show pull request list (filter by review requested, created and mentioned)
- `gh lspr --review-requested` ( `gh lspr -r` )
  - Show pull request list which filter by review requested to others
- `gh lspr --created` ( `gh lspr -c` )
  - Show pull request list which filter by created by myself
- `gh lspr --mentioned` ( `gh lspr -m` )
  - Show pull request list which filter by mentioned to others

### Options
- `-o`, `--org`
  - Filter by organization name or user name
- `-l`, `--limit`
  - Maximum number of items to fetch (default 10)
- `-h`, `--help`
  - Show help

## Installation
You need to install [GitHub CLI](https://github.com/cli/cli#installation) before you can use this extension.

```shell
$ gh extension install kentaro-m/gh-lspr
```

## Licence
MIT
