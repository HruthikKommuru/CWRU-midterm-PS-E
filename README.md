# Product Recall, 48 Hours

CareWell Pharmacy, a 12-store chain, has learned that one batch of ClearBreath Cough Syrup is contaminated. It must warn customers and the state Board of Pharmacy fast.

Prepare the full recall package, with every fact correct, within 48 hours of the report. This is a fictional classroom exercise. Prepare documents for review in this repository.

## Inputs

- inputs/batch_report.md: laboratory report and product information.
- inputs/sales_records.csv: store sales records.
- inputs/store_list.csv: store directory.
- inputs/regulator_form.md: Board reporting fields.
- inputs/company_policy.md: company service procedures.

## Roles

| Role | Your file | Job |
| --- | --- | --- |
| Quality Manager (leader) | roles/01_quality_manager/facts.md | Build the one correct list of facts: batch, stores affected, dates, risk, hotline, and customer actions. |
| Customer Service Lead | roles/02_customer_service_lead/customer_notice.md | Write a plain-language notice: what happened, what to do, and who to call. |
| Compliance Officer | roles/03_compliance_officer/regulator_letter.md | Write a formal letter covering every field in the supplied regulator form. |
| Social Media Manager | roles/04_social_media_manager/social_post.md | Write a public post under 280 characters and a longer version. |

## Rules

Hidden problems are in the inputs. Finding them is part of your score.
Use only files in inputs/. Prove your answer is right.

Work on your own role branch and edit only your role file. Leave inputs/, shared/, AGENTS.md, and other role folders alone. Follow AGENTS.md for joining and finishing. After all four roles are done, the leader builds final/ and the team reviews before merging.

## Timeline

| Minutes | Work |
| --- | --- |
| 0-10 | Read and make branches |
| 10-50 | Do your role |
| 50-60 | Merge |
| 60-80 | Leader builds final/, team reviews |
| 80-90 | Rehearse |

## Final work

The leader creates final/recall_package.md with all three messages checked against facts.md and a table showing each key fact matches everywhere. The leader also creates final/presentation_outline.md for five minutes.
