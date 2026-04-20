# DIGITAL LYFESTYLE, LLC — 2025 Financial Statements

**Entity:** Digital Lyfestyle, LLC (Houston, TX)
**Owner:** Christopher L. Hydrick
**Period covered by available data:** Jan 1 – Dec 31, 2025 (checking) / Mar 23 – Oct 22, 2025 (credit card)
**Source data:** 19 unique Chase PDF statements (see `transactions.csv`)
**Prepared:** 2026-04-20

> **Scope caveat (read first).** These statements are built **only** from two accounts:
> Chase Business Complete Checking `...9118` and Chase Ink Business Card `...3373`.
> The data clearly references at least two additional Chase accounts — `...3318` and `...3501` — plus a "Spend-Everyday" account `...4382`, none of which were provided. **No revenue deposits, payroll, or the credit-card autopay funding leg are visible in the supplied data.** The P&L below therefore reflects **expenses only**; the Cash Flow and Balance Sheet are **partial**. Treat every total as a floor, not the full picture. Open questions are listed at the end and in `business_profile.md`.

---

## 1. Reconciliation Summary (100% tie)

### Checking `...9118` — 12 monthly statements (Jan–Dec 2025)

| Month | Beg Balance | Deposits/+ | Withdrawals/− | End Balance | Ties? |
|---|---:|---:|---:|---:|:--:|
| Jan 2025 | 7,985.00 | 0.00 | 0.00 | 7,985.00 | ✓ |
| Feb 2025 | 7,985.00 | 0.00 | 5,985.00 | 2,000.00 | ✓ |
| Mar 2025 | 2,000.00 | 0.00 | 0.00 | 2,000.00 | ✓ |
| Apr 2025 | 2,000.00 | 0.00 | 0.00 | 2,000.00 | ✓ |
| May 2025 | 2,000.00 | 0.00 | 0.00 | 2,000.00 | ✓ |
| Jun 2025 | 2,000.00 | 0.00 | 0.00 | 2,000.00 | ✓ |
| Jul 2025 | 2,000.00 | 100.00 | 0.00 | 2,100.00 | ✓ |
| Aug 2025 | 2,100.00 | 0.30 | 0.30 | 2,100.00 | ✓ |
| Sep 2025 | 2,100.00 | 1,500.00 | 0.00 | 3,600.00 | ✓ |
| Oct 2025 | 3,600.00 | 0.00 | 0.00 | 3,600.00 | ✓ |
| Nov 2025 | 3,600.00 | 0.00 | 0.00 | 3,600.00 | ✓ |
| Dec 2025 | 3,600.00 | 3,000.00 | 0.00 | 6,600.00 | ✓ |

Full-year net change: **+$1,385** movement in (after netting the Feb $5,985 outflow to account 4382 against $4,700 inbound transfers).

### Credit Card `...3373` — 7 unique cycle statements (Mar 23 – Oct 22, 2025)

| Cycle (≈ 22nd–22nd) | Prev Balance | + Purchases | + Fees | − Payments | New Balance | Ties? |
|---|---:|---:|---:|---:|---:|:--:|
| Mar 23 – Apr 22 | 0.00 | 21.72 | 0.65 | 0.00 | 22.37 | ✓ |
| Apr 23 – May 22 | 22.37 | 21.91 | 0.65 | 44.93 | 0.00 | ✓ |
| May 23 – Jun 22 | 0.00 | 54.45 | 0.67 | 0.00 | 55.12 | ✓ |
| Jun 23 – Jul 22 | 55.12 | 49.09 | 0.67 | 55.12 | 49.76 | ✓ |
| Jul 23 – Aug 22 | 49.76 | 3,049.16 | 0.67 | 49.76 | 3,049.83 | ✓ |
| Aug 23 – Sep 22 | 3,049.83 | 2,459.56 | 0.68 | 3,049.83 | 2,460.24 | ✓ |
| Sep 23 – Oct 22 | 2,460.24 | 2,758.97 | 0.66 | 2,460.24 | 2,759.63 | ✓ |
| **YTD (7 cycles)** | — | **8,414.86** | **4.65** | **5,659.88** | **2,759.63** | ✓ |

**Nov 2025 and Dec 2025 credit-card statements were not provided** (see Open Questions).

---

## 2. Income Statement (YTD 2025)

Because no revenue-bearing deposits were observed in the provided data, this is effectively an **Operating Expense Schedule**. Dollar amounts are in USD; credit card cycle data runs through **Oct 22, 2025** only.

| Line | 2025 YTD ($) | Notes |
|---|---:|---|
| **Revenue** | **0.00** | No identifiable customer receipts in `9118`. Revenue — if any — is routing through accounts not supplied (likely `3318`, `3501`, or external Stripe/PayPal balances). |
| | | |
| **Operating Expenses** | | |
| Contractor / Professional Services | 8,120.00 | PayPal → CJONESMEDIA (Omaha NE); three payments Aug/Sep/Oct |
| Software & Subscriptions | 294.86 | Squarespace (7 × ~$22), Replit (5 × $26.65), OpenAI ($5.32) |
| Bank & FX Fees | 4.65 | 3% foreign-transaction fees on the THB Squarespace charges |
| **Total Operating Expenses** | **8,419.51** | |
| | | |
| **Net Operating Income (Loss)** | **(8,419.51)** | Pre-tax; no revenue visible |

