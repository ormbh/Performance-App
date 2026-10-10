# Source-grounded design notes for the portfolio concepts

Concept advice only; production code and supplied workbooks remain unchanged. Reviewed the current model, the rendered sector/unit and manager areas, and the reporting preferences already supplied. This file contains no imported figures, project content or personal names. Design risks below are analytical judgments, not observed usability-study findings.

## One sector/department area

Use one always-visible hierarchy: a sector summary row followed by its departments. Direct standalone units appear at the same first level as sectors, with the parent organization shown as context. A standalone unit should appear once. Preserve blank departments as explicit children of their known sector and unresolved classifications in a separate review group.

Use consistent columns for **القطاع / الوحدة، عدد المشاريع، الموازنة المعتمدة**. Bold summary rows and indentation should distinguish sector subtotals from the included department detail. Only the disjoint first-level rows produce the portfolio total; do not sum every displayed row. This replaces the current two alternative tables of the same records with one understandable structure. Keep children visible in the default screen and print view.

A count opens all records in that exact group. A budget amount opens only its contributing records with valid numeric amounts. Show budget coverage when incomplete. A zero amount is a recorded numeric result; an unavailable amount stays unavailable. Reuse source hierarchy and approved lookup aliases without changing raw snapshot identities.

The model already exposes disjoint sector/standalone groups and department groups with sector context, row membership and drill IDs. A hierarchy needs a presentation mapping between those groups, preserving their actual membership; it does not need a new KPI.

## One priority/type area

Use one **الأولوية ونوع المشروع** cross-tab. Priority forms the rows and type forms the columns, following source order. Each intersection shows both a project count and the revised approved-budget amount, with incomplete financial coverage beside it. Provide row totals, column totals and one portfolio total. Retain unknown, blank and additional source categories.

Keep the count and money distinguishable through labels and typography. An empty intersection can show no records; it must not masquerade as a measured zero budget. A nonempty intersection with no valid budget values shows its count and an unavailable amount. Counts and budgets must remain visible together, including in print.

Current priority and type arrays are separate marginal distributions. A true matrix requires grouping the actual scoped records by **priority + type**, then registering a count drill and a valid-budget contribution drill for each cell and margin. Multiplying or joining the two marginal totals cannot recover intersections. Historical cell arrows require the same verified snapshot and coverage rules as the existing metrics.

Avoid a red/amber/green heatmap or treating high budget as high importance. No source policy defines such a scale. A matrix with clear numbers is sufficient; any optional shading must communicate quantity alone and have a clear legend.

## Project-manager workload

Lead with registered work still open under the existing source rules, followed by overdue exposure and forthcoming deadlines. Keep total assigned projects as context because it also contains completed and other source states. A compact horizontal comparison can show open-work counts with exact numeric labels; display overdue counts alongside rather than stacking them as an additional population. Keep the comparison table visible and accessible.

Suggested columns are **مدير المشروع، المشاريع المفتوحة، متأخر، استحقاق خلال 1–30 يوماً، إجمالي المشاريع، الموازنة المعتمدة**. Mean source progress may remain secondary, clearly distinguished from the proportion of completed projects. Use neutral count/budget styling; neither is a capacity or competence rating. Do not label a manager overloaded, efficient or underperforming without effort, capacity and responsibility data.

Existing manager groups provide assigned counts, status distributions, overdue counts, valid progress, budgets, coverage and contributing rows. Per-manager open and upcoming-deadline figures need additional aggregates and drill IDs from those same scoped records. Deadline eligibility is intentionally distinct from exact source-status classification: do not assume the sum of displayed status counts always equals the date-eligible open population. Preserve the existing month-end and selected-date rules.

Keep unassigned records visible. A missing manager field is different from a present field containing blank names. Do not merge possible name variants or split a joint-name cell into several people without an approved ownership mapping. No current field establishes available staff capacity, project effort or contractual manager accountability.

## Shared interaction and comparison requirements

| Concept element | Required source/model information | Interaction |
|---|---|---|
| Hierarchy row | Existing sector/unit relationship, group membership, count, budget value/coverage | Exact group records or contributing budget records |
| Priority/type cell | Raw source priority/type, scoped eligible records, valid revised budget | Exact intersection; separate count and money populations |
| Manager workload bar | Source manager, existing open/deadline predicate, selected cutoff, matching rows | Exact manager/open subset |
| Manager upcoming/overdue count | Planned end, source status, selected date, existing date-bin rules | Exact eligible deadline subset |
| Change indicator | Confirmed distinct snapshots, approved exact keys, matching scope/fields, required numeric coverage | Observed difference with period context |

Every area follows the shared filters; multiselect unions within a field and intersections between fields remain unchanged. Missing history stays unavailable, genuine unchanged comparisons remain blank, and percentage differences use percentage points. Assignment and budget changes are direction only, not evidence of improvement or approval. All chart labels, tables, drilldowns and print outputs must share the same scoped records. Avoid nested vertical scrolling, hidden table content and unexplained alternate denominators.
