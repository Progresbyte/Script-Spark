# ScriptSpark

**Stack:**  
- Django (Backend)  
- GPT-4  
- PostgreSQL  
- React (Frontend)  
- PDFKit or ReportLab (PDF export)  
- Fountain.js (Screenplay formatting)

---

## Features

1. **User Input**
    - Genre (sci-fi, thriller, drama, comedy, etc.)
    - Main theme or premise
    - Number of main characters (1–5)

2. **Screenplay Generation (via GPT-4)**
    - Title
    - Logline (1-sentence summary)
    - 3 main characters with bios
    - 5-scene structure
    - Dialogue excerpts (screenplay format)
    - Twist or conflict reveal

3. **Screenplay Structure**
    - Content formatted in [Fountain](https://fountain.io/) syntax

4. **Frontend Functionality**
    - Script editor with syntax highlighting and preview
    - Export to PDF and Fountain format
    - Character and Scene navigator
    - Regenerate specific sections (e.g., “rewrite scene 2”)

5. **Persistence**
    - Save screenplay drafts to PostgreSQL under user profiles

6. **AI Feedback Tool (Optional)**
    - Reviews pacing, dialogue strength, and emotional tone using GPT

---

## Monetization

- **Free:** 1 screenplay project
- **Paid:** Unlimited projects, feedback, and export options

---

## Example User Flow

1. User enters genre, premise, and number of characters.
2. GPT-4 generates a structured screenplay draft.
3. User edits, previews, and exports the script.
4. Drafts are saved to user profiles.
5. (Optional) User requests AI feedback on their script.

---

## Key Libraries & Tools

- **Backend:** Django, PostgreSQL
- **AI:** GPT-4 API
- **Frontend:** React, Fountain.js
- **Export:** PDFKit or ReportLab
- **Syntax Highlighting:** CodeMirror or Monaco Editor
