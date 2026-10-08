# v107 change and verification record

The supplied ZIP/workbook were preserved. The Excel mold is private test input,
not organizational performance. No workbook, illustrative records, screenshots,
source-filled PDF or PPTX examples are included in the app ZIP. The operational
workbook shown in screenshots was not supplied and was not validated.

## Changes and evidence

| Issue | Before | v107 |
|---|---|---|
| Monthly printed footer | Filename/calculation-date metadata occupied footer | Organization/copyright only; selected cutoff remains in header and screen provenance remains in footer |
| عرض جميع البنود | Depended on opening a new tab; popup blocking prevented navigation | Filtered follow-up results open in the same tab, preserving scope and records |
| Council report metadata | Generic/legacy defaults and an overreaching old-string migration | مستجدات قرارات المجالس plus selected year; حتى تاريخ plus selected cutoff; explicit custom overrides remain until reset |
| Projects overview | Individual-project and PMO layout | One portfolio-delivery overview, visible sector/unit comparisons and due-date breakdown, finance coverage, validated snapshot movement and exception totals; totals open details |
| New portfolio print pagination | Orphan explanation, then header-only page ends found during review | Connected headings/rows/definitions; long tables repeat their headers; all content retained |

The existing search, multi-select union/intersection, single filter-options
scrollbar, visible tables, aligned strategy typography, executive-right/projects-left
monthly order, source footer on screen and direct print/settings workflow remain.

## Source-to-report reconciliation

| Source / field | Rule and report scope |
|---|---|
| Named Projects table, project number and classification | Existing strategic-budget population retained; all selected rows contribute to group totals. Parent organization is context, standalone units are separate rows; blank/unresolved classifications remain |
| Status | Completed divided by all selected projects, including not-started/suspended/cancelled/transferred. Raw status categories retained; overdue overlaps open statuses and is not added to them |
| Planned end and selected calculation date | Existing month-end interpretation retained. Open-project horizon windows 1–30,31–60,61–90 days are disjoint. Current-month planned dates are an independent view |
| Original/approved budgets, allocation, unallocated and invoice expenditure | Source labels, sums and per-field coverage retained. Utilization uses a paired positive-budget/nonnegative-expenditure population; expenditure is not achievement. Values above paired budget are preserved and flagged for source review |
| Previous/current workbooks and exact project identity | Two confirmed distinct dated snapshots required. Scope entry is not a new project. Missing/ambiguous/duplicate identities quarantine movement; no invented third trend point or missing-history zero |
| Monthly follow-up notes / council source content | Current selected scope retained in browser/print/export. Full source notes and council records remain present |
| Actual completion, available balance, approval record and required decision | Absent or undefined in supplied mold; relevant measures remain unavailable with the source reason. Observed revisions are not approvals |

The retained import contract binds named tables before supported sheet/header
fallbacks; renaming a valid table's sheet does not require a hardcoded filename.
Typed cells, cached formula results, original row references and full notes remain
available. Excel formulas/Power Query are not recalculated by the app.

| Named source table | Test rows retained | Reporting use |
|---|---:|---|
| ECSAC |118|Annual agenda totals, status drilldowns and agenda reports; approved/emerging classes retained|
| Resolutions |136|All council records retained; follow-up eligibility70 and excluded66 remain distinct and searchable; council report retains both|
| Legislations |192|Legislation totals, source completion/due rules and reports|
| Special |55|Existing special-project portfolio indicators; not silently combined with strategic-budget delivery|
| Projects |84|Strategic-budget monthly cards and portfolio delivery described above|
| Strategy |52|Source KPI definitions/denominators retained; genuine measured zero needs explicit state; result and target means use their separate populations|

Source totals and screen/drill/print populations are reconciled under the same
selected scope. The source-to-model contract and earlier unchanged-loader tests
are reused; v107 is not a new visual sweep of every unchanged detailed-report page.

Independent raw-workbook reconciliation uses 84 test Projects rows:10 completed;
five source sectors77 plus three standalone units7; all16 blank departments
retained. Finance sums and coverage match, including genuine numeric zeros versus
missing values. The broader imported source population remains637 rows. These
are test acceptance counts, not executive performance claims.

## Outstanding decisions

1. Whether the delivery page should combine Projects with Special or preserve the
   existing strategic-budget Projects population. Different data/finance grain
   prevents a silent union; this release preserves the existing population.
2. An agreed mapping from the mold's five sector labels to the illustrative
   reference's three sectors. This release preserves imported hierarchy and does
   not invent organizational classifications or placeholder unit names.

Source fields/definitions are needed to populate on-time completion, a defined
available balance, approved changes and required decisions. A proposed field
schema is a recommendation, not completed source integration.

## Verification

| Check | Result | Practical evidence |
|---|---|---|
| Exact ZIP, clean extraction and manifest | Passed | CRC clean; all115 extracted files byte-match ZIP; all114 manifest entries match; no source/test-report files shipped |
| Empty startup/local assets | Passed | Build107, empty upload screen, no page errors, fonts/bundles/images loaded |
| Import/error recovery | Passed | Mold import637 records; malformed import preserves existing data |
| Follow-up navigation | Passed | Popup-blocked same-tab click, scope retained, reload recovery and complete records |
| Portfolio data and journeys | Passed | Independent raw source oracle, status/group/finance coverage, dates/zero/missing, visible tables and exact drills; actual desktop/mobile screenshots reviewed |
| Compound filters and reset | Passed | Two-sector union33, completed intersection3, Arabic searched unit intersection2, empty intersection recovery, reset84 |
| Historical identity | Passed | Confirmed exact snapshots, missing history unavailable, duplicate quarantine, scoped entry not counted as added, unchanged movement blank |
| Monthly PDF | Passed | Actual2pages, all8full notes, no filename/calculation footer or logo, organization/copyright visible on both pages |
| Portfolio PDF | Passed | All7actual pages visually reviewed; headings/rows/definitions together; long-table headers repeat; no clipping |
| Council metadata/native export | Passed | Actual HTML/PPTX covers match selected2026/cutoff;2027 defaults and explicit custom overrides tested.136records/60note fields retained in native text;58slides with37tables/3charts; rendered cover/dense tables/notes visually checked |
| Bundle consistency/syntax | Passed | Readable sources agree with generated local CSS/JS; JavaScript syntax passed |

Independent QA tested the implementation and the frozen package.45 focused
browser/data checks passed with0remaining failures; that count is supporting
evidence, not a usability verdict. Working print failures were corrected and
actual affected outputs rerun before package acceptance. No material implementation
defect was found within the tested scope. Original uploaded ZIP/workbook hashes
remain unchanged. Other unchanged detailed-report layouts reuse prior evidence;
a whole council body visual sweep was not repeated.

ZIP SHA-256: `d23b0112ecaf91285be4647cbb7852fe272433c527c1f1a083023bfdadf5d496`.
Size:7,790,397bytes;115files including release manifest.

Not run: native Windows double-click/file-opening (managed browser rejects
file:// before app execution), Microsoft PowerPoint interactive editing, physical
printing, real mobile-device software keyboard, full screen-reader certification
and Power Query refresh. HTTP Chromium success and editable XML structure do not
substitute for these checks. This is not unconditional operational readiness.
