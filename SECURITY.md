# Security Policy

## Supported versions

The latest release on the default branch receives security fixes. Older tags do not.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

1. Use GitHub private vulnerability reporting on this repository (Security tab, "Report a vulnerability").
2. If that is unavailable, contact the maintainer listed in CODEOWNERS.
3. Include affected version or commit, reproduction steps, and impact.

## What to expect

- Acknowledgement within 7 days.
- An assessment with severity and next steps within 14 days.
- Credit in the release notes once a fix ships, unless you ask to stay anonymous.

## Scope

In scope: this repository's source, build and CI configuration.
Out of scope: vulnerabilities in third-party dependencies (report upstream, or rely on Dependabot),
and anything requiring an already-compromised maintainer account.

## Baseline controls

Dependabot alerts and security updates, secret scanning with push protection,
CodeQL analysis, least-privilege workflow permissions, and SHA-pinned third-party actions.
