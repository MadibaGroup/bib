Review proposed additions against the attached bibliography. Use its prevailing conventions as the style guide; existing outliers are not precedents to copy.

Before adding an entry:

- Check for an existing version of the same work. Prefer updating or completing that entry over creating a duplicate.
- Choose the correct BibTeX type based on the source being cited.
- Use a concise citation key consistent with nearby entries: usually author surname initials plus a two-digit year; surname-based keys are also used for single authors. For organizational or authorless sources, use a descriptive single-word tag beginning with `+`, such as `+voatz`. Check for collisions.
- Verify uncertain publication details using authoritative sources. Do not invent missing authors, dates, publishers, or other metadata.

Keep entries minimal:

- `inproceedings`: only `author`, `booktitle`, `title`, and `year`. Use this type for conference/workshop papers and conference talks.
- `article`: `author`, `journal`, `title`, and `year`, plus existing publication dates, volume, issue/number, and pages when useful. Newspapers and magazines belong here too.
- `techreport`: use only when an identifiable institution, publisher, or report series issues the report. IACR ePrint reports qualify; an arXiv, CoRR, SSRN, or CiteSeer listing alone does not. Preserve relevant institution, report number, and report type.
- `misc`: websites, documentation, blog posts, press releases, speeches, self-published papers, and repository preprints without a clear report issuer. Preserve useful source descriptions and URLs.
- Use `book` for whole books, `incollection` for chapters in edited books, and the appropriate thesis type for confirmed theses. Use `unpublished` for unpublished manuscripts when appropriate.

Match established venue names in the bibliography. Prefer recognizable short names and appropriate IEEE/ACM prefixes, with these specific conventions:

- Main FC conference: `Financial Cryptography`.
- FC workshops: `FC Workshops (ACRONYM)`, such as `FC Workshops (WTSC)` or `FC Workshops (VOTING)`. Determine the actual workshop rather than treating the combined proceedings title as the main conference.
- Advances in Financial Technologies: `AFT`, without an ACM prefix.
- Security and Privacy conference: `IEEE Symposium on Security and Privacy`.
- Security and Privacy magazine: `IEEE S\&P`.

Use BibTeX `author` and `booktitle` fields, not literal fields named “authors” or “conference.” Separate authors with `and`; prefer given-name-first formatting and brace organizational authors appropriately. Preserve necessary LaTeX escapes and protect acronyms or system names selectively.

Use a four-digit `year`; put additional date information in separate fields. Do not invent a year from an access date. Remove import clutter such as abstracts, BibDesk dates, local file attachments, ratings, and duplicate URL metadata. Preserve useful links and identifiers, especially for online-only sources.

Match the file’s formatting: tab-indented fields, generally alphabetical field order, braced values, and blank lines between entries. Avoid unrelated edits to existing entries.

Return the cleaned addition(s), identifying any duplicate matches, citation-key changes, or unresolved classification questions. Ask only when the attached bibliography and reliable sources do not resolve a meaningful ambiguity.