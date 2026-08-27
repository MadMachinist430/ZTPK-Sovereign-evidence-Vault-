# ZTPK Ledger Vault

A public verification and methodology repository for the ZTPK sovereign evidence-vault framework.

## Purpose

This repository documents the evidence-handling methodology, redaction standards, verification approach, and sanitized findings structure.

It is **not** a public repository for raw evidence, testimony, private case materials, operational data, credentials, or live ledger state.

## Security Boundary

**Never publish secrets, keys, raw evidence, or local operational data.**

The following categories must remain private:

```gitignore
.env
.env.*
!.env.example

secrets/
credentials/
private/
evidence/
exports/
intake/
case-data/
legal-data/

*.pem
*.key
*.p12
*.pfx
*.jks
*.kdbx

*.sqlite
*.sqlite3
*.db
*.log

.terraform/
*.tfstate
*.tfstate.*
*.tfvars
```

## Public Repository Contents

```text
README.md
NOTICE.md
LICENSE-CODE.md
LICENSE-EVIDENCE.md

docs/
  methodology.md
  verification.md
  redaction-policy.md
  disclosure-policy.md

manifests/
  README.md

examples/
  fictional-or-fully-redacted-example.md

tools/
  verify-manifest.py
```

## Disclosure Model

- **Public:** Methodology, schemas, fictional or fully redacted examples, sanitized manifests, and verification tooling.
- **Private vault:** Original evidence, testimony, notebooks, raw artifacts, identities, credentials, live operational records, and detailed access logs.
- **Controlled disclosure:** Redacted or verified material released only when appropriate and authorized.

## Status

Initial repository structure established. Public material will be added only after privacy, redaction, integrity, and disclosure review.