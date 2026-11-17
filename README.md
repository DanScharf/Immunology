# Basic Immunology – Interactive Study Guide

An interactive, bilingual (English / עברית) study website for **Basic Immunology (027604130), Technion, winter 2026–27**.

Each lecture is turned into a short, ordered set of chapters with diagrams, interactive figures, a quiz and flashcards, so the material can be learned step by step instead of from the slides alone.

**Live site:** `(https://danscharf.github.io/Immunology/#home)`

---

## Lessons

| # | Date | Topic | Status |
|---|------|-------|--------|
| 1 | 03.11 | Introduction to the immune system. Strategies of innate vs adaptive | ✅ Available |
| 2 | 10.11 | Innate immunity: functional mechanisms | ✅ Available |
| 3 | 17.11 | Complement, and where immune cells come from | ✅ Available |
| 4–13 | | Antibodies, B and T cells, MHC, vaccines, Tregs and tumour immunology | Coming soon |

## Features

- **Chapters in order**: every lecture is split into short chapters that follow the slides.
- **Key terms first**: each page opens with the basic terms it uses, so you understand them before you start reading.
- **Hover definitions**: underlined words show a short definition when you point at them (or tap on a phone).
- **Interactive diagrams**: click through pathways step by step, explore cells, receptors and organs, and try simulators such as the NK cell signal balance.
- **Quiz per lesson**: exam-style multiple-choice questions in random order, each with an explanation. Your best score is saved.
- **Flashcards and glossary** for each lesson.
- **Dictionary**: every term from all lessons in one place, searchable and filterable. Each term has its own page, with a picture where it helps.
- **English and Hebrew**: switch with the button in the header. Hebrew is fully right-to-left.
- **Works on phone and desktop**, in light and dark mode.

## Content policy

All course content comes **only from the lecture slides** (including the lecturer's notes inside the slide files). The only material added from outside the slides is short, basic scientific definitions, such as "enzyme" or "receptor", that help in reading the slides.

All diagrams are original drawings made for this site. No images are copied from the slides or from textbooks.

## How it works

The whole site is a single file, `index.html`, with no build step, no server and no external libraries (only Google Fonts). Pages are switched with the address hash, for example `#l2-recognition`.

Small conveniences are saved in your own browser (`localStorage`): your language choice, which chapters you visited, and your best quiz scores. Nothing is sent anywhere.

## Run it

**Locally:** download `index.html` and open it in any modern browser.

**On GitHub Pages:**
1. Put `index.html` at the root of the repository.
2. Go to **Settings → Pages**, choose the main branch and the root folder, and save.
3. After a minute or two the site is live at the address above.

After uploading a new version, do a hard refresh (Cmd+Shift+R / Ctrl+Shift+R) to skip the cached copy.

## Updating

To add a lesson, replace `index.html` with the new version. Its terms are added to the dictionary automatically, and its card on the home page switches from "Coming soon" to "Available".

## Disclaimer

This is an unofficial, student-made study aid. It is not affiliated with or endorsed by the Technion or the course staff. The official slides, lectures and the recommended textbooks remain the authoritative source. If something here differs from the slides, the slides are correct.

Recommended books for the course: *Janeway's Immunobiology* and *Cellular and Molecular Immunology* (Abbas, Lichtman and Pillai).

---

## בעברית

אתר לימוד אינטראקטיבי, בעברית ובאנגלית, לקורס **אימונולוגיה בסיסית (027604130)** בטכניון. כל הרצאה מחולקת לפרקים קצרים, עם תרשימים אינטראקטיביים, בוחן, כרטיסיות ומילון מונחים.

- כל התוכן לקוח **רק מהשקפים** של ההרצאות (כולל הערות המרצה בקבצים). מבחוץ נוספו רק הגדרות מדעיות בסיסיות.
- כל התרשימים צוירו במיוחד לאתר.
- זהו כלי עזר לא רשמי שנכתב על ידי סטודנט. השקפים וההרצאות הם המקור המחייב.
