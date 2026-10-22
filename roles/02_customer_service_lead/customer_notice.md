# Customer Service Lead

Write a plain-language notice: what happened, what to do, and who to call. Cite input file names and show your reasoning.

## Draft

### Recall notice: ClearBreath Cough Syrup, batch 4471

CareWell Pharmacy is recalling **ClearBreath Cough Syrup, 120 mL bottles, batch 4471**, made by Cedar Health Products. The affected bottles expire on **February 28, 2029**. Check your bottle's label for the batch number. **Batch 4470 is not included in this recall.**

Testing found microbial contamination in batch 4471. Taking this syrup may cause nausea, vomiting, diarrhea, or fever. **Children under 12 are at higher risk.**

**What to do**

- Stop using batch 4471 immediately and keep the bottle away from children.
- Return it to **any operating CareWell Pharmacy store for a full refund**. Bring the bottle if available. **No receipt is required**, and you do not need to return to the store where you bought it.
- Your purchase price will be refunded to your original payment method where possible; otherwise, a cash refund will be offered.
- If you feel unwell after taking it, contact a healthcare professional promptly. **For severe symptoms, seek urgent medical help.**

Affected sales records cover **February 16–April 15, 2027**. Use the batch number to identify recalled bottles; do not rely only on when or where you bought the syrup. Harbor Annex closed on March 31, 2027. If you bought your bottle there, return it to another operating CareWell store.

**Questions? Call the recall hotline: 1-800-555-0199**, daily **8 AM–8 PM Eastern**, beginning April 16, 2027.

Notice sources: `inputs/batch_report.md` (Product and testing; Distribution and response; Appendix A), `inputs/company_policy.md` (refund procedures; Directory administration), and `inputs/sales_records.csv` (affected sales period, with the Lakeview discrepancy explained below).

## Evidence

| Topic | Supporting source and reasoning |
| --- | --- |
| Product and identification | `inputs/batch_report.md`, Product and testing, identifies ClearBreath Cough Syrup, 120 mL, Cedar Health Products, batch 4471. Appendix A supplies the expiration date, February 28, 2029. Batch 4470 passed testing and is explicitly outside the recall. |
| Risk and customer actions | `inputs/batch_report.md`, Product and testing and Distribution and response, supports the four listed symptoms, higher risk for children under 12, stopping use, keeping bottles away from children, returning bottles, and the stated medical-help instructions. No organism name or confirmed illness count is supplied; neither is invented. |
| Refunds | `inputs/batch_report.md`, Distribution and response, says full refund at any operating store, bottle if available, and no receipt required. `inputs/company_policy.md`, opening paragraph and customer service instructions, agrees and specifies original payment method where possible, otherwise cash. No refund deadline is supplied, so none is added. |
| Conflicting hotline | `inputs/company_policy.md`, January 2027 edition, lists general customer hotline **1-800-555-0119**. `inputs/batch_report.md`, released April 16, 2027, explicitly assigns **1-800-555-0199** to this recall, beginning April 16. The notice uses the newer, recall-specific instruction. Both sources give daily 8 AM–8 PM Eastern hours. The conflict is disclosed for team review rather than silently treated as agreement. |
| Lakeview batch discrepancy | `inputs/sales_records.csv`, S08 row, labels 64 sales as **4417**. `inputs/batch_report.md` says only batches 4470 and 4471 were supplied in January–April and explicitly records S08 receiving 75 bottles of **4471** on February 15, with 11 remaining. **75 − 11 = 64**, matching the sales row. This supports treating 4417 as a likely transcription error and including Lakeview in the affected sales analysis; the source row remains unchanged and needs Quality Manager confirmation. `inputs/store_list.csv` identifies S08 as CareWell Lakeview. |
| Sales period and reconciliation | Rows explicitly labeled 4471 in `inputs/sales_records.csv` total **609 bottles**. Including S08’s 64 bottles gives an **inferred reconciliation total of 673, pending source confirmation**, not a confirmed sales count. The date spans **February 16–April 15, 2027** and the inferred total is calculated as 76 + 59 + 68 + 54 + 62 + 45 + 64 + 50 + 58 + 46 + 53 + 38. This matches `inputs/batch_report.md`: **889 distributed − 216 store stock = 673**; **311 warehouse + 216 store stock + 673 inferred sold = 1,200 received**. The report states no returns at report time. These checks support the interpretation; they do not establish a number of individual customers. |
| Closed store and directory gap | `inputs/sales_records.csv` includes S13, with 38 affected bottles sold February 19–March 31. `inputs/store_list.csv` lists S01–S12 only. `inputs/company_policy.md`, Directory administration, explains that S13 Harbor Annex closed March 31 and its historical sales remain in the archive; the April 1 directory lists current sites. Its address is 13 Harbor Lane, Northbridge, Ohio 44000. No direct S13 phone is provided; the policy gives HQ Records at 1-800-555-0150 for closed-store records, not as the public recall hotline. The notice directs former S13 customers to operating stores. |
| Stores selling affected stock versus return locations | `inputs/sales_records.csv` identifies affected sales at S01–S04 and S06–S13, including S08 as explained above: 12 historical selling locations, 11 still open. S05 sold 81 bottles of excluded batch 4470 and has no batch 4471 shipment in `inputs/batch_report.md`. The 12 current stores in `inputs/store_list.csv`, including S05, may accept returns under `inputs/company_policy.md`; selling affected stock and accepting returns are different categories. |
| Communication information not supplied | `inputs/company_policy.md` requires a printed recall notice at each store counter. `inputs/regulator_form.md` asks for communication channels and a schedule, but supplies no launch schedule. `inputs/batch_report.md` gives an April 18, 2027, 9 AM Eastern response-package deadline, not a publication time. The draft does not claim the notice has been issued or promise unsupported outreach dates. |

## Handoff

- Customer notice is drafted above for review; it has not been published. Preparation is Codex-led in response to the student's requested scope, not evidence of independent student verification.
- Quality Manager: confirm the S08 batch interpretation and reconcile the two hotline entries using the recall-specific report before final release. Preserve the distinction between 12 historical affected selling locations and 12 currently operating return locations.
- Use batch **4471**, expiration **February 28, 2029**, hotline **1-800-555-0199**, and **daily 8 AM–8 PM Eastern** consistently across team messages. Do not include batch 4470 in the recall or direct returns to closed Harbor Annex.
- Team: confirm the notice's release schedule and arrange printed copies at operating store counters as required by `inputs/company_policy.md`. No publication schedule or completed distribution is assumed here.
- Only this assigned role file is changed. The notice remains a draft for team review and submission.
