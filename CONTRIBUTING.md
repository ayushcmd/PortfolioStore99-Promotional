# Contributing to PortfolioStore 99 Promotional

Thank you for your interest in improving the PortfolioStore 99 promotional documentation.

## Project scope

This is a **documentation, brand, marketing, and architectural specification repository**, not the production storefront or the source code for commercial portfolio templates.

The current implementation checklist describes the promotional website implementation as **not started and pending separate authorization**. Do not assume that work on the public repository grants permission to implement, publish, or deploy the live storefront.

Useful contributions may include:
- Fixing typos, broken links, unclear explanations, and Markdown formatting
- Clarifying the existing architectural and customer journey documentation
- Improving accessibility guidance, consistency, and documentation navigation
- Reporting stale catalog details or inconsistencies for maintainer verification
- Suggesting improvements to the planned promotional landing page specifications

Changes to pricing, product availability, payment flows, published policies, customer-facing claims, or brand identity require maintainer verification against authoritative sources.

## Read first

- [README.md](README.md) — project overview and document index
- [LICENSE](LICENSE) — proprietary rights and reuse restrictions
- [SECURITY.md](SECURITY.md) — private vulnerability reporting
- [Documentation](docs/) — detailed specifications and implementation checklist

Check [open issues](https://github.com/ayushcmd/PortfolioStore99-Promotional/issues) and existing pull requests before starting. For larger or substantial changes, open an issue to propose the scope first.

## Important licensing and permission rules

**This is not an open-source licensed repository.** The contents are covered by a proprietary, all-rights-reserved license. Public visibility and the ability to open a pull request do not grant permission to reuse, redistribute, commercially exploit, or create derivative versions of protected materials outside authorized contributions.

Only submit text, designs, screenshots, or other material you have the rights and authorization to contribute. Do not copy third-party material without permission. If you are uncertain whether a proposed change is authorized under the repository's license, contact the maintainer before proceeding.

A submitted pull request does **not** by itself establish any special licensing, assignment, or permission terms beyond those actually agreed by the relevant rights holders. Maintainers may request clarification or authorization before accepting it.

## Propose and make a change

1. Check existing issues and read the relevant Markdown document in `docs/`.
2. For material content, policy, licensing, or brand changes, discuss the proposal with the repository owner first.
3. If authorized to contribute, make a descriptive branch from `main`, such as `docs/fix-catalog-links` or `docs/clarify-customer-journey`.
4. Keep each change narrowly scoped and maintain the document's terminology and section structure.
5. Verify any facts against existing authoritative documentation; explain uncertainties rather than inventing new pricing, product claims, or customer policies.
6. Use relative Markdown links for repository files, and prefer official storefront URLs for published policies.
7. Do not commit credentials, internal customer/order data, unreleased source code, private API details, or sensitive screenshots.

There is no root application package or build process required for ordinary Markdown changes in this repository. The production storefront is maintained separately.

## Documentation review checklist

Before submitting a PR, check the following:

- Markdown headings, lists, tables, and code fences render cleanly.
- Internal links point to existing files and section anchors.
- Website links, demo links, and policy links are relevant and clearly labeled.
- Commercial and technical claims are either supported or identified as requiring verification.
- Screenshots and images have suitable alternative text when used in Markdown.
- There are no secrets, customer details, internal credentials, or unpublished commercial assets in the change.
- Any modification to the brand system stays consistent with [brand and design guidance](docs/brand-and-design-system.md).

If you use a Markdown linter or link checker, mention it in the PR description. **Do not claim automated checks or tests were run unless you actually ran them.**

## Pull request expectations

Target `main`. Include:
- A concise explanation of the change and why it helps
- A link to any related issue
- Which documents or asset files changed
- How links and factual claims were validated
- Any areas needing owner approval (especially commercial claims, policy, rights, pricing, or branding)
- Screenshots or previews for meaningful visual asset changes, where appropriate

Give credit to actual collaborators. A `Co-authored-by` trailer should only be included when that person or account genuinely helped create the commit; it is not a substitute for real collaboration.

Maintainers may request revisions or decline submissions that conflict with commercial, brand, privacy, or legal requirements.

## Help and reporting

For ordinary corrections and proposals, use [GitHub Issues](https://github.com/ayushcmd/PortfolioStore99-Promotional/issues).

For security findings, use the private channel documented in [SECURITY.md](SECURITY.md), **not** a public issue.

For customer purchases, download problems, or storefront support, use the official support email already published in the project: [portfoliostore99@gmail.com](mailto:portfoliostore99@gmail.com).

Thank you for helping keep these specifications clear, accurate, and useful.
