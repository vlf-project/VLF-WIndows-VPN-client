# Architecture

This repository is a release/documentation repository for the Windows VLF client.

A formal independent third-party security audit has not yet been completed.

The README describes a Windows VPN client with subscription/direct-link import, deep links, routing modes, exclusions, logs and GitHub Releases update checks. Because source code is not present here, this document cannot verify internal implementation details.

## Security Boundaries

- User-provided profile/subscription links are sensitive input.
- Deep links can carry sensitive profile data.
- Logs and generated client configs may contain secrets.
- Installer/release assets are part of the trust boundary.

## Known Limitations

- Source code is not available in this repository.
- Architecture details require review of the private/source repository or release build.
- Formal external audit is not completed yet.
