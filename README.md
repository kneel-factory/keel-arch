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
