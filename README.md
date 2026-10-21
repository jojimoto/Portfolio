# Gideon Lanz Arias — Portfolio

Portfolio site for Gideon Lanz Arias, a BSIS student aiming to work as a business analyst.

## About

One HTML file with the CSS and JavaScript inline. No build step, no dependencies.

The design runs on a dithered halftone canvas behind a radial scrim, with a sticky top nav, a centred hero, and a GA monogram in the corner. Type is Instrument Sans. The palette is near-black with a single scarlet accent.

## Run locally

Open `index.html` in a browser, or serve the folder:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 8080
```

Then open http://localhost:8080/

## Sections

| Section | Contents |
| --- | --- |
| Home | Name, role, introduction, monogram, CTA buttons |
| About Me | Background, interests, career goals |
| Projects | Description, screenshot slot, technologies used, live and source links |
| Skills | Programming languages, design tools, databases, soft skills |
| Education | Degree, track, courses, achievements |
| Experience | Internships, freelance work, previous roles |
| Contact | Email, LinkedIn, GitHub, contact form |
| Footer | Social links, copyright |

## Fill these in

- `profile.jpg` — put it in the folder and it replaces the monogram.
- Projects — replace the three placeholder cards with your own. Swap each screenshot slot for an `<img>`.
- Contact form — point the `<form>` `action` at a real endpoint such as Formspree before publishing.
- Social links — `hello@example.com` and `linkedin.com/in/your-handle` are placeholders.
- Education and experience — dates, school names, and roles.

## Layout notes

- Skills use a four-column grid, dropping to two columns below 1100px and one below 580px.
- Education and experience use a two-column timeline that stacks on narrow screens.
- The nav scrolls sideways below 580px instead of wrapping.
