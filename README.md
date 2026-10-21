# Gideon Lanz Arias — Portfolio

A personal portfolio for Gideon Lanz Arias, a BSIS student focused on business analysis, data, and systems thinking.

## About

The site presents Gideon's background, projects, skills, education, and contact details in a black, scarlet, and white visual theme, with an animated geometric GA monogram, a circular profile picture, and a subtle scanner-style background.

## Run locally

Open `index.html` in a browser. The site is built with HTML, CSS, and vanilla JavaScript and has no build step.

To preview with a local server instead:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 8080
```

## Sections

| Section | Contents |
| --- | --- |
| Home | Name, professional title, introduction, profile picture, CTA buttons |
| About Me | Background, education summary, interests, career goals |
| Projects / My Works | Description, screenshot slot, technologies used, live + source links |
| Skills | Programming languages, design tools, databases, soft skills |
| Education & Certifications | Academic background, training, achievements |
| Work Experience | Internships, freelance work, previous roles |
| Contact Me | Email, LinkedIn, GitHub, and a contact form |
| Footer | Social links and copyright |

## Things to fill in

- `profile.jpg` — drop your photo in the project folder and it replaces the monogram automatically.
- Projects — replace the three placeholder cards with your own, and swap each screenshot slot for an `<img>`.
- Contact form — point the `<form>` `action` at a real endpoint (e.g. Formspree) before publishing.
- Social links — `hello@example.com` and `linkedin.com/in/your-handle` are placeholders.
- Contact sheet — the `profile.jpg` / screenshot slots are intentionally empty.

## Layout

- Skills render as a four-column grid, collapsing to two columns below 1100px and one below 580px.
- Education and Experience use a two-column timeline layout that stacks on narrow screens.
- The navigation sits in a rounded pill container and scrolls horizontally below 580px.
