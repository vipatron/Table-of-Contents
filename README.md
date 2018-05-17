# Table-of-Contents
Vanilla Javascript that adds a Table of Contents to well-ordered HTML with some bells and whistles.
Well-ordered HTML uses headings for layout, not styling.

## Future Features
- Two ways to process the data:
  - Have textareas to paste into/copy from
  - Load the file from the local machine, and write out to a file
    - Optional: overwrite the original file
- Depth flags as checkboxes
  - Option: maximum depth to be added to the TOC
  - Option: include h1 in TOC or not
- Checkbox option: link back to the TOC after every heading
  - option: link back to h1, or the TOC's id. (if include-h1 toggle is set to "no," set this to yes.)
