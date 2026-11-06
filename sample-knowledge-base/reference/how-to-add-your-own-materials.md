# How to Add Your Own Materials

This sample shows the folder layout the app expects. To study with real materials:

1. Create a folder anywhere on your computer (for example `Documents/cisi-materials`) with this layout:
   ```
   cisi-materials/
   ├── topics/<part-name>/*.md
   ├── question-bank/section-a/*.md  (and section-b, section-c)
   └── reference/*.md
   ```
2. Convert your own PDFs to Markdown with `python batch-convert-pdfs.py <pdf-folder> <output-folder>`.
3. Set `MATERIALS_DIR` in your `.env` file to that folder, and restart the app.

Only use materials you are licensed to use. Never commit them to a public repository.
