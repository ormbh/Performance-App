# Performance App v117 verification

This release applies the requested simplifications to **مستجدات محفظة المشاريع**. Extract the complete ZIP and open `index.html`. Assets and imported-data processing remain local.

## Before and after

| v116 | v117 |
| --- | --- |
| Separate planned-open-project deadlines panel | Removed from screen and print |
| Sector/unit completion-comparison table below the delivery summary | Removed; overall status, completion/progress and beige quarter boxes retained |
| Count/Budget chart-scale switches | Removed; organizational and type/priority bars use project counts, with both numeric count and budget still visible |
| Zero and maximum chart-axis labels | Removed; row readings and accessible chart values retained |
| Per-reading financial coverage and paired-ratio explanatory sentence | Removed from the finance card; source totals, missing-value rules and ratio eligibility unchanged |
| Named manager workload list | Compact count of distinct recorded manager names within the selected scope; no names listed in this card |
| Unresolved-status row shown with zero | Hidden at current zero; shown for a nonzero or unavailable value; records remain loaded |

Full source issues, owner and finance notes, shared searchable multi-select filters, selected calculation dates, contributor drills, print scope and genuine historical arrows remain.

## Source-to-report definitions

The named-project eligibility rule, source classifications, six financial readings, valid numeric progress mean, status predicates, planned month-end quarters and exact project matching are unchanged from v116. One organizational hierarchy contains its actual unit children; child rows are already included in the parent. Type/priority rows use the actual joint records. Fixed count charts do not replace the numeric financial readings.

The manager summary counts distinct nonblank text labels from the manager field of the same selected eligible projects. It uses existing filter display normalization: canonical Unicode/presentation glyphs, invisible formatting removal, whitespace collapse and case folding. Arabic spelling, diacritics and punctuation remain distinct; no fuzzy name matching or splitting a cell into several people. Numeric, boolean and Excel-error cells, blanks and shared whole missing-value placeholders are excluded from this new count. This counts source labels rather than verifying individual identities. Missing manager columns are unavailable; an available column with no named manager is a genuine zero, displayed as `-`. Source names, invalid cells and original records are unchanged.

Manager-count change compares the actual scoped distinct counts only in confirmed exact historical pairs with both manager fields available and no unresolved matching identities. Missing history is unavailable; unchanged arrows stay blank. Financial and progress change guards remain unchanged. Finance-card coverage text is omitted as requested; calculations still use valid contributors and retain their existing change guards. The paired spending ratio still uses positive revised budget and nonnegative actual invoices on the same records.

## Verification

| Check | Result |
| --- | --- |
| Distinct text-name counts, formatting variants, blanks/placeholders and nontext/error cells | Passed |
| Actual scoped manager increases/decreases, unchanged indicators and missing/ambiguous history guards | Passed |
| v116 source records and existing numeric/status/date/financial objects compared with v117 | Passed; unchanged apart from the new manager summary |
| Source imports, renamed sheets, compound multi-select filters, search, reset and empty scope | Passed |
| Requested section/control/text removals, fixed count charts and conditional unresolved-status row | Passed |
| Keyboard drills/return, responsive RTL, visible tables and complete source notes | Passed |
| Populated and empty-v2 portfolio PDFs | Passed; every page inspected, complete source notes retained |
| Paired, compound-filtered and long-note PDFs | Passed; all 18 generated pages visually inspected, full notes retained |
| Exact ZIP CRC, manifest/hash coverage, clean extraction and original upload hashes | Passed; 117 files, 116 manifest hashes |
| Clean-extracted startup, settings/notes retention, imports and scoped manager summary | Passed |
| Exact-package regenerated PDF | Passed; all six scoped pages visually inspected |
| Native file/double-click opening | Not run; managed Chromium blocks file URLs |
| Monthly/PowerPoint visual regression, physical printing, full assistive-technology certification, native Office and Excel/Power Query refresh | Not run in this focused release |

Independent checks caught and corrected nontext source cells being counted as manager names. The correction affects only the new manager summary; all source rows and previous readings remain intact. Test counts are inventories of checks, not usability certification. Source-filled visual evidence remains private.

## Remaining limits and decisions

Original workbooks remain unchanged. Test/reference molds and private fictional historical fixtures are evidence, not organizational performance; none ship or are published. No real organizational historical comparison is asserted. Source completeness, blank-title eligibility and existing Data Notes counting/validation decisions remain pending outside this change.

Native double-click/file URL startup is not run when blocked by managed Chromium policy. Actual browser checks use local HTTP. Physical printing, full assistive-technology certification, native browser zoom, native Office editing and Excel/Power Query refresh are not run. PowerPoint and monthly-report assets are unchanged; their previous verification is not presented as a new visual pass. Unchanged native templates retain their empty structural chart workbooks.

No source records, sample fixtures, imported workbooks, private audit evidence or source-filled PDFs/screenshots ship.

ZIP: `Performance-App-v117.zip` (7,827,417 bytes; 117 files, 116 manifested hashes).

SHA-256: `9c8646a38ec55cf025aee82056f4c763b03a1ed723ccb6a465994e0977547fa6`.
