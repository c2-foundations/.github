# Security Policy

## Public discussions are not a security channel

Do not report vulnerabilities in public GitHub Discussions, Issues, YouTube
comments, or social media.

## How to report

For a vulnerability affecting a public C² repository, use GitHub's private
vulnerability reporting feature in the affected repository.

For Circuit Lab, open the repository's **Security** area and choose the private
reporting option:

<https://github.com/c2-foundations/circuit-lab>

This option will be enabled before Circuit Lab becomes public. If the
repository is not public yet, there is no supported public release to report
against. Do not send exploit details to the community conduct address.

Include:

- a clear description of the impact;
- the affected version or build, when known;
- minimal reproduction steps;
- a proof of concept only when necessary;
- a suggested mitigation, when available.

Do not include real credentials, personal data, or destructive payloads.

## Scope

Security reports include, among other cases:

- unsafe handling of imported projects or remote resources;
- path traversal or unintended file access;
- script execution or injection;
- exposure of tokens, private Studio data, or local paths;
- bypasses of the public/private build boundary;
- abuse of any future circuit-sharing service.

Questions about expected simulator behaviour belong in GitHub Discussions.

## Supported version

The latest publicly deployed version is the supported version unless a
repository states otherwise.
