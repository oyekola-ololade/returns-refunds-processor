# Template Status & Verification

**Classification:** Configurable n8n template asset — not a verified production deployment.

The workflow export and documentation are inspectable template evidence. They do not prove a configured production refund system, payment accuracy guarantee, SLA, ROI, or client outcome.

## Verification gate
1. Parse/import into a clean current n8n instance.
2. Inspect eligibility rules, amount calculations, idempotency, payment/refund actions, branches, expressions, and Code nodes.
3. Replace placeholder ecommerce/payment credentials, order/store IDs, URLs, webhooks, and resource references.
4. Run eligible, ineligible, duplicate/replay, partial-refund, malformed-input, and provider-failure cases.
5. Require human review for high-consequence/ambiguous refunds unless exact business rules explicitly allow automation.
6. Verify no duplicate financial side effects and record configured test date/result.

## Security
Never commit payment/store tokens, customer PII, private webhooks, or production order/payment data. Use sandbox/test credentials and synthetic orders.

## Change record
- **2026-09-03:** Added repository verification/security/status control. No workflow-logic change or runtime pass is implied.
