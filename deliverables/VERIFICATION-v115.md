# Performance App v115 verification

This release redesigns **مستجدات محفظة المشاريع** into five reporting areas with visible source notes and delays. It removes the generic execution-overview heading. The app remains an offline HTML package: extract the complete ZIP and open `index.html`.

## Source-to-report contract

| Source / rule | Portfolio output |
| --- | --- |
| Named Projects rows under the existing mold eligibility rule | Selected project totals; unnamed rows remain loaded with a scoped completeness notice |
| Sector and organizational unit | Disjoint sectors/direct units, plus a separate breakdown of all units; two views of the same population |
| Status | Six exact mold status counts and unresolved states; completed status divided by all selected named projects |
| Numeric progress from 0 to 100 | Unweighted mean and valid-value population; zero retained, missing/invalid excluded |
| Revised budget | Approved-budget headline and each distribution's sum with numeric coverage |
| Original budget, revised budget, allocated, unallocated, work completed, actual invoices | Six separate source totals; no invented available balance or spending-as-achievement claim |
| Positive revised budget and nonnegative invoices on the same projects | Paired spending ratio with its eligible population |
| PM, priority and type | Source-based distributions; blank/unresolved values retained |
| Planned end date and selected calculation cutoff | Source month-end rule, year quarters and open-project date windows; overdue overlaps open status counts |
| Owner and finance remarks, date delays and data gaps | Complete visible notes/issues table and complete issues drill/print |
| Confirmed previous/current snapshots and `# + project name + sector` | Exact typed matches, same filters in both periods, genuine arrows; duplicate/incomplete keys withhold comparisons |

Missing history is unavailable. Unchanged indicators are blank. Partial financial/progress coverage withholds change arrows; date-derived changes require the calculation dates to match the confirmed periods, and quarters must refer to the same year. Displayed zero is an ASCII dash; numeric zero remains distinct from unavailable data.

## Verification status

| Check | Result |
| --- | --- |
| Independent source arithmetic, denominators, financial coverage and quarter populations | Passed |
| Exact identities, duplicate/incomplete quarantine, renamed sheets and dated comparison cases | Passed |
| Missing status/date headers; source-status equality and existing date eligibility | Passed |
| Actual imports, manager search, union/intersection filters, reload/reset and drill recovery | Passed |
| Keyboard focus, responsive RTL, visible tables and one-scroll filter menus | Passed |
| Malformed-file recovery, invalid monetary types and preserved source content | Passed |
| Actual portfolio, filtered, issues-drill, record-detail and monthly PDF pages | Passed; full notes, repeated headers and no observed clipping |
| Frozen ZIP CRC, manifest, clean extraction, startup and preserved settings | Passed; exact package also passed 107 targeted checks and all 9 regenerated PDF pages |
| Native double-click file startup | Not run; managed browser policy blocked file URLs |
| Physical printing, full assistive-technology certification and native Office interactive editing | Not run |
| Excel recalculation/Power Query refresh and real organizational monthly history | Not run |

Working-output defects found during review were fixed and their affected checks rerun: source-status normalization differed from the monthly mold, missing headers could imply zero, short print cards wasted space, an explanation orphaned onto its own page, and the issues drill omitted source notes/reasons. Complete source content now remains visible in that drill and print output.

Long reports may span multiple pages; text is not hidden to force a page count. Test/reference molds and clearly fictional private fixtures support the checks; they are not organizational performance and are not included in the app. Source-filled evidence remains private.

Existing Data Notes counting/validation review decisions and the blank-title eligibility definition remain pending. Missing titles, managers, measurements and budgets are not invented. These limits prevent an unconditional production-readiness claim.

ZIP: `Performance-App-v115.zip` (7,817,930 bytes; 117 files, 116 manifested hashes).

SHA-256: `8f9109929ab79cbe8b9f8be130ba943be0950ef0e15e88ead742e50b4710df6c`.
