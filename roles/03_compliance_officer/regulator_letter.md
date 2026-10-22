# Compliance Officer

Write a formal letter covering every field in the supplied regulator form. Cite input file names and show your reasoning.

## Draft

April 16, 2027

State Board of Pharmacy<br>
Recall Duty Officer<br>
400 Civic Plaza<br>
Northbridge, Ohio 44000

**Re: Recall submission — ClearBreath Cough Syrup, batch 4471**

Dear Recall Duty Officer:

CareWell Pharmacy, 180 Meridian Avenue, Northbridge, Ohio 44000, submits this recall notice for ClearBreath Cough Syrup. The responsible contact is Lena Ortiz, Quality Manager, `quality@carewell.example`.

The product is ClearBreath Cough Syrup, an oral liquid in 120 mL bottles, manufactured by Cedar Health Products, 45 Industry Road, Northbridge, Ohio 44000. The recalled batch is 4471, expiring February 28, 2029. It was manufactured February 8, 2027, bottled February 9, 2027, shipped February 15, 2027, and reported to CareWell quality management on April 16, 2027, at 9:00 AM Eastern.

Retained samples from batch 4471 contained an unintended microbial contaminant and failed the release specification. Exposure may cause nausea, vomiting, diarrhea, or fever; children under 12 are at higher risk.

CareWell received 1,200 bottles of batch 4471. At report time, 311 bottles were held at the warehouse and 889 had been distributed to stores. Store stock control reported 216 bottles on shelves or in back rooms. CareWell will immediately quarantine remaining stock and log all returns. Store teams will quarantine returned goods for collection by the quality team and will not resell recalled goods.

The affected distribution locations are listed below. S01–S04 and S06–S12 are operating CareWell stores that received the recalled batch. S13 is included because it received and sold the affected batch, but it closed March 31, 2027; its remaining stock was sent to the central warehouse. The supplied directory does not provide a direct telephone number for S13. Its historical records contact is CareWell HQ Records, 1-800-555-0150, `records@carewell.example`. S05 is an operating CareWell store but is not listed because its sales record is for unaffected batch 4470.

| Store | Address | Phone |
| --- | --- | --- |
| S01 — CareWell Central | 112 Oak Street, Northbridge, Ohio 44000 | 216-555-0101 |
| S02 — CareWell Oak Square | 124 River Road, Northbridge, Ohio 44000 | 216-555-0102 |
| S03 — CareWell Riverside | 136 West Avenue, Northbridge, Ohio 44000 | 216-555-0103 |
| S04 — CareWell Westgate | 148 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0104 |
| S06 — CareWell Hillcrest | 172 River Road, Northbridge, Ohio 44000 | 216-555-0106 |
| S07 — CareWell South Market | 184 West Avenue, Northbridge, Ohio 44000 | 216-555-0107 |
| S08 — CareWell Lakeview | 196 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0108 |
| S09 — CareWell Maple Plaza | 208 Oak Street, Northbridge, Ohio 44000 | 216-555-0109 |
| S10 — CareWell East Point | 220 River Road, Northbridge, Ohio 44000 | 216-555-0110 |
| S11 — CareWell Garden Center | 232 West Avenue, Northbridge, Ohio 44000 | 216-555-0111 |
| S12 — CareWell North Commons | 244 Meridian Avenue, Northbridge, Ohio 44000 | 216-555-0112 |
| S13 — Harbor Annex (closed March 31, 2027) | 13 Harbor Lane, Northbridge, Ohio 44000 | No direct store phone supplied; historical records: 1-800-555-0150 |

Sales records cover February 16 through April 15, 2027, for the affected batch. The shipment and inventory records support 673 bottles sold or otherwise no longer in store inventory (889 distributed less 216 on hand). The transaction rows explicitly labelled batch 4471 total 609 bottles. S08 records 64 units as batch 4417; however, S08 received 75 bottles of 4471 and had 11 on hand, which reconciles to 64 bottles. The batch report identifies 4471 as the batch supplied to S08 and states that no other ClearBreath batches besides 4470 and 4471 were supplied during January–April. Accordingly, the 64-unit S08 correction is a likely batch-record discrepancy used for reconciliation only; CareWell must confirm the source record before representing those 64 units as confirmed batch-4471 sales. S05's 81 units are not included: they are recorded as batch 4470, which passed testing and is outside this recall. S13 historical sales run February 19 through March 31, 2027, its closure date.

Customers should stop using the product, keep the bottle away from children, and return it to any operating CareWell store for a full refund. They should bring the bottle if available; a receipt is not required. Refunds will be returned to the original payment method where possible, or paid in cash otherwise. Anyone who feels unwell after taking the product should contact a healthcare professional promptly; severe symptoms require urgent medical help.

The recall hotline is 1-800-555-0199, staffed daily from 8:00 AM to 8:00 PM Eastern beginning April 16, 2027. Operating stores will keep a printed copy of the recall notice at the counter. No additional customer communication channel or communication schedule is specified in the supplied records; CareWell will confirm any such details before submission. The first status update is due April 19, 2027, at noon Eastern.

Sincerely,

Sergio Beltran<br>
Compliance Officer<br>
CareWell Pharmacy

## Evidence

- `inputs/regulator_form.md`: addressee, Board address, and all required letter fields.
- `inputs/batch_report.md`: reporting company and responsible contact; manufacturer; product, form, package size, batch, expiration, dates, finding, health risk, distribution, inventory, customer directions, recall hotline, and status-update deadline.
- `inputs/store_list.csv`: names, addresses, and phone numbers for operating stores S01–S12.
- `inputs/sales_records.csv`: per-store batch and date-span records, including S05 batch 4470 and S08's batch-4417 discrepancy.
- `inputs/company_policy.md`: full-refund process, return logging, quarantine/no-resale instructions, counter notice requirement, S13 closure and address, stock transfer, and historical-records contact.

### Reconciliation

- The batch report's store shipment total is 889 and its on-hand total is 216; `889 - 216 = 673` bottles sold or otherwise no longer in store inventory.
- The rows labelled 4471 in `inputs/sales_records.csv` total 609 bottles. S08 is listed there as 64 units of batch 4417, yet the batch report shows that S08 received 75 bottles of batch 4471 and held 11, also producing 64 units. The batch report states that only batches 4470 and 4471 were supplied in January–April. This supports a likely S08 data-entry error for reconciliation, but does not independently confirm the 64 units as batch-4471 sales.
- S05's 81 units are excluded because its sales record names batch 4470, and the batch report says 4470 passed testing and is outside the recall.
- The batch report's 12 operating store shipments plus S13 total 889. S13 cannot serve as a return location because company policy says it ceased trading on March 31.

## Handoff

The formal regulator letter covers every field in `inputs/regulator_form.md`, identifies affected locations, and records the S08 sales-batch discrepancy with its reconciliation. The 673 figure is the shipment/inventory outflow (`889 - 216`); the confirmed transaction rows labelled 4471 total 609. Do not present S08's additional 64 units as confirmed batch-4471 sales until the source record is checked. Use the recall hotline (1-800-555-0199), not the general customer-service hotline in company policy.

Before actual external submission, confirm whether there are customer communication channels or a schedule beyond the printed counter notice; the supplied inputs do not specify them. S13 has no direct telephone number in the inputs, so the letter provides the supplied historical-records contact instead.
