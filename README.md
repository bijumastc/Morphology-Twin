# Morphology-Twin
Beginner Level Morphology Notes and tests
# Morphology Twin

A web-based assessment module for English Linguistics — Morphology.

## Features

- **Two Test Sets**: Set 1 (Beginner) and Set 2 (Intermediate), each containing:
  - 15 two-mark questions (2–3 sentence answers)
  - 6 paragraph questions (full paragraph answers)
  - 4 essay questions (detailed multi-step answers)
- **Immediate Feedback**: Check each answer individually to see a model answer and feedback
- **General Feedback**: Overall performance summary with grade and study recommendations after completing a test
- **Teacher Dashboard**: Login-protected dashboard with student results, statistics, and CSV export
- **Google Sheets Integration**: Optional backend to store results in Google Sheets

## Topics Covered

All questions are based strictly on English morphology:
- Morphemes, morphs, and allomorphs
- Free and bound morphemes
- Roots and affixes (prefix, suffix, infix, circumfix)
- Null/zero morphemes
- Inflectional morphology (8 English inflectional suffixes)
- Derivational morphology
- 14 word-formation methods: affixation, compounding, conversion, blending, clipping, acronyms, initialisms, backformation, reduplication, coinage, borrowing, eponyms, onomatopoeia, calque
- Lexical vs. grammatical morphemes
- Open and closed word classes
- Tokens, types, and lexemes
- The mental lexicon

## Setup

### Basic (no backend)
Simply open `index.html` in a browser. Results are stored in localStorage.

### With Google Sheets
1. Create a new Google Sheet with a "Results" tab
2. Go to Extensions → Apps Script
3. Paste the contents of `google-apps-script.js`
4. Deploy as a Web App (access: Anyone)
5. Copy the deployment URL into the `SHEET_URL` variable in `index.html`

### Teacher Login
- Username: `admin`
- Password: `morph2024`

## Author
Created for English Linguistics instruction.
