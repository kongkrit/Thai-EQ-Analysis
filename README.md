# Portfolio Research — Source Documents (Jun 2026 valuation set)

Private archive of the source documents behind the PTT / TLI / ADVANC / ACWI-IMI
valuation work from June 2026 and the BH (Bumrungrad) analysis of September 2026: exchange factsheets, company filings, index factsheets,
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
- **BH (Bumrungrad) — pulled 28-Sep-2026** (`data/BH/`): `bh-one-report-2025-en.pdf`;
  audited FY2025 and reviewed 1Q26/2Q26 statements (`bh-fs-*-en.pdf`); MD&As for 3Q25, FY25,
  1Q26, 2Q26 (`bh-mdna-*-en.pdf`); analyst-meeting decks 4Q25/1Q26/2Q26 and the Apr-2025
  investor deck (`bh-analystmeeting-*.pdf`, `bh-investor-presn-april2025.pdf`); IR
  financial-highlights sheet (23-Mar-2026); IR pages saved as .htm (shareholders 31-Dec-2025,
  dividends, factsheet, group structure); `BH_market_snapshot_20260925.md` (SET factsheet
  numbers, peers, multiple history — the saved SET .htm is the JS shell without figures).
  Analysis: `bh_fundamental_analysis_2026-09.md` (incl. dividend gross-up comparison vs PTT/TLI;
  summary appended to `thai_equity_valuations.md`).
- **Dividend-source notices (for the Section 47 bis credit split):** `data/BH/bh-interim-dividend-notice-20260814.pdf`,
  `data/BH/bh-dividend-resolution-20260219.pdf`, `data/PTT/ptt-agm2026-and-2025-dividend-notice-20260224.pdf`,
  `data/PTT/ptt-interim-dividend-notice-20250918.pdf`, `data/PTT/ptt-interim-dividend-notice-20240815.pdf`,
  `data/TLI/tli-agm-2026-minutes-en.pdf`.
- **Santander (EU banking footprint):** `america_e.pdf`,
  `Contrato_Cuenta_de_Custodia_de_Valores.pdf`, `docysadetallesdelacuentasantander.pdf`.

## Conventions
- **Dates on everything financial.** These are snapshots; nothing is a standing truth
  without an as-of date. Re-pull at each review.
- **Text vs binary.** Notes/data are diffable text (LF); documents are committed as
  binary (no LFS).
