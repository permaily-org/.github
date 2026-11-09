# Permaily

**Give apps and AI agents the emails they need. Not your whole inbox.**

Permaily is an email access broker. Each app, AI agent or vendor gets only the mail you approve, every message that leaves is recorded, and any connection can be revoked in one click.

## Don't trust us. Verify.

Permaily runs inside AWS Nitro Enclaves, and its service image is built reproducibly from public code. Anyone can rebuild the image, compare its measurements with the attestation of the running service, and check that the TLS connection ends inside the enclave. [How verification works](https://github.com/permaily-org/permaily/blob/develop/docs/verification.md)

## Start here

| | |
|---|---|
| [permaily](https://github.com/permaily-org/permaily) | The enclave service, the verifier, the web app and the public site |
| [Verification](https://github.com/permaily-org/permaily/blob/develop/docs/verification.md) | Rebuild the image and verify a running deployment |
| [Contributing](https://github.com/permaily-org/permaily/blob/develop/docs/contributing.md) | Propose a change and sign the CLA |
| [Discussions](https://github.com/permaily-org/permaily/discussions) | Questions and ideas |
| [Security](https://github.com/permaily-org/permaily/security/advisories/new) | Report a vulnerability privately |
| [Code of conduct](https://github.com/permaily-org/.github/blob/main/code_of_conduct.md) | How we expect everyone to behave |

## Status

Early development, built in the open. Reproducible builds and end-to-end verification are available; connecting a mailbox, per-app and per-agent access rules, the MCP server for agents and the app API are planned.

## License

The code is public so anyone can audit and verify it. It is free for personal use; companies and organizations need a [commercial license](https://github.com/permaily-org/permaily/blob/develop/docs/commercial.md). See the [Permaily Personal Use License](https://github.com/permaily-org/permaily/blob/develop/license.md).
