# TEI XML Digital Scholarly Editions

This repository section contains digital text encodings created according to the **TEI P5 (Text Encoding Initiative)** guidelines, demonstrating scholarly digital editing and metadata structuring.

## 📄 Encoded Texts

### 1. Abraham Lincoln to Joshua Fry Speed (20 February 1849)
* **File:** [`lincoln-letter.xml`](./lincoln-letter.xml)
* **Description:** Scholarly transcription and encoding of a historical manuscript letter from Abraham Lincoln to his confidant Joshua Fry Speed, held at the Maine Historical Society.
* **Features:**
  * Detailed manuscript metadata (`msDesc`) and physical description.
  * Prosopographical authority file tagging (`listPerson`) linked with external identifiers (VIAF, Wikidata, Library of Congress).
  * Line-by-line facsimile alignment (`<lb/>`, `<pb/>`) and scribal intervention markup (`<add>`, `<gap>`).

---

### 2. Emily Dickinson – "I Never Saw A Moor"
* **File:** [`dickinson-poem.xml`](./dickinson-poem.xml)
* **Description:** Digital edition encoding of Emily Dickinson's famous poem.
* **Features:** Structural verse markup (`<lg>`, `<l>`) and TEI header bibliographic alignment.

---

## 🛠️ Skills & Technologies

- **Standard:** TEI P5 XML
- **Tools & Validation:** RelaxNG Schema, Schematron
- **Methods:** Digital Philology, Metadata Structuring, Authority Record Integration (VIAF / Wikidata)

## Academic Context

Developed as part of my Master's Degree coursework in Digital and Public Humanities.
