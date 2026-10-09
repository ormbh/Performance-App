# v108 change and verification record

The inspected and verified v107 package was the implementation baseline. The original v102 ZIP and supplied Excel mold remain unchanged. The mold and XML-preserving variant fixtures were used privately for testing; no demonstration records, workbooks, source-filled reports or screenshots ship in the app. The operational workbook shown in the user's screenshot was not supplied.

## Changes and before/after evidence

| Issue | Before | v108 |
|---|---|---|
| Duplicate-looking filters | Exact tokens differing only in invisible characters, spacing or Arabic presentation glyphs appeared as separate choices | One visible choice includes all matching exact tokens; records/identifiers are unchanged. Genuinely different source values with the same translated label remain distinguishable |
| Saved selection and filter scrolling | Grouping risked widening a saved subset; remembered one-result search left a tiny list after clearing | Saved subsets remain marked as partial until deliberately changed; searchable multi-select has one scroller and resizes after live search |
| Projects navigation | المشاريع | محفظة المشاريع, matching the portfolio destination |
| Zero metric readouts | 0 / 0% | ASCII- for exact zero; missing em dash, unchanged deltas blank; small positive values remain visible |
| Strategy card | غير مقاسة count below measured/total | Line removed; measured population and result/target averages unchanged |
| Legislation terminology | تجاوز الموعد lacked a nearby explanation | Bottom-right note: تجاوز الموعد: أُنجز بعد أحد المواعيد المسجّلة في الملف. |
| Native pie export | Two adjacent 4.8% labels collided in an actual filtered agenda render | Editable legend carries counts and percentages; native series and embedded workbook stay numeric. Legend annotations reflect export-time scope |

The filtered chart collision and two introduced grouping regressions were found during testing, corrected and rerun. Grouped select-all initially missed FEFF-prefixed source cells; raw alias collection restores all records. Changing the selected date initially reached aggregate history without its source schema; guarded lookup restores that journey. One visible agenda type with several raw aliases now selects the correct single-type report branch.

## Source-to-report reconciliation

| Source | Preserved rule / evidence |
|---|---|
| Named tables ECSAC 118, Resolutions 136, Legislations 192, Special 55, Projects 84, Strategy 52 | All 637 test records, exact identifiers, typed cells, row references and full notes remain unchanged from v107. These are acceptance populations, not government performance claims |
| Filter fields and raw Excel tokens | Presentation grouping only; exact aliases retained for existing source matching. Union within a filter and intersection between filters; blanks remain selectable. Selected scope stays consistent in screen, drill, CSV, print and native reports |
| Annual KPI result/state and target | Legacy zero remains unmeasured; genuine measured zero counts only with an explicit measurement-state field. Mold 32/52 measured and separate result/target means unchanged. Tiny genuine positive values are not masked as zero |
| Legislation actual/SLC/external/department dates | Existing rule retained: completed work after any recorded due date is beyond deadline. Explanation adds no institutional policy or new threshold |
| Zero/missing and history | Display-only change; source/CSV/numeric chart caches and workbooks retain 0. Missing history is never synthesized as 0; unchanged movement remains blank |
| Project status, grouping, planned dates and finance | Existing 84-row strategic-budget population, imported hierarchy, paired utilization population, source labels and coverage retained; expenditure is not achievement |
| Monthly follow-up and council/agenda/special reports | Full selected records and source notes retained. Monthly source filename/calculation-date footer stays removed; organization footer and selected cutoff remain |

Independent comparisons against v107 give identical hashes for complete source cells/notes, portfolio calculations, monthly counts, KPI model and actual CSV output. Source populations are preserved under the same calculation date. The shared grouping helper does not change identifier normalization or snapshot matching.

## Verification

| Check | Result | Evidence / practical limit |
|---|---|---|
| Shared filter menus | Passed | Actual 54 dropdown instances across 11 contexts; clean labels/search, one scroller, keyboard Escape/focus |
| Grouped scope behavior | Passed | Actual select-all 637/84, multi-value union, cross-filter intersection, blanks, saved partial subset/reload, chip removal, reset/empty recovery across 6 screens |
| Live-search sizing | Passed | Actual desktop/mobile remembered search → clear and zero results; larger list, viewport fit and focus retained |
| Source/calculation/CSV regression | Passed | Identical v107/v108 source and model hashes; actual CSV unchanged |
| Zero/measurement states | Passed | Genuine measured 0, legacy unmeasured 0, missing and tiny positive cases tested; source/chart/CSV values unchanged |
| Navigation/date recovery | Passed | Portfolio label/destination, popup-blocked follow-up navigation, date/custom defaults and reset |
| Monthly actual PDF | Passed | 2 pages; all 8 rows and all 6 nonblank source notes complete; no logo/source metadata footer; organization/copyright visible; note position and KPI-line removal checked |
| Native PPTX structure/content | Passed | Agenda 27 slides/118 topics/51 notes; council 58 slides/136 titles/60 notes; special 68 slides/55 titles/229 complete content fields; numeric chart caches agree with embedded workbooks |
| Native PPTX visual review | Passed | Actual LibreOffice renders/contact sheets across generated reports; final agenda/council/alias summaries and real zero-completion scope inspected. Labels, RTL, notes and numeric chart workbooks remain intact |
| Exact ZIP / clean extraction / hashes / startup | Passed | CRC clean; 116 members match clean extraction; all 115 manifest hashes valid; build 108 empty startup/local assets pass; no source/test outputs included |
| Malformed import / preserved notes and settings | Passed | Actual malformed-file rejection retains source data, notes and A3 setting; reload preserves them |
| Bundle consistency and JavaScript syntax | Passed | Frozen bundle matches 45 CSS/45 JS source inputs; 49 JavaScript files pass syntax |
| Native file opening on Windows | Not run | Managed browser blocks file:// before application execution; HTTP Chromium testing does not replace it |
| Microsoft PowerPoint interactive editing | Not run | Native editable XML/chart workbooks and LibreOffice rendering verified; interactive Office not available |
| Physical print, real-device keyboard, full screen-reader certification, Power Query refresh | Not run | Environment/tool coverage unavailable; no claim of certification or workbook recalculation |

Independent QA tested the frozen implementation and its actual outputs. Working failures were fixed and affected checks rerun; no unresolved implementation failure was found within the tested scope. Assertion counts are supporting evidence, not a usability verdict. Unchanged detailed layouts reuse earlier evidence; this is not unconditional operational readiness.

## Outstanding decisions and source limits

The earlier questions about combining Projects with Special and mapping the mold's five sectors to the illustrative three sectors remain unanswered. This release preserves the existing Projects population and imported hierarchy. Actual on-time completion, a defined available balance, approved changes and required decisions need source definitions/fields before they can be populated. Observed revisions are not approvals. No illustrative unit names or invented decisions are included.

The exact source cause of the screenshot's repeated unit cannot be certified without that workbook. The shared duplication defect is reproduced and corrected with private variants, and all available filters are verified.

ZIP SHA-256: `652082f06ee476474a5a606f235a3e66cf46d3481032b33fd0d7d70f39d6480f`.

Size: 7,797,059 bytes; 116 files including the manifest. All 115 manifest entries verified. Original v102 ZIP and mold SHA-256 values match the preserved uploads.
