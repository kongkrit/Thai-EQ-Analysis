# Portfolio Research — Source Documents (Jun 2026 valuation set)

Private archive of the source documents behind the PTT / TLI / ADVANC / ACWI-IMI
valuation work from June 2026: exchange factsheets, company filings, index factsheets,
and supporting charts — with their as-of dates.

## Note
Private repository — some files (e.g. the Santander account/custody PDFs) contain
personal data, so keep it access-controlled. Binaries are committed directly (no Git
LFS); the two largest are `ptt-one-report-2025-en.pdf` (~68 MB) and
`advanc-ar2025-en.pdf` (~49 MB), so the repo and its history will be sizeable.

## Documents (point-in-time — each carries an as-of date; refresh before relying)

- **SET factsheets — 8-Jun-2026** (`*_-_Factsheet_-_The_Stock_Exchange_of_Thailand.htm`):
  PTT, PTTEP, OR, PTTGC, TOP, IRPC, GPSC, ADVANC, TLI.
- **Annual / One reports:** `ptt-one-report-2025-en.pdf` (segment EBITDA, group
  structure), `advanc-ar2025-en.pdf`.
- **Statutory financials / notes / auditor:** `PTT_FINANCIAL_STATEMENTS.XLSx`,
  `PTT_NOTES.DOC`, `PTT_AUDITOR_REPORT.DOC`, `PTT_Shareholders.htm`;
  `TLI_FINANCIAL_STATEMENTS.XLSX`, `TLI_NOTES.DOCX`, `TLI_AUDITOR_REPORT.DOCX`.
- **TLI embedded value:** `TLI-20260226-embedded-value-reports-en.pdf` — Milliman
  actuarial report, valuation date **31-Dec-2025** (EV, VONB, sensitivities).
- **MSCI index factsheets — 29-May-2026** (`msci-*.pdf`): ACWI IMI, USA, World ex USA
  (price + gross-return variants).
- **Yardeni forward-P/E charts — 8-Jun-2026** (`Yardeni-*.png`): US-and-ACWI,
  US-vs-ACWexUS, US-minus-ACWexUS, EM.
- **US CAPE:** `Shiller_PE_Ratio_by_Month_-_Multpl.htm`.
- **ADVANC stats:** `Advanced_Info_Service_PCL__BKK_ADVANC__Statistics___Valuation_Metrics.htm`.
- **Santander (EU banking footprint):** `america_e.pdf`,
  `Contrato_Cuenta_de_Custodia_de_Valores.pdf`, `docysadetallesdelacuentasantander.pdf`.

## Conventions
- **Dates on everything financial.** These are snapshots; nothing is a standing truth
  without an as-of date. Re-pull at each review.
- **Text vs binary.** Notes/data are diffable text (LF); documents are committed as
  binary (no LFS).
