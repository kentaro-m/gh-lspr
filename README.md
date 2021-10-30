# gh prs
`gh prs` is GitHub CLI extension. It helps you to check pull requests which you need to respond.

## Usage
- `gh prs`
  - Show pull request list (filter by review requested, created and mentioned)
- `gh prs --review-requested` ( `gh prs -r` )
  - Show pull request list which filter by review requested to others
- `gh prs --created` ( `gh prs -c` )
  - Show pull request list which filter by created by myself
- `gh prs --mentioned` ( `gh prs -m` )
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
$ gh extension install kentaro-m/gh-prs
```

## Licence
MIT
