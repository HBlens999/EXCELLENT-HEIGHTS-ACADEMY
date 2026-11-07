# Excellent Heights Academy

**Project 2: School Management and Information Website**  
**Student:** Agbo Joseph Chiemezie  
**Project type:** Real-life client simulation / HTML5 and CSS3 assignment

## Project description
A responsive, multi-page information website designed for the simulated private school client, Excellent Heights Academy. It introduces the school, explains its learning pathway, shares activities and sample notices, and gives families a way to make an admission or general enquiry.

> **Client simulation notice:** Excellent Heights Academy and the school information on this website are presented for an academic project. Contact details, dates, announcements and operational policies must be verified by an actual school before public use.

## Objectives
- Build a six-page website with consistent navigation.
- Use semantic HTML5 elements and meaningful page structure.
- Demonstrate HTML tables, lists, images, forms and embedded media.
- Apply CSS selectors, colours, spacing, borders and the box model.
- Use Flexbox and responsive media queries.
- Publish the project using GitHub Pages.

## Technologies used
- HTML5
- CSS3
- SVG illustrations
- GitHub and GitHub Pages

No JavaScript, Bootstrap, Tailwind or other front-end frameworks are used.

## Website pages
1. `index.html` — Home
2. `about.html` — About Us
3. `academics.html` — Academic programmes
4. `admission.html` — Admission information and application enquiry form
5. `activities.html` — Activities, sample timetable, announcements and embedded video search
6. `contact.html` — Contact form, social links and location map

## Folder structure
```
EXCELLENT-HEIGHTS-ACADEMY/
├── index.html
├── about.html
├── academics.html
├── admission.html
├── activities.html
├── contact.html
├── css/
│   └── style.css
├── images/
│   ├── logo.svg
│   ├── school.svg
│   ├── classroom.svg
│   ├── lab.svg
│   ├── football.svg
│   ├── basketball.svg
│   ├── debate.svg
│   ├── music.svg
│   ├── coding.svg
│   └── cultural.svg
└── README.md
```

## Features developed
- Shared navigation menu and footer on all six pages.
- School welcome banner, motto, school levels and sample announcements.
- Mission, vision, core values and school management message.
- Academic programme descriptions and subject areas.
- Admission application form with text, date, radio, select, email, telephone, textarea and required declaration checkbox fields.
- Weekly academic timetable using table headings and row headings.
- Six activity cards with individual SVG illustrations and descriptions.
- Embedded video discovery frame and Abuja map.
- Contact enquiry form, social media links and responsive layouts.
- CSS hover and focus states, Flexbox, grid layouts and mobile media queries.

## Forms and functionality notes
The forms use a demonstration `mailto:` action. They do not save applications or messages to a database. A real deployment should connect them to an authorised school email or secure form-processing service. Replace the example email destinations before real use.

The embedded video area is a YouTube search embed to help the visitor find a relevant school tour; replace it with a school-approved video embed URL when one is available.

## Repository and live website
- **GitHub repository:** https://github.com/HBlens999/EXCELLENT-HEIGHTS-ACADEMY
- **GitHub Pages:** https://hblens999.github.io/EXCELLENT-HEIGHTS-ACADEMY/

GitHub Pages must be enabled in **Settings → Pages → Deploy from a branch → main → /(root)**. The live link becomes available after GitHub completes its deployment.

## Challenges encountered and resolutions
- **Consistent navigation across several pages:** a shared navigation structure and common stylesheet were used.
- **Responsive display:** Flexbox, CSS Grid and media queries adapt layouts for smaller screens.
- **Image availability:** lightweight SVG illustrations are stored in the repository, so the project does not depend on remote image hosts.
- **Form processing:** HTML can collect and validate fields in the browser, but a backend or authorised form service is required to store and process submissions.

## How to view locally
Download or clone the repository, then open `index.html` in a web browser. Keep the folder names and relative paths unchanged.
