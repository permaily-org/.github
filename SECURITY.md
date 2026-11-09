# Security policy

Do not report vulnerabilities in public issues, discussions or pull requests.

## Reporting a vulnerability

Report it privately on GitHub: open the repository's **Security** tab and choose **Report a vulnerability**. For the main repository, use [this form](https://github.com/permaily-org/permaily/security/advisories/new). If you cannot use GitHub, write to hello@permaily.com and we will arrange a private channel.

Include the affected component, the release tag or commit, steps to reproduce or a proof of concept, and the impact you expect.

## What matters most

Permaily's promise is that the public code is the code running, and that only the enclave can read user data. Reports that break that chain have the highest priority, for example:

- a running service that passes verification while running code other than the published release;
- a way for the parent instance, which is untrusted, to read or alter user data;
- a TLS connection to the service that ends outside the enclave;
- a verifier (`scripts/verify.sh`, `pkg/attestation`) that accepts a forged or debug-mode attestation.

Permaily trusts AWS and the Nitro hardware; weaknesses in them are out of scope. The [threat model](https://github.com/permaily-org/permaily/blob/develop/docs/security.md) describes what is and is not trusted.

## Supported versions

Permaily is in early development. Only the latest release and the `develop` branch receive fixes.
