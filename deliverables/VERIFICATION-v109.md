# v109 change and verification record

Implementation started from the inspected and verified v108 ZIP. Original uploads remain unchanged. The mold and private fixtures are test inputs, not organizational performance; no workbooks, screenshots, sample records or source-filled reports ship in the ZIP. The operational screenshot workbook was not supplied.

## Changes and evidence

| Issue | Before | v109 |
|---|---|---|
| Source footer on short pages | At 1906×1057, search footer ended at 644px, leaving 413px below | Minimum-viewport-height page; footer is the final element after content/copyright. It stays at the bottom without covering content |
| Project overdue wording | تجاوز موعد الانتهاء and other derived variations | متأخر across project overview, tables, timeline/drill headings, PMO and report |
| Legislation explanation | أُنجز بعد أحد المواعيد المسجّلة في الملف | تجاوز الموعد: تشريعات أُنجزت بعد الموعد المحدد للإنجاز. Source-date details remain in the tooltip |
| Follow-up owner column | المسؤول occupied summary-table space | Removed from screen/print summary; notes gain width. Source fields and full detail remain intact |

The source footer is screen-only; monthly printed filename/calculation metadata remains omitted. Header reporting cutoff and organization/copyright footer remain. The app still opens locally after extraction.

## Source-to-report reconciliation

Project **متأخر** remains the existing open-project date test; it is not a rewritten source status or a merged category. Month-only end dates keep their original selected-year and month-end interpretation. Explicit full dates retain their source year. The portfolio overdue population remains an overlapping exception, not another status count to add to the total.

Legislation **تجاوز الموعد** remains source KPI=في الموعد plus recorded actual completion later than any available SLC, extension or department deadline. **متأخر** remains its separate unfinished population without an actual completion date. The new explanation does not change the source rule or introduce an institutional policy.

All 637 private mold records, exact identifiers, typed fields, original references, full notes and owner cells remain intact. Monthly summary/drill/print scope stays consistent. Owner removal is presentation-only; CSV/source/search/details retain it. KPI measurement-state behavior, zero/missing distinction, filters and snapshot identity rules remain unchanged. No Excel formulas are recalculated.

## Verification

| Check | Result | Evidence / practical limit |
|---|---|---|
| Short/long screen footer | Passed | Actual desktop/mobile/short layouts and reduced viewport widths equivalent to 200% zoom; source footer at viewport/document bottom, final DOM child, full filename/date, no overlay or horizontal overflow |
| Project labels and dates | Passed | Explicit private past full-date scenario yields one overdue record; heading متأخر and exact drill population. Original month-only date behavior retained |
| Monthly follow-up summary | Passed | Five columns, all 8 rows/full notes; detail retains owner; table fits desktop/mobile |
| Source/calculation/CSV regression | Passed | Source, derived calculations, monthly/KPI/portfolio/follow-up data and actual CSV agree with frozen v108 in three runs (original cutoff, selected September cutoff and January), covering two distinct effective dates |
| Actual generated PDF | Passed | Exact monthly A4 2 pages/A3 1 landscape page; all 8 rows/5 columns/full notes; clear note, RTL, no clipping, no metadata/logo. Portfolio 7 pages and overdue detail 1 page visually inspected; labels/full content retained |
| Frozen ZIP / clean extraction / startup | Passed | All 116 archive files match clean extraction; all 115 manifest hashes pass; no test/source outputs shipped. Empty startup, import, reload and malformed rejection preserve notes/settings |
| Bundle/syntax | Passed | 45 CSS/45 JS source bundle inputs and 49 JavaScript syntax checks |
| Native Windows file opening | Not run | Managed browser blocks file:// before app execution |
| Interactive Microsoft Office, physical print/device keyboard, full screen-reader certification, Power Query refresh | Not run | Unavailable coverage; not inferred from browser/PDF checks |
| Operational screenshot workbook | Not run | Not attached; unchanged mold used privately for QA |

Independent QA tested the exact frozen package and its actual output pages. All affected checks passed; no unresolved implementation failure was found within the tested scope.

No native PPTX generator/template changed in v109; v108 native structure/content/render evidence is retained rather than described as a new v109 sweep. This is not unconditional operational readiness.

The earlier portfolio-combination and sector-mapping decisions remain unresolved; the existing Projects population and imported hierarchy are retained. Absent actual-completion/financial/approval/required-decision fields remain unavailable rather than invented.

ZIP SHA-256: `e02920177e4a8155a7f7bd2c18e0acf9bc505f8a2ac2bf77609777d7d83f78e6`.

Size: 7,797,443 bytes; 116 files including manifest. All 115 manifest hashes verified. Original ZIP/workbook hashes remain unchanged.
