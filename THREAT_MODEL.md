# Threat Model

A formal independent third-party security audit has not yet been completed.

## Assets

- Subscription/profile links and VPN credentials.
- Deep-link payloads.
- Local logs and diagnostics.
- Installer/release assets.
- Update channel metadata.

## Threats

- Malicious profile or deep-link input.
- Credential leakage in logs/screenshots.
- Installer or release asset compromise.
- Update-channel spoofing or stale release metadata.
- Local attacker reading client files.

## Recommended Improvements

- Publish checksums and signing details for release assets.
- Document source commit provenance for each release.
- Document log redaction and local storage behavior.
- Add public security contact.

## Non-Goals

- Full private source-code audit from this repository alone.
- DDoS mitigation.
- Service-level retention policy.
