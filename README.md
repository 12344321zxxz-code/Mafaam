# סימולטור מפע"ם

Practice old Israeli psychometric tests in the Mafaam (מפע"ם) format: one question at a time, per-question timers, no skipping and no going back, adaptive difficulty, and 7 minutes alone with each reading passage and each chart before their questions appear.

## How to use
1. **ייבוא מבחן**: create a test, upload the PDF (or page images).
2. Pick the chapter and question type, then drag a box around each question, including its 4 answers. Mark them in the order they appear in the test, because that order sets the difficulty level.
3. For a reading passage or a chart: mark the passage or chart first, then its questions. The questions are attached to it automatically.
4. Enter the correct answers: press 1–4 right after marking a question, or paste the chapter's answer key.
5. **בית → התחל סימולציה**.

Everything is saved in the browser (IndexedDB). Use **מאגר שאלות → ייצוא** to back up your bank or share it.

## Hosting
It's a single `index.html` with no build step. Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and open the URL.

Timers and the test structure can be changed in **הגדרות**. The default timers come from the NITE page:
https://www.nite.org.il/special-test-accommodations/two-domain-mifam/
