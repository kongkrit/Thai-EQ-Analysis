# Portfolio Research — Source Documents (Jun 2026 valuation set)

Private archive of the source documents behind the PTT / TLI / ADVANC / ACWI-IMI
valuation work from June 2026 and the BH / BDMS / BCH / PR9 / CHG hospital analyses of
September 2026: exchange factsheets, company filings, index factsheets,
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
- **BDMS / BCH / PR9 / CHG — hospital peers, pulled 28-Sep-2026** (`data/BDMS/`, `data/BCH/`,
  `data/PR9/`, `data/CHG/`), same layout as `data/BH/`: One Report 2025; FY2025 audited and
  1Q26/2Q26 reviewed statements (BDMS and CHG as PDF; **BCH and PR9 publish only the SET e-filing
  set — statements .xlsx/.xls, notes and auditor report .docx**); MD&As for FY25, 1Q26, 2Q26 (plus
  3Q25/2Q25 where available); analyst-meeting / Opportunity Day decks; dividend resolutions and
  interim notices (source split for the tax credit where stated); AGM 2026 papers; IR pages saved
  as .htm (shareholders, dividends, highlights, structure); `<TICKER>_market_snapshot_20260925.md`
  (SET factsheet, stockanalysis, multiple history; the saved SET .htm is the JS shell). BDMS also
  has the TRIS rating report (Nov-2025), the WellEra budget notice (Jun-2026) and the IR
  operational-figures workbook; BCH the JUMP+ plan deck and the Rajavej Ubon acquisition notices;
  CHG the F45 summaries and the revised dividend resolution. Analyses:
  `bdms_ / bch_ / pr9_ / chg_fundamental_analysis_2026-09.md` (each with a gross-up section);
  BH note revisited the same day (Jun-26 receivables ageing); peer summary and seven-name
  gross-up ranking appended to `thai_equity_valuations.md`.
- **Browser-saved SET pages, 28-Sep-2026** (`data/<TICKER>/<TICKER> - Factsheet.mhtml`,
  `... - Rights and benefits.mhtml`, `... - Company highlight.mhtml`): rendered SET factsheet
  (25-Sep close), dividend/XD history with operating period and "source of dividend" text (no
  tax-rate split — that is only in the per-announcement attachment), and SET's five-year
  financial table. BCH company-highlight not yet saved. Also `data/<TICKER>/<TICKER>.BK.csv/.json`
  (daily OHLCV, adjusted close and dividends from listing to Sep-2026, with `-remarks.txt` data
  flags), `data/BH/BH-Earnings call transcript_Q2 2026.mhtml` (Investing.com machine transcript
  of the 20-Aug-2026 call), `data/sso-go-th-ceiling-increase.mhtml` (SSO contribution-ceiling
  notice, Jan-2026), `data/BCH/BCH-20260911-dividends.pdf` (FY26 interim SET summary form).
- **SET-filed annual-report archives** (`data/<TICKER>/<TICKER>-<year>.zip`, 2021–2025 for BDMS,
  BCH, PR9; 2024–2025 for CHG): the 56-1 One Report as filed on SET (`ONEREPORT*.PDF` /
  `E_ONE_REPORT*.PDF`, longer than the IR-site versions archived as `*-one-report-2025-en.pdf`)
  plus the group-structure attachment (`STRUCTURE*.PDF`). `data/BCH/BCH-Q1-2026.zip` and
  `BCH-Q2-2026.zip` are the SET e-filing sets (identical to the archived `bch-fs-*` files; the
  loose `BCH-Q2-2026-*` files are a different build of the same filing, kept for comparison).
  None of these carry the dividend tax-source split.
- **`data/SET/`** (SET downloads, 28-Sep-2026): `set-tri-download.xlsx` (SET TRI, SET50/100 TRI,
  sSET TRI, SETCLMV TRI, daily 27-Sep-2021 to 25-Sep-2026) and `set-download.xlsx` (SET and mai
  industry-group indices, same dates; the Services group is the hospitals' industry — there is
  no sector-level HELTH series in it). `set-helth.json` / `set-helth.csv` (SET Health Care Services sector index HELTH, daily
  closes with volume and value, same dates; the .csv is converted from the SET JSON —
  its Change columns are relative to the series' opening reference, not day-on-day). Used for
  market- and sector-relative returns and weekly betas.
- **`data/SSO/`**: Social Security Office material (contribution-ceiling notice, Jan-2026). The
  2023 medical-committee declaration (capitation ฿1,808 from 1-May-2023, ฿453 chronic add-on, the
  26-disease list) and any 2026 rate notification belong here when saved.
- `data/search_pr9-alkoot_bdms-wellera_20260928.mhtml`: Google AI-mode search page on PR9's Al
  Koot MOU and BDMS WellEra pre-sales (secondary; press-level, no contract term disclosed).
- **Dividend-source history pulled 28-Sep-2026 (evening):** BDMS notice-of-dividend letters
  FY22–FY26 (`data/BDMS/bdms-dividend-notice-2023*..2025*.pdf`, from
  investor.bdms.co.th/en/shareholder/dividend-payment-announcement); CHG AGM resolution reports
  2023–2025 and interim notices Aug-2023/Aug-2024 plus board resolutions Feb-2023/Feb-2024
  (`data/CHG/chg-agm-*-resolutions-*.pdf`, `chg-interim-dividend-notice-2023*/2024*.pdf`,
  `chg-dividend-resolution-2023*/2024*.pdf`, via investor.chularat.com set-announcements
  tracker links); BCH interim SET forms Aug-2024 (`data/BCH/bch-interim-dividend-notice-20240814.pdf`).
  PR9 Thai dividend advertisements (IR viewer ids 7–12) were read and carry no tax source; not archived.
  `data/BCH/BCH_IR_reply_dividend_tax_source_20260928.md`: BCH IR's written confirmation that the
  Sep-2024, Sep-2025 and Sep-2026 (incl. special) interims were paid from 20%-taxed profit.
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
