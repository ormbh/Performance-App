# Performance App v105

[Download the current ZIP](https://github.com/ormbh/Performance-App/raw/refs/heads/main/deliverables/Performance-App-v105.zip). Extract the entire ZIP and open `index.html`; all assets are local. No server is required by the product. Imported data stays on the device.

## Changes from v104

- File name and selected calculation date move from the page heading to a shared footer. A distinct saved-source reference is shown when different. Monthly PDF pages repeat source file name and selected date alongside the existing organizational wording and copyright.
- Strategy, council decisions and legislation share the same title, label and figure typography on desktop, mobile and paper. Long labels wrap; full notes remain intact.
- Executive follow-up portfolios are on the right and projects on the left, matching the RTL mold. Executive content appears first on narrow screens.
- Follow-up tables and other data sections remain visible. Filters, help and source-quality explanations can still collapse.
- **طباعة التقرير** prints the current filtered report directly. The adjacent **إعدادات الطباعة** opens a native dialog in place. Date/layout changes persist; **حفظ الإعدادات** closes the dialog and returns focus to the print button. Escape and the close control return focus to settings without moving the page.

The v104 navigation and searchable multi-select filters are retained. Union within each filter, intersection between filters and scope consistency across screen, detail, print and CSV remain unchanged.

## Data and reconciliation

No supplied workbook, embedded source records, screenshot, source-filled PDF/PPTX example, sample-file fingerprint, data-purpose selector or sample-classification banner is delivered. The mold is a test reference for source fields and calculations. Neutral editable chart/workbook templates remain empty scaffolds. No RAG thresholds, server or tracking were introduced.

Source totals, status complements, KPI measurement/result/target populations, exact identifier matching, missing-value handling and full notes were checked against the unchanged source reference. Genuine measured zero still requires an explicit measurement-state field. Selected calculation date, reporting period, historical cutoff and source reference retain separate meanings; unavailable history is not zero. Both v102 and v104 upgrades preserve the tested complete Arabic note and A3 setting. Keep a notes backup when moving folders or changing browser profiles because file-origin storage varies by browser.

## Verification

Passed: exact ZIP CRC and manifest hashes, clean extraction, bundle consistency and actual browser startup; responsive RTL, source footers, visible tables, matched card typography, keyboard/dialog focus, date/reset, compound filters, empty results, Arabic search, scoped CSV, measurement and duplicate-ID cases, notes/settings upgrades. Generated A4 and filtered A3 PDFs were inspected for full notes, scope, pagination, column order, font equality, repeated footer visibility and no logo. A long filename was challenged to check escaping, wrapping and continuation-page visibility; a discovered footer regression was fixed before release.

The unchanged PowerPoint export implementation retains native editable chart/workbook elements validated in the earlier review. Microsoft PowerPoint interactive editing was not run. Native file-opening is blocked by the managed test browser, so Windows double-click startup remains not run. Physical printing, full screen-reader certification and live user research also remain not run. Detailed report pages were sampled in the earlier review rather than every page independently read at full size.

Final ZIP SHA-256: `4021e6875a305033aaef11aa5788dd43f86cff3d5f35b7596ae5f3c31087b6ac`.
