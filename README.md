# Crypto Style Improvement Proposals (CSIP)

This repository contains **Crypto Style Improvement Proposals (CSIPs)** — technical specifications and standards for the Crypto Style smart contract ecosystem.

CSIPs describe interfaces, message/opcode conventions, data layouts, and best practices that help contracts and tooling interoperate.

## Repository structure

- `csip/` — CSIP documents
  - `csip-0001.md` — CSIP template and process (initial draft)
- `assets/` — optional diagrams, images, or supporting files (if needed)

## CSIP lifecycle

A CSIP generally goes through the following stages:

- **Draft** — work in progress, may change significantly
- **Review** — ready for wider feedback
- **Final** — considered stable and recommended for adoption
- **Deprecated** — superseded or no longer recommended

## Creating a new CSIP

1. Copy `csip/csip-0001.md` (template) to a new file:
   - `csip/csip-XXXX.md` (zero-padded number)
2. Fill in the header fields and content.
3. Open a Pull Request.

### File naming

- `csip-0001.md`, `csip-0002.md`, ...
- Use four digits, zero-padded.
- Keep one CSIP per file.

## Contributing

- Open an issue to discuss a proposal idea early.
- Keep changes focused and easy to review.
- Prefer small, composable standards (core + optional extensions).

## License

All content in this repository is licensed under the **MIT License** unless stated otherwise in a specific CSIP.
See [LICENSE](LICENSE).
