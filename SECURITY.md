# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

Email **glimacode.studio@gmail.com** with:

- what the issue is and where it lives (file, endpoint, or flow)
- how to reproduce it
- what an attacker could do with it

We aim to acknowledge within **72 hours** and to agree on a fix timeline with
you before anything is disclosed publicly.

## Scope

These repositories are portfolio and tooling projects. None of them handle
production customer data, and none ship with credentials. If you find a
credential, key, or real dataset committed anywhere in this organization, treat
it as a valid finding and tell us — that is exactly the kind of mistake this
policy exists to catch.

## What we consider out of scope

- Vulnerabilities in third-party dependencies that are already publicly known
  and tracked by Dependabot
- Issues that require physical access to a developer machine
- Missing hardening on demo or sample configuration that is documented as such
