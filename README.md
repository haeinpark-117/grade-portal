# Grade Portal

Student grade lookup for Intro to English Linguistics (Kyung Hee University, AELTS).

- Site: https://haeinpark-117.github.io/grade-portal/
- Front end: `index.html` (this repo, served by GitHub Pages)
- Back end: Google Apps Script web app (JSON API, `?code=XXXXXX`) reading the course spreadsheet
- Demo: enter `DEMO01` to see a sample dashboard (no real student data)

The same `index.html` also runs inside Apps Script (it detects `google.script.run`); on GitHub Pages it calls the JSON API with `fetch`.
