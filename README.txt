Edge Measure — guided EdgeBook and quick measurement flow
29 September 2026

This bundle uses the supplied index(6).html as its app baseline and brings in the guided Office Fit-out EdgeBook questionnaire from the available September Edge Measure bundle.

Project route
1. New Project → fill in project name, client, date, prepared by and site address.
2. In the open project, create a new EdgeBook in the white modal or choose an existing saved EdgeBook.
3. You may also upload a PDF and calibrate the page with one known dimension before choosing a book. Length, Area, Perimeter and Count can be tagged later.
4. Add locations/areas and tag plan measurements before sending them to Scope and BOQ.

Guided route
1. Open the white EdgeBook creator modal from EdgeBooks or Project Setup, name a new book and answer the 29-bill questionnaire.
2. The questionnaire saves a resumable draft in the company EdgeBook library.
3. Save the completed reusable EdgeBook. If a project is open, it also gets its own copy unless linked Scope quantities prevent a whole-book change.
4. Existing saved books can be selected from the open project's setup screen.

Changing a project's EdgeBook preserves untagged measurements. Unsent measurements with activity tags keep their geometry but lose those tags after confirmation. A project with Scope quantities linked to activities cannot change its whole EdgeBook.

Projects can be archived or permanently deleted with deletion PIN 2468. Saved company EdgeBooks and drafts can also be permanently deleted in the modal. The PIN is an accidental-deletion guard, not account security. The signed-in account must have Supabase permission to delete those records.

No database schema migration is included. Upload the contents of this folder to the repository root when ready. Check against the live repository before replacing production code: the supplied index file did not contain the questionnaire, and a newer deployed copy could contain other changes.
