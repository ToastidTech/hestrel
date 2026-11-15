# Hestrel

**Every Estimate Has a Witness.**

Hestrel is a field-estimate PWA for home-services businesses (HVAC first). A technician builds an estimate from the business's own price book, captures the customer's signed consent before work is discussed, gets a separate signed approval, and hands over a print-ready packet — consent page included — then converts the approved estimate to an invoice carrying the business's own payment link. Toastid Tech is never the merchant of record.

- Single-file PWA (`index.html`) — no build step, no backend required to run
- Disk-first: every keystroke saves locally, so a dead battery or dropped signal loses nothing
- Config-driven content packs per trade (HVAC pack included, prices set by the business at setup)
- Two distinct signatures: consent to the on-site conversation, then approval of the work

Status: v1 core (estimate core, consent + approval, packet, invoice) plus Step 4 dictation — consent-gated Web Speech API capture that structures speech into proposed line items for tech review. Cloud consent storage is on the roadmap.

A Toastid Tech, LLC product.
