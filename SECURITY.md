# Security policy

This policy covers every repository in the any-table organization and the
anytable.org website.

## Reporting a vulnerability

Please do not open a public issue, pull request, or discussion for a security
problem. Report it privately through GitHub's private vulnerability reporting:

1. Go to the **Security** tab of the affected repository.
2. Click **Report a vulnerability**.
3. Describe the problem, where it is, and how to reproduce it.

Direct links:

- Text and publishing workflow: <https://github.com/any-table/anytable/security/advisories/new>
- Website (anytable.org): <https://github.com/any-table/site/security/advisories/new>
- Directory: <https://github.com/any-table/directory/security/advisories/new>
- Organization defaults: <https://github.com/any-table/.github/security/advisories/new>

If you are not sure which repository is affected, use the website link. Only
the reporter and the project's custodians can see a private report.

## What to report

- Problems with anytable.org, such as a way to change what it serves or to
  bypass its security headers.
- Exposed credentials, such as a deploy hook URL or access token.
- Problems in a repository's workflows or build scripts that could let
  someone publish, alter, or delete content without review.
- Weaknesses in how the domain, the GitHub organization, or other
  infrastructure is held.

## What not to report here

This is not a channel for safeguarding matters. Do not use it to report
abuse, harm at a table, or anything said in a hard-truth round. If someone is
in danger, contact local emergency services; for abuse or other serious harm,
go to the appropriate authority or service where you are. See
[On harm within](https://anytable.org/foundational/#on-harm-within).

Disagreements about the text, broken links, and citation errors are not
security problems; use the issue forms instead.

## What to expect

The project is in its bootstrap period and is run by volunteers, so responses
are best effort. You should hear back within a week. There is no bug bounty:
the project takes no collection and holds no treasury.

As `CONTRIBUTING.md` in any-table/anytable allows, a security problem may be
contained privately first. Once it is fixed, a public record of the change is
published without exploitable details. Reporters are credited in that record
unless they ask not to be.
