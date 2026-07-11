# Nagari

_Created: 22-12-2013 · Last updated: 11-07-2026_

Devanagari-script tooling and reference data for Sanskrit: OpenType font-layout
projects, OCR training resources, ligature and sandhi reference lists, and the
legacy VBAnagari transliteration macros. This repository collects material
assembled between 2005 and 2013 for typesetting, digitizing, and transcribing
Sanskrit in the Devanagari script.

## Contents

### [FontDev/](https://github.com/gasyoun/Nagari/tree/master/FontDev)

Microsoft VOLT (Visual OpenType Layout Tool) project files for two Devanagari
OpenType fonts:

- [chandas-volt/chandas1-2.vtp](https://github.com/gasyoun/Nagari/blob/master/FontDev/chandas-volt/chandas1-2.vtp)
- [uttara-volt/uttara-volt.vtp](https://github.com/gasyoun/Nagari/blob/master/FontDev/uttara-volt/uttara-volt.vtp)

### [SanskritOCR/](https://github.com/gasyoun/Nagari/tree/master/SanskritOCR)

Resources for OCR of printed Sanskrit:

- [IAST.fbt](https://github.com/gasyoun/Nagari/blob/master/SanskritOCR/IAST.fbt) — ABBYY FineReader training/pattern file for IAST.
- [Nagari ITRANS Pattern.ptn](https://github.com/gasyoun/Nagari/blob/master/SanskritOCR/Nagari%20ITRANS%20Pattern.ptn) — ITRANS recognition pattern for Devanagari.
- [SanskritSpellingDictionary.txt](https://github.com/gasyoun/Nagari/blob/master/SanskritOCR/SanskritSpellingDictionary.txt) — spelling dictionary used to correct OCR output (~2.7 MB).
- [Mahabharata.pdf](https://github.com/gasyoun/Nagari/blob/master/SanskritOCR/Mahabharata.pdf) — sample scanned page material.
- [ErrorCorrection-RussianArticle.doc](https://github.com/gasyoun/Nagari/blob/master/SanskritOCR/ErrorCorrection-RussianArticle.doc) — a Russian-language article on OCR error correction.

### [Varnamala/](https://github.com/gasyoun/Nagari/tree/master/Varnamala)

Devanagari ligature ("varṇamālā") and sandhi reference material in parallel
`.txt`, `.doc`, and `.pdf` forms:

- **460 Rigveda ligatures** — [Liste-460-Rigveda-Ligaturen.txt](https://github.com/gasyoun/Nagari/blob/master/Varnamala/Liste-460-Rigveda-Ligaturen.txt) plus an English variant and a frequency-statistics workbook.
- **807 Sanskrit ligatures** — [Liste-807-Sanskrit-Ligaturen.txt](https://github.com/gasyoun/Nagari/blob/master/Varnamala/Liste-807-Sanskrit-Ligaturen.txt) with German (`-D`) and English (`-E`) variants, and Santipur/Siddhanta font renderings as PDF.
- [Sandhi-Table-19.10.13.pdf](https://github.com/gasyoun/Nagari/blob/master/Varnamala/Sandhi-Table-19.10.13.pdf) — a Sanskrit sandhi table.
- [devanagari-unicode-font-specimens.pdf](https://github.com/gasyoun/Nagari/blob/master/Varnamala/devanagari-unicode-font-specimens.pdf) — Unicode Devanagari font specimens.
- `samasa-2000-*.txt` — compound (samāsa) word lists.
- [XindyDevanagariTestList.txt](https://github.com/gasyoun/Nagari/blob/master/Varnamala/XindyDevanagariTestList.txt) — a xindy (LaTeX index processor) test list for Devanagari sorting.

### [readme.txt](https://github.com/gasyoun/Nagari/blob/master/readme.txt)

Legacy documentation for the **VBAnagari** EmEditor transliteration macros — 21
VBA scripts for converting large Devanagari documents between Devanagari,
IAST, and Harvard-Kyoto (developed 2005–2013). The macros themselves are
distributed via the historic [samskrtam.ru Devanagari VBA converter](http://samskrtam.ru/devanagari-vba-converter/)
page and the [nagari Google Group](https://groups.google.com/forum/#!forum/nagari);
this file is retained here as the project's origin record.

## License

This repository is licensed under the [GNU General Public License v3.0](https://github.com/gasyoun/Nagari/blob/master/LICENSE).

Note: the legacy VBAnagari macros described in
[readme.txt](https://github.com/gasyoun/Nagari/blob/master/readme.txt) were
originally released under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.en_US);
that historical notice applies to those macros, while the repository as a whole
is GPL-3.0.

## Credits

Curated by Mārcis Gasūns (Krasnodar), with initial VBA code by
bayaryn@gmail.com (Minsk, 2005–2006) and changes/additions by Anton Pilyuganov
(2012–2013), per [readme.txt](https://github.com/gasyoun/Nagari/blob/master/readme.txt).
See also [samskrtam.ru](http://samskrtam.ru/) and [ayurvedam.ru](http://ayurvedam.ru/).

_Dr. Mārcis Gasūns_
