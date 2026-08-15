# Keel Arch

Public reconstructions of Fortune 500 enterprise-architecture *shapes*.
Not internal diagrams. Not leaked systems. Not a claim we have Goldman’s boxes.

Each firm folder is a public-source map: channels, CRM/CX, core, risk/KYC, lakehouse.
Sources go in the same folder. If a source is not public, the box is empty.

## Layout

```
firms/<slug>/
  README.md          # what is public vs unknown
  landscape.mmd      # mermaid shape
  SOURCES.md         # URLs
  C360.md            # customer-360: public vs plausible vs empty
  SYSTEMS.md         # sniffed CS/marketing/ops names
```

Goldman Sachs is the template, not the exception.


## First batch

- [firms/goldman-sachs](firms/goldman-sachs/) — template
- [firms/jpmorgan-chase](firms/jpmorgan-chase/)
- [firms/bank-of-america](firms/bank-of-america/)
- [landscape/financial-services](landscape/financial-services/) — BIAN-shaped generic
- [firms/morgan-stanley](firms/morgan-stanley/)
- [firms/wells-fargo](firms/wells-fargo/)
- [firms/blackrock](firms/blackrock/)

Next batches go under `firms/<slug>/`. Empty boxes stay empty.

- [firms/visa](firms/visa/)
- [firms/capital-one](firms/capital-one/)
- [firms/citigroup](firms/citigroup/)
- [firms/american-express](firms/american-express/)
- [firms/mastercard](firms/mastercard/)
- [firms/charles-schwab](firms/charles-schwab/) — thin

New bar (2026-08-16): every firm gets C360.md + SYSTEMS.md. Public sniff first. Plausible stays labeled. Empty stays empty.

- [firms/paypal](firms/paypal/)
- [firms/microsoft](firms/microsoft/)
- [firms/progressive](firms/progressive/) — thin
