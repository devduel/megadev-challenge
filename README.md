# S01E03 — what it shows

This repository contains the signed KB page source and a standalone rendered preview for ticket #4471.

- `support-kb/src/routes/kb/incidents/4471/+page.svx` is intended for the supplied support-KB runtime and uses its existing `CauseTable`, `QueueTimeline`, `Callout`, and `RenderStamp` components.
- `support-kb/rendered/incidents/4471.html` is a self-contained rendering of the page using the downloaded export.

The report export is kept out of this public repository. The counts use unique report IDs from that export; its overlapping rows are not counted twice.
