# .github

Organization-wide defaults for [any-table](https://github.com/any-table).

GitHub uses these files in every repository in the organization that does not
have its own copy:

- `ISSUE_TEMPLATE/`: the issue forms (documentation issue, source correction)
  and `config.yml`, which turns off blank issues and links to Discussions and
  to the safeguarding guidance. A repository with any file in its own
  `.github/ISSUE_TEMPLATE/` uses only its own forms, not these.
- `pull_request_template.md`: the contribution terms every pull request
  confirms.
- `profile/README.md`: the organization's public profile page.

The issue forms apply the `documentation` and `source` labels. A label that
does not exist in a repository is silently skipped, so each repository that
uses these forms needs both labels.

Workflows and scripts are not shared from here. Each repository keeps its own
in `.github/workflows/`.
