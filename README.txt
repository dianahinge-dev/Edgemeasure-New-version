Edge Measure — 19 October 2026 update

Deploy
Unzip this bundle and upload the contents of the extracted app folder to the existing repository root, as usual. No SQL or database schema update is required. This bundle has not been deployed to the live app.

Changes
- Count activities have an optional marker of up to two letters or numbers, such as E, DK (desks), DA (data) or DR (doors). Leave it blank to use numbered markers.
- Manage Activities: choose Count, enter the optional marker, and save. Markers can be changed on activities already in use without changing quantities.
- EdgeBook Creator: custom activities and the review screen include the optional marker field.
- Excel EdgeBook templates, drafts and exports include an optional Count marker column. Older EdgeBooks still import; Count E, Count D and Count P retain their symbols.
- Hover labels show the category and measured value. If no category is available, the activity description is used.
- Wall Height and Wall SQM strokes are 20% thinner, including their contrast outline. Other measurement methods keep their current thickness.
- The collapsible capture-symbol legend shows only custom or E/D/P count symbols used by visible items on the current page, labelled by Bill with one entry per marker within each Bill. It excludes lines, areas and plain numbered counts, disappears when no symbols are used, and is included when printing or saving the annotated plan as a PDF.
- BOQ descriptions omit automatic From plan and counted on plan notes, including in older saved projects. Actual notes and deduction details remain.

Validation
Checked in an isolated Chromium browser with sample project data: legacy count conversion, editing markers on used activities, quantity calculations, category labels, page-specific legends, canvas stroke widths, real XLSX export/re-import, legacy XLSX import, guided builder custom activities and saved-book payload, and one-page A3 plan printing. Live authentication and Supabase writes were not exercised.
