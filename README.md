# rothfuss.io

Plain static site, no build step. Every page is hand-editable HTML.

| Page | Contents |
|---|---|
| `index.html` | Home: about, contact, CV table of contents |
| `legislature.html` | Wyoming State Senate |
| `university.html` | University of Wyoming roles, courses, theses supervised |
| `career.html` | Other positions (X, Pilot Hill, Xinova, State Dept, ...) |
| `education.html` | Degrees and continuing studies |
| `research.html` | Publications, patents, dissertation |
| `talks.html` | Presentations, meetings, workshops |
| `awards.html` | Awards and honors |
| `files.html` | Index of everything in `files/` |

The menu at the top and the previous/next links at the bottom are repeated on each page; if you add or rename a page, update them everywhere.

`style.css` is deliberately tiny. `files/` holds the downloadable PDFs.

Preview locally: `python3 -m http.server`, then open http://localhost:8000.

Hosting: GitHub Pages from `main`, custom domain in `CNAME`.
