# St. Peter's Modern Website

Static HTML5, CSS3, Bootstrap 5.3, vanilla JavaScript and AOS redesign for St. Peter's Educational Association.

## Upload

Upload the full `st-peters-modern-website` folder contents to your hosting public directory. Open `index.html` as the home page.

## Update Content

- Edit page text directly in the relevant `.html` file.
- Replace images in `assets/images/` and update the matching `src` path if needed.
- PDF/document buttons currently preserve the original live URLs from `https://www.stpetershnk.org/`. To host documents locally, place files in `assets/pdf/` and update the links.
- Pages marked "Content to be updated by admin." existed in the requested sitemap but did not have detailed source text available in the legacy scrape.

## Old URL Compatibility Notes

Recommended redirects after upload:

- `b.aboutus.html` -> `about.html`
- `b.vission & Mission.html` -> `vision-mission.html`
- `b.directormessage.html` -> `director-message.html`
- `b.principalMessage.html` -> `bed-principal-message.html`
- `d.principalMessage.html` -> `ded-principal-message.html`
- `d.admissions.html` -> `ded-admissions.html`
- `bedfaculty.html` -> `bed-faculty.html`
- `dedfaculty.html` -> `ded-faculty.html`
- `dpsefaculty.html` -> `dpse-faculty.html`
- `gallery_test.html` -> `gallery.html`
- `d.contact.html` and `contact.html` -> `contact.html`

## Features

- Sticky responsive navbar with dropdowns
- AOS scroll animations
- Faculty cards and table views
- Document search/filter
- Gallery modal/lightbox
- Frontend-only contact form validation
- SEO titles, descriptions and home structured data
