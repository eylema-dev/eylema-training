# Eyleme training

**One Eyleme brand — 15 October 2026:** [eyleme.dev](https://eyleme.dev/) is the shared home for Eyleme and its community. Eyleme remains a standalone, public Apache-2.0 project. **Eyleme Derleme** and **Eyleme Onama** follow a private-source, paid subscription model as optional products. Commercial services and terms are in development; pricing and availability are unpublished. This repository does not provide a subscription service.

The family is presented as **Derleme → Onama → Eyleme**: prepare data, authorize work, then execute. Eyleme keeps its own basic access controls and does not require either subscription for independent use. See the [public product-family overview](https://github.com/eyleme-dev/eyleme/blob/main/docs/en/product-family.md).

Technical identifiers retain their existing spelling for compatibility. Historical evidence preserves its original names and URLs.

Pinned training recipes and permitted data preparation. [Türkçe](README.tr.md).

**Status: repository scaffold only.** No application, benchmark, catalog entry, trained model or training run is delivered by this setup.

## Scope

Reviewable Unsloth recipes, environment locks, data-lineage formats and candidate evaluation handoffs. Pin and inventory training dependencies before running them. Training produces candidates, never automatic promotion.

Production Rust code, shared types, runtime/model execution and the CLI stay in [Eyleme](https://github.com/eyleme-dev/eyleme); product contracts live in [English docs](https://github.com/eyleme-dev/eyleme-docs-en) and [Turkish docs](https://github.com/eyleme-dev/eyleme-docs-tr). [The repository map](https://github.com/eyleme-dev/devguide/blob/main/docs/en/repository-map.md) defines the boundaries.

## First acceptance gate

Before implementation, open a scoped task with input/output contracts, an exact core revision, meaningful failure cases, dependency inventory and named execution targets. Replace the documentation-only source guard with suitable tests in the same PR that introduces implementation. Documentation CI is not runtime or hardware evidence.

Use [CONTRIBUTING](CONTRIBUTING.md) and [AGENTS](AGENTS.md). Keep private data, credentials, operational records and model weights outside Git. Public artifacts need their own approved storage, provenance and license decision; no store or service is provisioned here. First-party source and documentation are licensed under [Apache-2.0](LICENSE). Separately identified third-party material, model weights and datasets retain their own terms.
