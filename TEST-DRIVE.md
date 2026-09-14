# Edge Measure — Office Fit-out Creator test drive

## Start

1. Create a new project.
2. Choose **Guided Office Fit-out Creator** as the EdgeBook option.
3. Confirm the available project information and whether one reliable plan dimension is available.
4. Review Bills 1–29 in order.

For every bill, choose one status:

- **Included** — select at least one standard activity or add a project-specific activity.
- **By others** — record the responsible party if known.
- **Not required** — deliberately exclude the bill.
- **To be confirmed** — record the question for the client.

## Finish

After Bill 29, the **Customise & Price** screen provides:

- the selected activities grouped into manageable bills;
- editable activity descriptions;
- optional cost and selling rates;
- editable units and measurement methods;
- the ability to remove an activity or add another one;
- a named, reusable EdgeBook saved directly in the app;
- client scope questions;
- an internal action list, including linked-scope checks;
- an Excel draft containing Activities, Client Questions, and Internal Actions.

Enter an EdgeBook name and choose **Save EdgeBook & finish**. The result must be available in the current project and in the company EdgeBook list for future projects.

Pricing is optional. Use **More options** only when you want to export to Excel or build the EdgeBook for this project without saving it for reuse.

## Team test — Customise & Price

Ask each tester to build a short EdgeBook with at least two included bills, then check:

1. The final screen clearly feels like the next step rather than an Excel export screen.
2. A generic description can be rewritten and the new wording appears under Manage Activities.
3. Cost and selling rates accept both `1250.50` and `1 250,50` formats correctly.
4. Rates may be left blank without stopping the EdgeBook from being built.
5. An activity can be removed from the final screen.
6. A completely new activity can be added to a chosen bill with its own unit, rates and measurement method.
7. The pricing progress figures update while rates and descriptions are entered.
8. The saved EdgeBook name appears in the reusable company EdgeBook list.
9. A new project can select that saved EdgeBook without using Excel.
10. The existing Excel export, edit, import and overwrite route still works.

## Live-project improvements to test

1. Measure an m² activity and send it to the BOQ.
2. On its measurement row, choose **Save for reuse**.
3. Select another m² activity and choose **Use saved measurement**.
4. Confirm that the quantity appears under the second activity without another shape being drawn.
5. Use **Current activity** in the measurement filter and confirm the shared shape remains accessible.
6. Remove the reused activity from the original measurement row and confirm the original BOQ quantity remains.
7. Measure a framed window or Venetian blind, enter its height and an identical count, and confirm the BOQ receives length × height × count.
8. Confirm the Ceilings library includes both new-grid and existing-grid options for 1200 × 600 mm acoustic tiles.
9. In a newly generated EdgeBook, confirm complete drywall partition systems are measured in linear metres.
10. Save a drywall wall-line measurement, reuse it for an m² acoustic-infill activity, and confirm the result is wall length × default wall height.
11. Start drawing a new measurement across an existing one and confirm its hover label disappears while points are being placed.
12. Print or preview the BOQ and confirm automatic text does not repeat the activity description after the quantity.

## Safety rule

The creator will not replace an EdgeBook after plan measurements or scoped quantities have been captured, because those quantities are linked to the existing activity IDs.