### Expense detail — Contractor / Professional Services
| Date | Vendor | Amount | Notes |
|---|---|---:|---|
| 2025-08-18 | PayPal *CJONESMEDIA | 3,000.00 | 402 area code = Omaha NE |
| 2025-09-17 | PayPal *CJONESMEDIA | 2,410.00 | |
| 2025-10-13 | PayPal *CJONESMEDIA | 2,710.00 | |
| **Total** | | **8,120.00** | |

### Expense detail — Software & Subscriptions
| Vendor | Count | Unit range | Total |
|---|---:|---|---:|
| Squarespace (billed in THB) | 7 | $21.72 – $22.91 | 156.29 |
| Replit | 5 | $26.65 | 133.25 |
| OpenAI | 1 | $5.32 | 5.32 |
| **Total** | **13** | | **294.86** |

> **Note on Squarespace:** billing in Thai Baht (724.88 THB/month) suggests the account's billing address or payment method is registered in Thailand, consistent with a digital-nomad positioning but worth confirming.

---

## 3. Cash Flow Statement — Partial (Account 9118 only)

Only checking `...9118` shows cash movement at the bank-ledger level; credit card `...3373` is a liability, not cash.

| Category | 2025 ($) |
|---:|---:|
| **Operating activities** | |
| Cash received from customers | 0.00 |
| Cash paid to vendors / contractors | 0.00 |
| PayPal verification (micro) — in | 0.30 |
| PayPal verification (micro) — out | (0.30) |
| **Net cash from operating** | **0.00** |
| | |
| **Investing activities** | 0.00 |
| | |
| **Financing activities (inter-account owner movement)** | |
| Transfer to account `...4382` ("Spend-Everyday") | (5,985.00) |
| Transfer in from `...3501` (Jul) | 100.00 |
| Transfer in from `...3501` (Sep) | 1,500.00 |
| Transfer in from `...3318` (Dec) | 3,000.00 |
| **Net cash from financing** | **(1,385.00)** |
| | |
| **Net change in cash (9118)** | **(1,385.00)** |
| Beginning cash (9118), Jan 1 | 7,985.00 |
| Ending cash (9118), Dec 31 | 6,600.00 |

> Classification note: inter-account transfers between related Chase accounts of the same LLC are **not** GAAP operating cash flows; they are internal cash repositioning. Shown under financing here only because they are the only movement in the account. A proper cash flow statement requires the `3318`/`3501`/`4382` statements.

---

## 4. Balance Sheet — Partial Snapshot, Dec 31, 2025

Only two of the entity's known accounts were available, so this is a **two-line snapshot**, not a complete balance sheet.

| | Dec 31, 2025 ($) |
|---|---:|
| **Assets** | |
| Cash — Chase Checking `...9118` | 6,600.00 |
| *Cash — Chase `...3318`* | *not provided* |
| *Cash — Chase `...3501`* | *not provided* |
| *Cash — Chase Spend `...4382`* | *not provided* |
| *Accounts Receivable* | *not provided* |
| *Fixed assets / intangibles* | *not provided* |
| **Total Assets (from available data)** | **6,600.00** |
| | |
| **Liabilities** | |
| Credit Card — Chase Ink `...3373` (balance at Oct 22) | 2,759.63 |
| *Credit Card — Chase Ink `...3373` (Dec 31 balance)* | *not provided — Nov & Dec cycles missing* |
| *Accounts payable, loans, accruals* | *not provided* |
| **Total Liabilities (from available data)** | **2,759.63** |
| | |
| **Equity** | |
| Member's equity | *not derivable without full books* |

---

## 5. Confidence & Uncertainty Register

| Item | Confidence | Reason |
|---|---|---|
| Every line in `transactions.csv` | **100%** | Each statement reconciles to the penny; chained balances tie across periods |
| Expense categorization | **High** | Merchant names are unambiguous (Squarespace, Replit, OpenAI, CJONESMEDIA) |
| **Revenue figure = $0** | **Low (as a business conclusion)** | We are confident no revenue hit `9118`; we have no basis to conclude zero revenue for the business |
| Credit-card balance at year-end | **Low** | Nov & Dec 2025 cycles were not provided |
| CJONESMEDIA classified as Contractor | **Medium** | Vendor name + PayPal suggests contractor; could also be media buy or affiliate payout — form 1099 determination depends on relationship |
| Transfers classified as financing | **Medium** | True classification depends on purpose (owner draw vs. intercompany sweep), which requires user input |
| "Squarespace THB" = Thailand operations | **Medium** | Billing currency ≠ business operations with certainty; could be a legacy account setting |

---

## 6. Open Questions (material)

These block a fully-accurate set of statements. Details in `business_profile.md`.

1. **Statements for accounts `...3318`, `...3501`, and `...4382`** — without these, revenue and the credit-card autopay funding leg are invisible.
2. **November & December 2025 credit-card cycles** — needed for Dec 31 balance-sheet liability.
3. **Fiscal year** — calendar year assumed; confirm.
4. **LLC tax classification** — disregarded SMLLC vs. multi-member vs. S-corp (drives how transfers are labeled).
5. **Revenue model** — memberships, events, courses, sponsorships, affiliate? Where does the money land?
6. **CJONESMEDIA relationship** — 1099 contractor, vendor, or ad-spend reseller?
7. **Any off-bank channels** (Stripe balance, PayPal balance, cash) that never flow through Chase?
