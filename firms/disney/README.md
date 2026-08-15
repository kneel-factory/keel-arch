# Disney — public reconstruction

Disney+ on AWS is the only thick public map. Parks, studio, and Hulu/ESPN+ internals stay empty.

## Public

- **Disney+** — streaming product.
- **AWS control plane** — DynamoDB global tables for Continue Watching / Watchlist / recommendations; Kinesis ingest (re:Invent DAT304, Disney+ Content Discovery).
- **CDN / object store** — CloudFront + S3 are what AWS and Disney have put on a stage. Treat as the sold/used cloud, not a Disney-internal name.
- **Hulu / ESPN+** — public products. Shared stack with Disney+ is **plausible, not sourced**.
- **Parks / studio** — exist as businesses. System names **unknown**.

## Unknown
- Parks POS / CRM / reservation names.
- Studio finance / MAM / ERP.
- Disney’s own employee ITSM.
