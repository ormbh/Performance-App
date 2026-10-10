# Performance App v116 verification

This release implements approved Concept B for **مستجدات محفظة المشاريع**. It uses monthly-report cards, native horizontal charts and visible readings. Extract the complete ZIP and open `index.html`; all assets remain local.

## Before and after

| Before | Approved B |
| --- | --- |
| Separate sector and department distributions repeated the same population | One hierarchy: each sector contains its actual department rows; direct standalone units appear once |
| Priority and type were separate summaries | One type-to-priority hierarchy using actual record intersections, with counts and budgets together |
| Managers appeared as a general distribution | Open-work bars beside overdue and next-30-day readings; total, completed, progress and budget remain visible |
| Tables carried most comparisons | Chart rows also serve as visible comparison tables; Count/Budget changes only the bar scale |
| Drill return could lose the originating keyboard position | Native chart buttons open exact contributors and return focus to the matching reading |

All financial readings, complete notes, scope, date rules and historical matching remain tied to the imported source. There are no new RAG thresholds or invented performance figures.

## Source-to-report reconciliation

| Source / rule | Portfolio output |
| --- | --- |
| Named Projects rows under the existing mold eligibility rule | Selected totals; unnamed rows remain loaded and identified by a completeness notice |
| Sector and organizational unit | Disjoint parent groups with actual contained department rows; child rows are included in their parent, not additional projects |
| Revised budget | Approved-budget readings and chart scale; valid numeric contributors, coverage and exact contributor drill |
| Status | Six exact mold statuses plus unresolved state; seven mutually exclusive populations |
| Completed status divided by all selected named projects | Completion rate; distinct from the numeric progress mean |
| Numeric progress from 0 to 100 | Unweighted mean, retaining genuine numeric zero and excluding missing/invalid values |
| Original/revised budget, allocated/unallocated, work completed and actual invoices | Six separate source totals; no invented balance and no spending-as-achievement interpretation |
| Positive revised budget and nonnegative invoices on the same projects | Paired spending ratio and its eligible population |
| Project manager | Source order and unrecorded-manager category; assigned and open-work readings, not a capacity or competence ranking |
| Open status, planned month-end and selected calculation cutoff | Overdue, dated-open and next-30-day manager subsets; disjoint future date windows in the delivery area |
| Project type and priority on the same row | Actual type × priority intersections; their totals and valid budgets reconcile to their type parent |
| Planned end date and selected cutoff | Source month-end rule, report-year quarters and open-project date windows; overdue overlaps open status counts |
| Owner/finance remarks, date delays and data gaps | Full visible issues table, full issue drill and source-consistent print |
| Confirmed snapshots and `# + project name + sector` | Exact typed matching under the same filters; duplicate/incomplete keys quarantine comparisons |

Missing history remains unavailable. Unchanged comparisons stay blank. Partial financial/progress coverage withholds change arrows; date-derived changes require aligned calculation dates and quarters require the same year. Displayed zero is `-`, while unavailable is `—`; the numeric distinction and accessible labels remain intact. Signed monetary chart scales preserve negative values and label their zero baseline. Counts and budgets remain visible in both display modes.

## Verification status

| Check | Result |
| --- | --- |
| Independent workbook arithmetic, hierarchy membership, joint intersections and financial/progress coverage | Passed |
| Existing status predicates, date windows, exact identities, duplicate/incomplete quarantine and historical guards | Passed |
| Actual imports, renamed sheets, missing fields and malformed-file recovery | Passed |
| Shared searchable multi-select union/intersection, reset, reload and selected calculation dates | Passed |
| Count/Budget scale controls, signed/zero/missing values and exact contributor drills | Passed |
| Keyboard activation/return, native manager row-header associations and responsive RTL | Passed |
| Generated populated/empty portfolio and monthly regression PDFs | Passed; every generated page visually inspected, full notes retained |
| Paired, compound-filtered and complete long-note issue PDFs | Passed; repeated headers, readable readings and natural note continuation |
| Exact ZIP CRC/SHA, all 116 manifest hashes and clean extraction | Passed; 117 files, no private fixtures or source workbooks |
| Extracted-package startup, notes/settings retention, imports, selected scope and manager controls | Passed |
| Regenerated exact-package filtered PDF | Passed; all seven pages visually inspected, full owner/finance note endings retained |
| Native file opening | Not run; Chromium returned ERR_BLOCKED_BY_ADMINISTRATOR |
| Physical printing, native browser zoom and full assistive-technology certification | Not run; narrow-viewport reflow and keyboard checks are not certification |
| PowerPoint exports/native Office editing, Excel recalculation/Power Query refresh and real organizational monthly history | Not run |

Review reproduced and corrected page splits between due labels and values, a detached financial explanation, orphan guidance and manager names/readings separating across pages. Managers now use one native physical row with all their readings; standard table-header associations apply. Long issue notes retain automatic pagination, avoiding large gaps from forcing a whole note row onto a new page. Print omits screen-only mode/reset controls and focus outlines. No material failure remained in the approved B scope after affected checks were rerun.

Test counts document particular checks, not usability certification. Original uploads remain unchanged. Source-filled screenshots, PDFs and private fixture evidence remain private.

## Limits and outstanding decisions

Native double-click startup is **not run** because the managed browser policy blocks file URLs. Actual browser checks use local HTTP. Physical printing, full assistive-technology certification, native Office editing, PowerPoint exports and Excel/Power Query refresh are **not run** in this release. PowerPoint assets remain unchanged.

Test/reference molds and clearly fictional private dated fixtures support verification; their records and reports are not organizational performance and are not packaged or published. Latest supplied v2 project titles, managers and finance fields remain blank; those values are not invented. No real organizational monthly history was provided. Source completeness, blank-title eligibility and existing Data Notes counting/validation decisions remain under review. This is not an unconditional production-readiness verdict.

No imported data, source workbooks, private fixtures, source-filled screenshots or audit reports ship with the app. Unchanged native report templates retain their empty structural chart workbooks.


ZIP: `Performance-App-v116.zip` (7,833,187 bytes; 117 files, 116 manifested hashes).

SHA-256: `832765724b3f62771e62a0d7284b1df2ba47166e8f33f5fad108447a755daf78`.
