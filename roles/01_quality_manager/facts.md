# Quality Manager

## Draft

### Recall facts

- **Product and batch:** ClearBreath Cough Syrup, oral liquid, 120 mL; batch **4471**; expiration **February 28, 2029**. Batch 4470 passed testing and is outside this recall. (Source: `inputs/batch_report.md`)
- **Finding and risk:** Northbridge Product Laboratory found an unintended microbial contaminant in batch 4471; it fails release specification. Exposure may cause nausea, vomiting, diarrhea, or fever. Children under 12 are at higher risk. (Source: `inputs/batch_report.md`)
- **Affected stores:** Batch 4471 was delivered to S01–S04 and S06–S13. Of these, **11 are currently operating stores: S01–S04 and S06–S12**. S13 (Harbor Annex) ceased trading on March 31, 2027; its remaining stock was transferred to the central warehouse. S05's sales row is for batch 4470, not 4471. Customers may return product to any operating CareWell store. Do not direct customers to S13. (Sources: `inputs/batch_report.md`, `inputs/store_list.csv`, `inputs/company_policy.md`)
- **Distribution / inventory / sales:** CareWell received 1,200 bottles; 311 were held at the warehouse and 889 distributed to stores. Store stock control reports 216 bottles remaining across shipment destinations (including S13's recorded zero), leaving 673 distributed bottles not on hand. Sales rows explicitly labeled 4471 total 609 bottles. S08's row records **batch 4417, 64 bottles**, although the lab distribution register shows 75 bottles of 4471 delivered to S08 and the row's dates fit the 4471 sales period. Treat S08's batch code as a likely data-entry error and its 64 bottles as 4471 **for reconciliation only**: 609 + 64 = 673, matching 889 distributed less 216 on hand. Confirm this correction with source records before representing S08's 64 units as confirmed sales. (Sources: `inputs/batch_report.md`, `inputs/sales_records.csv`)
- **Sales dates:** Sales records run through April 15, 2027. Listed date spans for batch 4471 (including the likely S08 miscoded row) begin February 16, 2027, and extend through April 15 for open stores; S13's historical sales end March 31, 2027. (Sources: `inputs/sales_records.csv`, `inputs/company_policy.md`)
- **Key response dates:** Batch 4471 was manufactured February 8, bottled February 9, and shipped to CareWell/stores February 15, 2027. The lab report was released April 16, 2027 at 9:00 AM Eastern; no customer returns were recorded at that report time. Response package due April 18, 2027 at 9:00 AM Eastern; first status update due April 19 at noon Eastern. The recall hotline begins April 16. (Source: `inputs/batch_report.md`)
- **Recall hotline:** **1-800-555-0199**, staffed daily **8:00 AM–8:00 PM Eastern**, beginning April 16. The service manual's general hotline, 1-800-555-0119, is different; use the batch report's recall-specific number. (Sources: `inputs/batch_report.md`, `inputs/company_policy.md`)
- **Customer actions:** Stop using the product; keep the bottle away from children; return it to any operating CareWell store for a full refund. A receipt is not required; bring the bottle if available. Service policy says refund to the original payment method where possible, otherwise cash. Anyone feeling unwell after taking it should contact a healthcare professional promptly; severe symptoms require urgent medical help. (Sources: `inputs/batch_report.md`, `inputs/company_policy.md`)
- **Store response:** Immediately quarantine remaining stock and log all returns. Record product, quantity, date, and store; quarantine returned goods for quality-team collection; do not resell. (Sources: `inputs/batch_report.md`, `inputs/company_policy.md`)

### Current operating stores receiving batch 4471

| ID | Store | Address | Phone |
|---|---|---|---|
| S01 | CareWell Central | 112 Oak Street, Northbridge, Ohio 44000 | 216-555-0101 |
| S02 | CareWell Oak Square | 124 River Road, Northbridge, Ohio 44000 | 216-555-0102 |
| S03 | CareWell Riverside | 136 West Avenue, Northbridge, Ohio 44000 | 216-555-0103 |
| S04 | CareWell Westgate | 148 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0104 |
| S06 | CareWell Hillcrest | 172 River Road, Northbridge, Ohio 44000 | 216-555-0106 |
| S07 | CareWell South Market | 184 West Avenue, Northbridge, Ohio 44000 | 216-555-0107 |
| S08 | CareWell Lakeview | 196 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0108 |
| S09 | CareWell Maple Plaza | 208 Oak Street, Northbridge, Ohio 44000 | 216-555-0109 |
| S10 | CareWell East Point | 220 River Road, Northbridge, Ohio 44000 | 216-555-0110 |
| S11 | CareWell Garden Center | 232 West Avenue, Northbridge, Ohio 44000 | 216-555-0111 |
| S12 | CareWell North Commons | 244 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0112 |

## Evidence

- The laboratory report identifies batch 4471 as contaminated and 4470 as tested/passed, and gives the distribution, stock, safety instructions, recall hotline, and response timeline.
- Matching the delivery register to the active directory excludes closed S13 from current customer destinations; the service manual says the other 12 locations remain open.
- Sales CSV exceptions: S05 is batch 4470; S08 says 4417; S13 sales are historical. Rows explicitly labeled 4471 sum to 609. S08's 64 bottles are the only apparent addition needed to reconcile sales to 889 distributed less 216 on hand (673). This supports, but does not independently prove, the likely S08 miscoding.
- The recall report gives 1-800-555-0199 while the general service manual gives 1-800-555-0119. Use the recall-specific number and hours in recall communications.

## Handoff

Use batch 4471 and recall hotline 1-800-555-0199 (daily 8 AM–8 PM Eastern). List the 11 operating receiving stores above; explain that returns are accepted at any operating CareWell store with no receipt required. Do not include S13 as an operating store. Preserve the S08 batch-code discrepancy and label the 64-unit correction as an inference pending source confirmation; with that correction, sales and on-hand quantities reconcile to the 889 bottles distributed.
