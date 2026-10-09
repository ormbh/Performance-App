# v111 footer and monthly-card layout

This release starts from verified v110 and retains its six-sector/23-unit filter reference, bounded aliases and exact source-token scope. The new user screenshots show v109; they guide layout and wording, not replacement source data. The operational screenshot workbook remains unavailable. Original uploads and all source records remain unchanged; no sample workbooks or source-filled outputs ship.

## Changes

| Area | Before | v111 |
|---|---|---|
| App footer | Copyright on upload/monthly only, with different wording; a second standalone monthly footer | One shared footer throughout upload, error, search, filters, reports and other routes: الأمانة العامة للمجلس التنفيذي لإمارة دبي حقوق النشر © 2026 · جميع الحقوق محفوظة |
| Printed footer | Monthly wording differed; agenda/council suppressed center text; entity report used center for page number | Browser-printed pages repeat the shared phrase, including covers; existing numbering retained. Source filename/calculation metadata remains screen-only |
| Legislation note | “الموعد المحدد” did not identify a field | تجاوز الموعد: تاريخ الإنجاز الفعلي بعد أحد مواعيد SLC أو التمديد أو إدارة التشريعات. Tooltip explains the any-deadline source rule |
| Council card | Follow-up population note above metrics; unapproved status below | Population text at physical bottom-left, on the same row as unapproved status at right when present, on screen and paper |
| Quarterly distribution | Four quarters within one shaded band | Separate bordered quarter boxes; RTL Q1→Q4, two columns on narrow screens. Out-of-year/undated projects remain separately visible, including print |

The screen footer stays at the viewport bottom on short pages and follows all content on long pages. It includes source metadata when a workbook is loaded and never overlays content. The copyright year is the requested legal release year, **2026**, separate from calculation/reporting years. Printed monthly pages retain the reporting cutoff in the header and no logo.

The first implementation pushed the monthly overview to three pages. Card padding and gaps were reduced without shrinking text or removing content. The initial failed checks and corrections are recorded privately; revised pagination passed at two A4 pages or one A3 page.

## Which legislation date?

The original mold's `Legislations` table compares **K — تاريخ الانجاز الفعلي** independently against **H — تاريخ الإنجاز وفق (SLC)**, **I — تمديد حتى**, and **J — التاريخ المحدد من إدارة التشريعات**. A record classified **في الموعد** counts as **تجاوز الموعد** when its numeric actual-completion date is later than **any one** of those available dates. Whole days are compared; same-day completion does not qualify. The selected calculation date is not the completed-overrun comparison date.

An extension does **not** replace earlier dates in this supplied formula. Completion before an extension can therefore count when it is after an earlier SLC or department deadline. Cached flags and independent source comparisons both reconcile to **80** mold records. This is evidence about the test mold, not actual organizational performance or an invented institutional rule. Record-level examples remain in private audit evidence.

The presentation now states this basis. Changing the indicator to an extension-only or latest-approved-deadline test remains a business-definition decision; it was not silently changed.

## Reconciliation and verification

All 637 original test-mold records, identifiers, complete notes, source classifications, numeric values and selected-date behavior remain intact. Source/calculation/CSV regression against frozen v110 passed on the frozen implementation for the original mold and organizational-variant fixture at **30/09/2026 and 01/01/2027**. Import, rules, filter identity/reference and native PowerPoint generators are unchanged.

| Check | Result | Evidence / limit |
|---|---|---|
| Universal footer and monthly card layout | Passed | 84 focused browser checks over 11 routes at 1440/720/390px: one footer, exact wording, short/long placement, metadata, physical council positions, quarter borders/RTL and empty-scope recovery |
| Source/calculation/CSV regression | Passed | 30 frozen-runtime comparisons, original 637 records and broad alias fixture, two distinct effective dates; source, derived metrics/KPIs, follow-up notes and portfolio finance unchanged |
| Revised actual monthly A4/A3 PDF | Passed | A4 two pages / A3 one page; both A4 pages and full A3 visually inspected. Full notes, quarter boxes, council alignment, deadline note, repeated legal footer and no printed source metadata/logo |
| Other actual browser-report PDFs | Passed | Portfolio 7, entities 36, agenda 21, special 62, council 31, selected legislation result 1 page. Across all eight outputs: all 161 page footers checked by text/bounds and visually inspected as strips; representative generic first/last pages reviewed, numbering retained. All 161 fresh frozen-runtime pages match reviewed output by text/pixels; 328 PDF checks pass |
| Quarter/navigation/date journey | Passed | Six actual-browser checks; quarter drills retain scope, same-day/any-deadline source behavior and selected-date distinction preserved. 56 canonical compound/partial/reload filter checks pass |
| Frozen ZIP / clean extraction / startup / import / recovery | Passed | Final SHA/CRC/all 117 archive files and 116 manifest hashes checked independently; empty startup, local assets, original-mold import and malformed-file/reload preservation of records/notes/settings pass. No source-filled test outputs ship |
| Native PowerPoint | Inherited / unchanged | No native generator/template changes. Actual scoped native structure/content/render evidence remains in v110; no new interactive editing claim |
| Native Windows opening | Not run | Managed browser blocks file:// before HTML executes; local HTTP execution does not establish Windows behavior |
| Interactive Microsoft Office, physical printing/device keyboard, full screen-reader certification, Power Query refresh | Not run | Unavailable coverage; not inferred from browser/PDF tests |
| Operational screenshot workbook | Not run | Not supplied; original mold and private fixtures used |

Independent QA tested the frozen implementation and actual generated outputs. The final ZIP adds only a README clarification of the KPI eligibility condition and its manifest hash; every runtime/export asset is byte-identical to the tested package. Final integrity, startup and import were freshly checked after this documentation revision. No material implementation failures remain within the tested scope; this is not an unconditional production-readiness or accessibility certification.

Earlier unresolved portfolio population/three-sector mapping decisions remain unchanged. Missing actual-completion/financial/approval/required-decision fields remain unavailable rather than invented.

ZIP SHA-256: `581296007bff1a6ecc033c13ff5ec72184d3c537c8903fafa1ee3acc59f3e8fe`.

Size: 7,805,824 bytes; 117 files including manifest, 116 manifest entries. Original ZIP/workbook hashes remain unchanged.
