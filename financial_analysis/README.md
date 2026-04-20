# Digital Lyfestyle, LLC — Financial Analysis

Deliverables extracted from 20 Chase bank & credit-card PDF statements (period: 2025 calendar year for checking `...9118`; Mar 23 – Oct 22, 2025 for credit card `...3373`).

## Files

- [`transactions.csv`](./transactions.csv) — every transaction extracted from the statements. Columns: `date, account, description, amount, direction, category, source_file, notes`. All statements reconcile to the penny.
- [`financial_statements.md`](./financial_statements.md) — Income Statement, Cash Flow, and partial Balance Sheet, plus per-statement reconciliation tables and confidence register.
- [`business_profile.md`](./business_profile.md) — Inferred business type, counterparty list, and prioritized open questions.

## Headline findings

1. **All 19 unique statements reconcile exactly.** (One PDF was a duplicate, one was misnamed — both handled.)
2. **No revenue deposits are visible in the supplied data.** Revenue and the credit-card autopay funding both appear to flow through accounts `...3318` / `...3501`, which were not provided.
3. **Visible 2025 operating expenses: $8,419.51** — dominated by contractor payments to CJONESMEDIA ($8,120), with Squarespace/Replit/OpenAI subscriptions and minor FX fees.
4. **Business type:** digital-nomad community / membership platform (public brand matches spend pattern).
5. **Missing data blocks a full picture** — see the Open Questions in `business_profile.md`.
