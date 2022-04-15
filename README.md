# `github-actions-code-to-do-github-issues-backup` GitHub Action Demo

[svg]: https://github.com/TomasHubelbauer/github-actions-code-to-do-github-issues-backup-demo/actions/workflows/main.yml/badge.svg
[yml]: https://github.com/TomasHubelbauer/github-actions-code-to-do-github-issues-backup-demo/actions/workflows/main.yml
[![main][svg]][yml]

This repository demonstrates the use of the
`tomashubelbauer/github-actions-code-to-do-github-issues-backup` GitHub Action.

This action is based on the https://github.com/TomasHubelbauer/todo tool.

It recognizes to-do comments in source code files. It can also recognize check
boxes in MarkDown, line this:

- [ ] Do something
- [ ] Do something else
- [ ] Do something different still

The workflow demonstrating this action can be seen through the badge link at the
top of this readme. It should print the checkboxes as seen here. For now, the
action is not syncing them to GitHub Issues yet, as it is still in development.
