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

## Repository File Structure (Raw Links)

### **Audio/**
- `Classicals.de - Mozart - Symphony No. 40 in G Minor, K. 550 - I. Molto allegro.mp3` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Audio/Classicals.de%20-%20Mozart%20-%20Symphony%20No.%2040%20in%20G%20Minor%2C%20K.%20550%20-%20I.%20Molto%20allegro.mp3)
- `Classicals.de+-+Bach+-+Badinerie+-+BWV+1067+-+Arranged+for+Woodwinds+and+Strings.mp3` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Audio/Classicals.de%2B-%2BBach%2B-%2BBadinerie%2B-%2BBWV%2B1067%2B-%2BArranged%2Bfor%2BWoodwinds%2Band%2BStrings.mp3)
- `Classicals.de-Beethoven-Moonlight-Sonata-1.-Movement-Sonata-Nr.-14,-Op.-27,-Nr.-2.mp3` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Audio/Classicals.de-Beethoven-Moonlight-Sonata-1.-Movement-Sonata-Nr.-14%2C-Op.-27%2C-Nr.-2.mp3)

### **docs/**
- `CEUsample.doc` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/docs/CEUsample.doc)
- `file-sample_1MB.docx` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/docs/file-sample_1MB.docx)
- `file-sample_1MB.rtf` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/docs/file-sample_1MB.rtf)

### **images/**
- `fahrul-azmi-BCEexmxL9EQ-unsplash.jpg` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/images/fahrul-azmi-BCEexmxL9EQ-unsplash.jpg)
- `jannes-jacobs-NfsB3jPVlcM-unsplash.jpg` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/images/jannes-jacobs-NfsB3jPVlcM-unsplash.jpg)
- `the-visual-stories-studio-tvss-8OMRA8zoLKA-unsplash.jpg` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/images/the-visual-stories-studio-tvss-8OMRA8zoLKA-unsplash.jpg)
- `the-visual-stories-studio-tvss-ti7lVJzwvSY-unsplash.jpg` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/images/the-visual-stories-studio-tvss-ti7lVJzwvSY-unsplash.jpg)

### **Latex/**
- `btxdoc.tex` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Latex/btxdoc.tex)
- `elsarticle-template.tex` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Latex/elsarticle-template.tex)
- `urlbst.tex` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Latex/urlbst.tex)

### **markdown/**
- `grpcREADME.md` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/markdown/grpcREADME.md)
- `pypiserverREADME.md` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/markdown/pypiserverREADME.md)
- `rmarkdownREADME.md` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/markdown/rmarkdownREADME.md)

### **pdf/**
- `concise Dictionary of old icelandic-oxford press.pdf` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/pdf/concise%20Dictionary%20of%20old%20icelandic-oxford%20press.pdf)
- `file-sample_150kB.pdf` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/pdf/file-sample_150kB.pdf)
- `wikibook-somatosensory.pdf` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/pdf/wikibook-somatosensory.pdf)

### **RSS/**
- `ABCNEWSusheadlines.rss` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/RSS/ABCNEWSusheadlines.rss)
- `Politicohealthcare.xml` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/RSS/Politicohealthcare.xml)
- `ReutersFinanicalnews-releases.txt` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/RSS/ReutersFinanicalnews-releases.txt)

### **tables/**
- `customers-100.csv` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/tables/customers-100.csv)
- `file_example_XLSX_5000.xlsx` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/tables/file_example_XLSX_5000.xlsx)
- `products-100.csv` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/tables/products-100.csv)

### **Video/**
- `Agent 327_ Operation Barbershop.mp4` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Video/Agent%20327_%20Operation%20Barbershop.mp4)
- `Big Buck Bunny 60fps 4K - Official Blender Foundation Short Film.mp4` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Video/Big%20Buck%20Bunny%2060fps%204K%20-%20Official%20Blender%20Foundation%20Short%20Film.mp4)
- `Spring - Blender Open Movie.mp4` → [raw](https://raw.githubusercontent.com/saurabhgayali/GhostKitSampleFiles/main/Video/Spring%20-%20Blender%20Open%20Movie.mp4)

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