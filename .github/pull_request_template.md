## What and why

## How it was tested

## Checklist

- [ ] Branched from `develop`; the title is a lowercase Conventional Commit.
- [ ] `make check` passes.
- [ ] If the build or anything in the enclave image changed, `nix build .#eif` still reproduces.
- [ ] A bug fix starts with a failing test.
- [ ] Docs and AGENTS.md are updated where needed (ADR, acceptance, security).
- [ ] Nothing logs email content, addresses, tokens, cookies or codes.
