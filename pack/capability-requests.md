# Capability requests

Rules this pack could not express with the capabilities in schema 0.1. Do not approximate them in rules.yaml.

## CR-1: Withholding tax on service fees with a monthly minimum and payee conditions
- **Rule:** 5% withholding tax on service fees paid to specified resident individuals when payments exceed LKR 100,000 in a calendar month. The list of covered professions was widened on 2026-06-03.
- **Legal source:** Inland Revenue Act No. 24 of 2017, s.85(1C), as amended by Act No. 11 of 2026; IRD notice SEC/PN/IT/2026/02 dated 2026-06-08; withholding circular SEC/2026/E/04 dated 2026-06-08 (not read in full by the author's assistant).
- **Who it affects:** Any business paying fees to individual professionals and contractors.
- **Worked example:** A business pays an individual consultant LKR 90,000 in a month: no deduction. It pays LKR 150,000: 5% of the full payment, LKR 7,500, withheld. (Hand computed; to be confirmed against the circular.)
- **Workaround meanwhile:** None in this pack. The engine cannot apply a monthly minimum or a payee-type condition, so a flat code would over-withhold on small payments.

## CR-2: VAT on financial services on value addition
- **Rule:** From 1 July 2026 VAT on financial services is 20.5%, charged on the value addition attributable to financial services, with an interim-estimate payment scheme.
- **Legal source:** VAT Act No. 14 of 2002 as amended by Act No. 14 of 2026; IRD notice SEC/PN/VAT/2026-03 dated 2026-07-03.
- **Who it affects:** Banks, insurers and other financial institutions.
- **Worked example:** Not yet written; needs the value-addition method from the Act.
- **Workaround meanwhile:** None; such businesses should not use this pack for VAT.

## CR-3: Payroll taxes (APIT, EPF, ETF)
- **Rule:** Employer deductions and contributions on salaries.
- **Legal source:** Inland Revenue Act No. 24 of 2017; Employees' Provident Fund Act; Employees' Trust Fund Act.
- **Who it affects:** Every employer.
- **Worked example:** Not written; payroll is outside the first-pack scope of the toolkit.
- **Workaround meanwhile:** Handled outside the pack.

## CR-4: VAT return due on the last day of the following month
- **Rule:** The VAT return is due not later than the last day of the month after the taxable period; payment is due by the 20th.
- **Legal source:** VAT Act No. 14 of 2002, s.21 as amended by Act No. 4 of 2025; IRD VAT page.
- **Who it affects:** All VAT-registered businesses.
- **Worked example:** July 2026 return: due 31 August 2026; July payment due 20 August 2026 (IRD notice dated 2026-08-13).
- **Workaround meanwhile:** The pack records the due day as 31; months with fewer days need a "last day of month" option and a separate payment date.
