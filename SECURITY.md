# Security policy

This policy covers every repository in the openlakestream organization that doesn't have its own
`SECURITY.md`. Ursa and Ursa for Apache Kafka (UFK) have their own, which also say which releases
receive fixes.

## Reporting a vulnerability

**Please don't report security problems in a public issue, pull request or discussion.**

Report them privately, in either of these ways:

1. **GitHub private vulnerability reporting.** Use the *Report a vulnerability* button on the
   Security tab of the affected repository, where it's enabled. It's private, it keeps the
   conversation in one thread, and it stays attached to the repository.
2. **Email `security@openlakestream.org`**, with the repository name in the subject line.

As much as you have of the following helps us act quickly:

- the affected version or commit
- what an attacker could do, and under which configuration
- steps to reproduce the problem
- anything you already know about the impact

A rough report sent early is better than a polished one sent late.

## What happens next

We'll acknowledge your report, investigate it, and keep you updated as we go. We coordinate
disclosure with you. By default we aim to publish within 90 days of the report, and sooner once a fix
is available.

When the fix is released, we publish a security advisory in the affected repository and credit you
in it, unless you ask us not to.

We don't run a bug bounty program.
