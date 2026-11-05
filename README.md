# PJCAgeniespace
%md
# PJCAgeniespace

Version-controlled configuration exports for Databricks Genie spaces.

## Genie spaces

| Space | Room ID | Description |
|---|---|---|
| Healthcare Claims and Patient Analytics | 01f1d3a58c8c13828af69606128772c8 | Analyzes MPS II healthcare claims, patient journeys, HCP/HCO performance, payer mix, and territory-level trends. |

## Contents

Each Genie space export is a JSON file containing the space's title, description, warehouse, attached tables, text instructions, SQL snippets and joins, SQL examples, column settings, starter questions, and benchmarks.

## Workflow

- `main` holds the reviewed baseline configuration.
- Changes to a Genie space are exported to a feature branch and merged into `main` through a pull request.
