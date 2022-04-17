# `todo-comments-github-issues` GitHub Action Demo

[svg]: https://github.com/TomasHubelbauer/github-actions-code-to-do-github-issues-backup-demo/actions/workflows/main.yml/badge.svg
[yml]: https://github.com/TomasHubelbauer/github-actions-code-to-do-github-issues-backup-demo/actions/workflows/main.yml
[![main][svg]][yml]

[todo-comments-github-issues]: https://github.com/TomasHubelbauer/todo-comments-github-issues
This repository showcases the [todo-comments-github-issues] GitHub Action.

The action is based on [todo](https://github.com/TomasHubelbauer/todo).

It recognizes to-do comments and MarkDown check boxes, like this:

- [ ] Do something
- [ ] Do something else

[workflow]: https://github.com/TomasHubelbauer/todo-comments-github-issues-demo/actions/workflows/main.yml
[issues]: https://github.com/TomasHubelbauer/todo-comments-github-issues-demo/issues
The [workflow] runs the action which searches the code base of this repository
for `TODO` comments and syncs them to [issues].
