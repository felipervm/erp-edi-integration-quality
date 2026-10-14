# From Order to Handoff

**Independent ERP / EDI integration quality work sample by Felipe Mattos** — designed for the Junior Business Systems Analyst role at SureWerx.

## What it shows

An interactive, entirely **fictional** EDI 850 purchase order flowing through a simulated item translation and ERP order process. Explore four failure modes:

1. Unmapped SKU
2. Unit-of-measure / quantity mismatch
3. Duplicate order replay
4. Price / line total variance

For each, the page includes field-level comparisons, a quality checklist, a mock remediation, a reproducible issue ticket, UAT cases, and business/support handoff notes.

**Important:** This is a scenario-based demo of analytical judgment and documentation — not a functioning EDI translator or ERP integration. Clicking “Apply proposed fix” simulates what success conditions could look like; it does not execute real data changes, verify a real mapping, or constitute approval to release an order. All records and data are invented.

## Run

Open `index.html` in a browser. No packages, build process, or external services required. The design optionally loads fonts from Google; system font fallbacks are provided.

## Technical focus

- Requirements and workflow framing
- Data mapping, validation and reconciliation
- Root-cause triage and escalation
- UAT, regression tests and acceptance criteria
- SOP and handoff communication

## Research context

SureWerx publicly describes a broad portfolio covering PPE, safety footwear, infrastructure safety, and tools: https://surewerx.com/en-ca/content/BRANDS . The fictitious SKU codes in the demo use product-family-inspired prefixes for storytelling only and are **not SureWerx item numbers**, nor is the architecture intended as a representation of SureWerx internal systems.

## Author

Felipe Mattos · https://github.com/felipervm · https://www.linkedin.com/in/felipervm/