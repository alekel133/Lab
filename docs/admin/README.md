# Administrative Documentation
- Description: Below is a general baseline for documentation.
- Revision: 1.0.0
- Author: Alexander Kellough (alekel101301@gmail.com)
- Date: 2026-02-02 CST

## Document Baseline
### Header
1. All documents should open with a top level header that serves as both title of the document.
2. All top-level headers should be followed by
   - A description bullet and a paragraph of more in depth description.
   - A revision number: X.Y.Z - (X = Major Revision/Rewrite, Y = Minor Revision/Update, Z = Grammar, Syntax, or Semantic fix).
   - An author bullet and corresponding name and email. <!-- This is me right now, but may be others later. -->
   - A Date bullet and the date of publish in (YYYY-MM-DD TZ) format.

### Subsections
- Subsections should be divided using markdown heading levels.
- A newline should be added between same level sections (this includes transitions from n-level sections to n-1 level sections).

### Comments
- Comments should be used throughout the markdown to denote information source reliability:
   - Begin with Reliability: 
   - Followed by AUTHORITY-DETAIL-HONESTY DATE Where each is scored out of 5
        - Authority = The prestige of the author. For network: Cisco Engineer = 5, Undergrad = 3, Conspiracy Theorist = 1.
        - Detail = The level of detail given by the source: Source Code = 5, Tutorial = 3, Reddit Comment = 1.
        - Honesty = The perceived truthfulness of the source: Manual = 5, Technical Blog Post = 3, TikTok = 1.
        - Date = YYYY.MM.DD.TZ
   - Finally, the source.
   - Notes can be placed after reliability score, beginning with "Note:", for more information.
   - These are only examples, as with all things use best judgement when both writing and reading these tags.
   - Ex (Only visible in markdown) <!-- Reliability: 3-4-3 2026.02.02.CST www.reddit.com/help Note: Scatterbrained. -->

- Every doc is encouraged to have a comment at the end with ongoing notes.

<!--
    Notes:
       - I wonder if the reliability thing is too complicated?
-->
