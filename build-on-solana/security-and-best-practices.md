---
description: Security and reliability references every Solana builder should review before shipping.
---

# 🔐 Security & Best Practices

If you only read one section before shipping something public, read this one.

## Essential Reading

- [Program Security](https://solana.com/developers/courses/program-security)
- [Verified Builds](https://solana.com/developers/guides/advanced/verified-builds)
- [Anchor Verifiable Builds](https://www.anchor-lang.com/docs/references/verifiable-builds)
- [Fees](https://solana.com/docs/core/fees)
- [PDA Accounts](https://solana.com/docs/core/pda/pda-accounts)
- [CPIs with PDA signers](https://solana.com/docs/core/cpi/cpi-with-pda)

## Practical Advice

- do not treat a hackathon submission as an excuse to ignore security basics
- use the simplest possible architecture that still solves the problem
- understand signer checks, account ownership, and PDA behavior before mainnet thinking
- verify that your deployed code matches your source if the project continues after the hackathon

## For Teams

Before submitting:

- confirm judges can access your repo and any docs
- document what is onchain and what is offchain
- explain why you chose Solana-specific design decisions
