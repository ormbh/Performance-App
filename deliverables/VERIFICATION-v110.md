# v110 organization filter correction

The confirmed duplication mechanism combines Excel's option lists with record values. v109 grouped spacing and invisible formatting but deliberately kept different Arabic spellings and renamed units separate. The latest user table now provides an explicit reference: six sectors and 23 units, in the supplied order.

## Changes and before/after evidence

| Legacy source value | Approved filter label |
|---|---|
| البحث والرصد | الأبحاث والرصد |
| الأرشفة | المراسلات والأرشفة |
| السياسات والاستراتيجيات الاجتماعية | السياسات والإستراتيجيات الاجتماعية |
| السياسات والاستراتيجيات الاقتصادية | السياسات والإستراتيجيات الاقتصادية |

Each of these known aliases now appears as one organizational choice, caption and chip. Selecting a group includes its exact source tokens. Search finds both legacy and approved names. The reference adds **الاتصال الداخلي** and supplies sector-dependent unit choices. Blank values remain selectable. Unlisted values carry **قيمة أخرى من الملف**; a known unit recorded under another selected source sector carries **تبعيتها مختلفة في الملف**. These are review cues, not reclassification.

The parent **الأمانة العامة للمجلس التنفيذي** remains organization context rather than a sector in the project portfolio menu, preserving the earlier approved preference. All six sectors and 23 units are available in other organizational filters when no sector is selected; unit choices narrow with sector selection. Actual unknown classifications are preserved alongside the reference.

Existing saved partial selections keep their exact scope until deliberately changed. Multi-select remains union within a field and intersection between fields. Filter search and its single scrollbar, visible tables, full notes, footer layout, zero dashes, print controls and previous report corrections are retained.

## Source-to-report reconciliation

This release starts from the inspected, verified v109 package. All 637 original mold records remain intact: ECSAC 118, resolutions 136 (70 follow-up and 66 appendix), legislation 192, special projects 55, Projects 84 and strategy 52. This is private test data, not actual organizational performance. No records, workbooks, screenshots or source-filled reports ship in the ZIP.

The original mold contains 22 Departments rows; the user supplied 23 current unit names. The four aliases apply only to organizational-unit filter presentation. Raw fields, identifiers, notes, numeric values, date rules, historical matching and source classifications are unchanged. No general fuzzy Arabic matching or sector reassignment was added. Import/rules modules and CSS are unchanged. No Excel formula recalculation or Power Query refresh is claimed.

Source, calculations, monthly/KPI/portfolio/follow-up models and actual CSV exports agree with frozen v109 for both the untouched mold and a private organizational-variant fixture. Each input was checked on the exact package at **30/09/2026 and 01/01/2027**. The working-build review additionally repeated the default September cutoff with an explicit selection; those runs represent the same effective date. Current/previous imports select the approved economic aliases as exact unions: 82 fixture records and 90 original mold records. An unapproved diacritic variant remains a separate source value.

The actual scoped monthly PDF reconciles all 39 metric/ratio/finance readings to that selected scope. Its two landscape A4 pages retain the full selected note and organization footer; filename/calculation metadata remains omitted from print. Actual scoped agenda and special-project PowerPoint exports retain their complete selected source content and canonical scope captions.

## Verification

| Check | Result | Evidence / limit |
|---|---|---|
| All filters | Passed | Exact ZIP: 54 actual dropdown instances / 119 checks; all 18 organizational menus follow supplied order. Four aliases, blanks, unknowns and distinct unrelated values checked |
| Scope and recovery | Passed | Exact ZIP: 56 behavior checks; 52 facet-count checks; 6 empty-new-unit/current-previous checks; 5 renamed/missing LOV fallback checks (23 fallback units, no unsupported sector inference). Search, union/intersection, dependent choices, partial selection, chip removal, reload and reset exercised |
| Source/calculation/CSV regression | Passed | 44 working-build comparisons and 30 exact-package comparisons against frozen v109; 637 records preserved, two distinct dates |
| Actual monthly PDF | Passed | Exact ZIP: two A4 landscape pages, 82 selected records / 39 scoped readings reconciled, full note and both visible footers; RTL/spacing/clipping visually inspected |
| Actual native PPTX | Passed | Exact ZIP: agenda 10 topics / 7 slides; special 6 projects / 12 slides, all 21 nonblank narratives. 16 native text/chart/cache/workbook checks; all 19 actual LibreOffice rendered pages inspected |
| Bundle / syntax | Passed | 45 CSS / 46 JS bundle inputs and 50 JavaScript syntax checks |
| Frozen ZIP / clean extraction / exact-package execution | Passed | All 117 archive files match clean extraction; all 116 manifest hashes and CRC pass. Empty startup, import, malformed-file preservation of records/notes/settings and actual reload pass; no test/source outputs ship |
| Malformed-file error and recovery | Passed | Four focused checks await actual error state and visible alert: تعذّر تحميل الملف — هذا الملف ليس ملف Excel بصيغة .xlsx. Recovery and reload retain all 637 records, complete note and A3 setting |
| Native Windows file opening | Not run | Managed browser blocks file:// before app execution; local HTTP browser execution does not establish native Windows behavior |
| Interactive Microsoft Office, physical printing/device keyboard, full screen-reader certification, Power Query refresh | Not run | Unavailable coverage; native object inspection and rendered output do not establish interactive Office editing |
| Operational screenshot workbook | Not run | Not supplied. Duplicate mechanism reproduced with a private fixture, not claimed as inspection of that workbook |

Independent QA tested the actual frozen package and its generated outputs. No unresolved implementation failure remains within the tested scope. Prior full-output checks remain documented in v108/v109; this is a targeted organizational-filter correction, not a new full usability certification.

The earlier portfolio-combination and three-sector mapping decisions remain unresolved. The latest filter list does not authorize combining Projects with Special or translating six sectors into three. Existing portfolio population and source hierarchy are retained; absent actual-completion, financial, approval and required-decision fields remain unavailable.

ZIP SHA-256: `eb4a29c746dbfa976362d8e3c07b2543903ed208fe09ffa1cec330c07b69d99f`.

Size: 7,803,141 bytes; 117 files including manifest, 116 manifest entries. Original ZIP/workbook remain unchanged.
