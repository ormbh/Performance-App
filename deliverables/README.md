# Performance App v106 — one scroll region in filters

[Download v106 ZIP](https://github.com/ormbh/Performance-App/raw/refs/heads/main/deliverables/Performance-App-v106.zip). Extract the entire ZIP and open `index.html`.

Filter search and multi-select are preserved. The popup now contains one scrollable options list; its title, search field, select-all and clear-selection controls stay visible. It fits the available viewport on short screens instead of clipping its controls into a tiny area beside the trigger. An actively focused filter retains its query, selection and focus when the viewport shrinks. Selection redraws keep the popup open, and mouse-wheel scrolling can move away from a focused checkbox. Keyboard navigation reveals the full option row where it fits; Escape restores focus to the trigger.

The independently reproduced v105 problem was two active nested vertical scroll regions: the popup and its list. v106 has only the list. The fix applies to all shared filter families across search, monthly reporting, projects, entities, comparison and detailed reports.

Passed: exact ZIP CRC, clean extraction and every manifest hash; source/bundle consistency; actual browser checks of Arabic search, multi-select, select-all/clear, empty-result recovery, checkbox and whole-row focus, query persistence, short/landscape screens, resizing an open popup, and real mouse-wheel behavior. Actual desktop/mobile filter screenshots were reviewed. A discovered selection-after-resize closure was fixed and independently retested before release.

Calculation, data-loader and report/export modules are byte-identical to v105. Their earlier reconciliation, notes/settings upgrade and actual monthly PDF evidence is reused rather than claimed as a new full report sweep. No source workbook, sample records, screenshots or source-filled report examples are included in this release. The v105 footer, typography, portfolio order, visible tables and direct-print workflow remain in place.

Real mobile-device software-keyboard behavior was not run; reduced viewport and focus behavior were tested in Chromium. Windows double-click startup, physical printing, full screen-reader certification and Microsoft PowerPoint interactive editing remain not run.

Final ZIP SHA-256: `583f197e861a9d5863cbe4840b26d1d53ff22cd45eff5149c41c1af83d28b735`.
