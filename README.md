<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/disclosery/disclosery/main/assets/disclosery-wordmark-inverse.svg">
  <img src="https://raw.githubusercontent.com/disclosery/disclosery/main/assets/disclosery-wordmark.svg" alt="Disclosery" width="328">
</picture>

### SEC ownership data for researchers and developers

[Disclosery](https://disclosery.com/) connects SEC ownership disclosures, institutional holdings, and filing history with a structured JSON API and a hosted Model Context Protocol (MCP) endpoint. Follow the reporting entity, inspect a disclosed quarter, and keep the source filing within reach.

**[Explore the website](https://disclosery.com/) · [API and MCP setup](https://disclosery.com/docs) · [API contract](https://disclosery.com/llms-api.txt) · [Data coverage](https://disclosery.com/data)**

## Build with Disclosery

Start with **[disclosery-examples](https://github.com/disclosery/disclosery-examples)** for runnable API recipes and assistant connection instructions:

- **Find a reporting organization.** Search firms and filing entities by name or CIK; distinguish a founder or historical manager from the organization making the disclosure.
- **Inspect filings and a quarterly portfolio.** Select an available reporting period and retain its units, filing provenance, and source links.
- **Connect an assistant.** Use the hosted MCP endpoint at [`https://disclosery.com/mcp`](https://disclosery.com/mcp) to search and retrieve ownership facts through the same underlying queries.

Read the [connection guide](https://disclosery.com/docs) for authentication and current usage limits. Never put an API key in a URL, repository, or notebook output.

## Understand the disclosure

13F holdings are a reported snapshot of covered securities held by a reporting institution. They are not a person's personal portfolio, a complete view of every fund's assets, or real-time trades. Historical relationships and missing coverage matter; check the [coverage notes](https://disclosery.com/data) and the linked filing before drawing a conclusion.

## Work with us

Found a confusing example or want a new research recipe? [Open an issue in the examples repository](https://github.com/disclosery/disclosery-examples/issues). For account and service help, visit [Disclosery](https://disclosery.com/).
