# Fady Nabil | Personal portfolio

A personal portfolio for Fady Nabil, a Business Information Systems student at Capital University in Cairo and an aspiring full-stack developer.

This is a **guided, assisted learning project**, not a claim of independent professional development experience. The site presents skills as learning in progress. Projects are learning exercises, not client work or production systems.

## Open it

1. Download and extract the ZIP.
2. Open `index.html` in your browser.

No installation, account, build step, framework, API key or internet connection is needed to view the site. External links and email need their normal apps or connection.

## Files

```text
index.html       Content and page structure
styles.css       Responsive layout and visual design
script.js        Small accessible mobile navigation enhancement
favicon.svg      Initials icon
portrait.png     Supplied portrait, transparent background
.nojekyll        Disables Jekyll processing on GitHub Pages
README.md        This guide
PUBLISH.md       Click-by-click GitHub Pages instructions
```

The CSS illustration is decorative, not an analysis chart or a claim about results. All fonts are system fonts. The supplied portrait is stored locally as a transparent PNG with its background removed and without its original metadata. There are no remote font services, tracking scripts, cookies, forms, dependencies or stock photos. The email link opens the visitor's email app; the site does not send or store messages.

## Sections

- Intro and about: student background and learning direction.
- Skills: ASP.NET Core, EF Core, Angular, HTML, CSS, JavaScript, SQL and GitHub, all framed as learning/practice.
- Projects: UCI student-performance analysis first, then this portfolio.
- Contact: email and GitHub.

## Before publishing

- Read the copy in `index.html` and make sure it describes you accurately.
- Confirm that you want the included email address visible on the open internet. Remove the email row if you prefer GitHub-only contact.
- The student-performance project links directly to its published repository: https://github.com/FadyyNabil/student-performance-analysis. Its README documents the AI-assisted starter and limits of the analysis. Keep that framing when discussing the work.
- No CV, personal phone number, detailed address or private credentials are included.

See [PUBLISH.md](./PUBLISH.md) for publishing steps. Nothing is published merely by downloading these files.

## How it works

- Semantic HTML provides the content, heading order, section landmarks and links.
- CSS Grid and Flexbox change the layout at smaller widths. Media queries stack cards on phones.
- The menu button updates `aria-expanded`. Escape closes the menu and returns focus to the button. Without JavaScript, navigation remains visible.
- A skip link and visible focus outlines support keyboard navigation.
- Reduced-motion preferences disable smooth scrolling.
- All local paths begin with `./`, so the site works both in a normal project repository and in a GitHub user-site repository.

## Practise before describing this project in an interview

1. Change the introduction and explain the HTML tags you used.
2. Add a project card yourself using a real repository URL.
3. Change the mobile breakpoint and observe what breaks.
4. Explain how the menu button's `aria-expanded` value changes.
5. Turn JavaScript off and explain why the links still work.
6. Explain that GitHub Pages only serves this static portfolio. A future ASP.NET Core API and SQL database require separate hosting.

Only claim skills and understanding you can explain. This starter is a base for your own revisions.

## Maintenance

Edit text and links in `index.html`, colours and layout in `styles.css`, and menu behavior in `script.js`. No generated files need updating. Keep published claims, project links and contact details current.
