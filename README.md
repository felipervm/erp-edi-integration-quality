# From Order to Handoff

**An interactive ERP / EDI systems-quality case study** by Felipe Mattos.

### [Explore the live interactive experience](https://felipervm.github.io/erp-edi-integration-quality/)

Built as an independent work sample inspired by the responsibilities of a Junior Business Systems Analyst. Not affiliated with, endorsed by, or commissioned by SureWerx.

## The problem

How should an analyst handle an inbound distributor purchase order that reaches an ERP system with incomplete or inconsistent information? In particular, how do you turn a detected exception into an actionable support ticket, realistic acceptance checks and a safe handoff?

## Explore the four synthetic failure modes

| Scenario | Risk | Analytical response |
| --- | --- | --- |
| Unmapped partner SKU | Wrong product or blocked fulfillment | Verify against approved product master data; request authorized mapping |
| Unit-of-measure mismatch | Wrong shipped quantity | Normalize using approved conversion; reconcile line quantity and amount |
| Duplicate EDI 850 replay | Duplicate order, shipment, or invoice | Validate idempotency key and correlate existing ERP order |
| Price variance | Margin or invoicing dispute | Confirm approved contract, effective dates and extended amounts |

Each scenario updates a simulated comparison table, four quality checks, corrected displayed values, a structured incident record and case-specific UAT criteria. The **Apply proposed fix** control only represents a proposed resolution in the local display. It does not process orders or change real data.

## What this demonstrates

- EDI-to-ERP transaction reasoning and field-level reconciliation
- Exception intake, business impact and issue routing
- Product and business master-data validation
- UAT: positive, negative and regression testing
- Incident documentation and operational handoff
- Clear stakeholder communication and responsible escalation

## Design and technology

A cinematic, high-contrast editorial experience with Boon-inspired image composition and typography, and a SureWerx-inspired black, white and orange palette. Includes a responsive portrait and introduction section for Felipe. Implemented with **semantic HTML, responsive CSS and vanilla JavaScript**. Interactions include an animated progress rail, scenario selection, proposed corrections and reset. Content remains visible without animation or JavaScript. Accessibility accommodations include keyboard-focus states, descriptive labels and `prefers-reduced-motion` handling.

No frontend framework, build pipeline, database, API key or vendor integration required.

## Run locally

Open `index.html` in a modern browser. For a local server, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Integrity note

**Every company, transaction, item, amount and incident in the demonstration is fictional.** The case uses an illustrative EDI 850 intake pattern and does not represent production EDI parsing, an actual ERP integration, a live SureWerx environment or authorized release decisions. The simulation is intentionally scoped to analytical judgment, quality controls, documentation and handoff.

---

[Felipe Mattos on GitHub](https://github.com/felipervm) · [LinkedIn](https://www.linkedin.com/in/felipervm/)

## Visual references and assets

- UI/UX composition reference: https://www.boonglobal.io/
- Brand palette and industrial imagery: https://surewerx.com/
- `assets/logistics.jpg`: public SureWerx image, https://media.surewerx.com/transform/86d6fbea-4d85-4cb7-80bd-22473d453c9b/MC201_UD
- `assets/felipe.jpg`: portrait supplied by Felipe for this portfolio.

Company photography and branding remain the property of their respective owners. This is an independent application portfolio, not an official company website.
