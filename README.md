# GhostKitSampleFiles

This repository contains **sample files and test assets** used to validate and
manually test **GhostKit HTML viewers**.

Its purpose is to provide a **single, stable location** for input files across
all supported formats, so GhostKit viewers can be developed and tested without
searching for external examples.

---

## What this repository is for

- Testing GhostKit HTML viewers in isolation
- Verifying support for different file formats
- Exercising edge cases and failure scenarios
- Regression testing when viewers are updated

This repository contains **data only**.  
It does not contain application logic, viewers, or runtime code.

---

## Typical contents

Depending on GhostKit development needs, this repository may include:

- PDF files (small, large, multi-page)
- Document files (`.doc`, `.docx`, `.rtf`, `.txt`)
- CSV / XLS / XLSX tables
- Markdown files
- LaTeX (`.tex`) files
- RSS feed examples (local exports or static samples)
- Media stream references (e.g. m3u8 playlists)
- Image sets for gallery testing
- JSON files for visualization testing
- Malformed or edge-case files for robustness checks

---

## How it is used

- Files are loaded via **URL** or **local path** into GhostKit viewers
- Used during viewer development, debugging, and validation
- Used to confirm behavior without relying on external sources
- Acts as a long-lived reference set for repeatable testing

---

## What this repository is NOT

- ❌ Not a GhostKit implementation
- ❌ Not a demo or showcase
- ❌ Not curated or authoritative content
- ❌ Not guaranteed to contain real-world data

Files exist **only** to exercise viewer behavior.

---

## Organization & naming

- Filenames indicate:
  - file format
  - size or structure
  - edge case (if applicable)
- Folder structure may evolve over time
- Files should not be removed once used for regression testing

---

## License

* Unless explicitly stated otherwise, files are provided **for testing and
development purposes only**.
* Permission is granted for non-commercial use only, provided that the original sources listed in the Acknowledgments section are clearly credited.


---

## Notes

If a GhostKit viewer fails on a file in this repository, the file should be
retained as a **regression test case**, not deleted.

---
## Acknowledgements
* https://file-examples.com/
* https://unsplash.com/
* https://www.classicals.de/
* Blender Foundation
* https://www.latextemplates.com/
* https://www.ctan.org/
* https://github.com/rstudio/rmarkdown
* https://github.com/grpc/grpc
* https://github.com/pypiserver/pypiserver
* https://abcnews.go.com/abcnews/usheadlines
* https://rss.politico.com/healthcare.xml
* https://ir.thomsonreuters.com/
* https://podcasts.ceu.edu
* https://www.princexml.com/
* Oxford Press
* https://en.wikibooks.org/
* https://www.datablist.com/