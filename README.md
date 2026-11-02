# Sweet Crumbs Bakery — Part 3 (WEDE5020)

**Student:** Thakane Penelope Mankgaba (ST10484839) | **Group:** Year 1 Group 4 | **Lecturer:** Deogratias Phiri

## Project overview
This project continues the Sweet Crumbs Bakery website from Part 2. The cream, brown and pink colour scheme, supplied bakery images and page layout have been kept. Part 3 adds JavaScript interaction, custom form validation, SEO improvements and publishing support. All file names are lowercase so the links work on case-sensitive web servers such as GitHub Pages and Netlify.

## Website files
- `index.html` — Home page, gallery lightbox and FAQ accordions.
- `services.html` — Bakery services.
- `about_us.html` — Bakery background, mission, vision and values.
- `product.html` — Product catalogue with live search and category filters.
- `enquiry.html` — Enquiry form with validation and email preparation.
- `contact.html` — Contact form, contact details, business hours and interactive map.
- `css/style.css` — Shared styles, responsive layouts, animation, gallery, form and map styles.
- `js/main.js` — Shared JavaScript for search/filtering, lightbox, form validation, map and reveal effects.
- `robots.txt` and `sitemap.xml` — Crawler and sitemap files.
- `images/` — Bakery images and responsive image sizes.
- `Sweet_Crumbs_Bakery_Proposal.pdf` — Part 1 website proposal.

## Part 3 functionality
1. **Interactive elements:** FAQ accordions, hover/focus transitions, scroll reveal effects and product category buttons.
2. **Interactive map:** Leaflet and OpenStreetMap show central Johannesburg, the area the bakery serves. If the map cannot load, a text message is shown instead.
3. **Gallery lightbox:** Click a gallery or content image to enlarge it. Close it with the button, an outside click or the Escape key. Keyboard focus stays on the close button while it is open.
4. **Dynamic content/search:** Product cards filter as the visitor types and can also be filtered by category (cakes, cupcakes, bread, cookies). A live result count and a "no results" message are shown.
5. **SEO:** Every page has a unique title, meta description, keywords, canonical link, robots, Open Graph tags and a favicon. The home page includes `LocalBusiness` (Bakery) structured data. Each page has one `h1`, descriptive alt text, descriptive internal links and responsive images with width and height set.
6. **Forms:** Both forms use JavaScript validation with an error message under each field, `aria-invalid` and `role="alert"` for screen readers, and focus moved to the first error. Rules: name (letters only, 2+ characters), email format, phone number format (9–15 digits, optional +), required selections, event date not in the past, quantity 1–500, and message length 10–1500 characters. Valid submissions prepare an email in the visitor's email application.
7. **Performance/accessibility:** Responsive image `srcset` with correct widths, `loading="lazy"` on gallery and product images, reduced-motion CSS, visible focus states, a skip link, a `fieldset`/`legend` for radio buttons, higher-contrast pink and a keyboard-operable lightbox.
8. **Crawler files:** `robots.txt` and `sitemap.xml` use the planned domain from the proposal (`https://www.sweetcrumbsbakery.co.za/`).

## Form limitation
This is a static HTML website. The forms validate user input and open a pre-filled email in the visitor's email application. They do not send email directly, save data to a database, or submit to a server. A server-side or form service would be required for automatic submission. The recipient is `info@sweetcrumbsbakery.co.za`.

## Sample business details
The phone number (+27 11 555 0123), business hours and the Facebook and Instagram links on the Contact page are sample details for this assignment. Replace them with the bakery's confirmed details before real use.

## Deployment checklist
1. Commit the HTML, CSS, JavaScript, README, `robots.txt`, `sitemap.xml` and image files to the GitHub repository.
2. Use descriptive commit messages, for example `Add Part 3 JavaScript and SEO improvements`.
3. Deploy the repository using GitHub Pages or Netlify.
4. If the live address differs from `https://www.sweetcrumbsbakery.co.za/`, update the address in `sitemap.xml`, `robots.txt` and the `canonical`/`og:url`/`og:image` tags, then record the live URL below.
5. Test every navigation link, product search and filters, image lightbox, both forms, the map, desktop/tablet/mobile layouts and the browser console.

**Live website URL:** _add the deployed link here_
**GitHub repository URL:** _add the repository link here_

## Changelog

### Part 3 — October/November 2026
- Added a separate Contact page and linked it in the navigation and footer on all pages.
- Added page-specific SEO titles, descriptions, keywords, canonical links, robots and Open Graph metadata, a favicon and structured data.
- Added JavaScript product search, category filters and a live result count.
- Added a clickable image gallery and accessible lightbox with keyboard support.
- Added FAQ accordion sections to the Home page.
- Added an interactive Leaflet/OpenStreetMap map to the Contact page.
- Added JavaScript form validation with inline error messages, and email preparation for the Enquiry and Contact forms.
- Added CSS transitions, scroll reveal effects, reduced-motion support, focus states and a skip link.
- Added `robots.txt` and `sitemap.xml`.

### Part 3 — final corrections
- Renamed all pages to lowercase `.html` and updated every internal link, the sitemap and this README so links work on GitHub Pages and Netlify.
- Fixed the phone number pattern, which was invalid in modern browsers.
- Fixed the prepared email so line breaks and special characters appear correctly.
- Replaced basic browser validation with custom JavaScript validation and clear messages.
- Added phone, location, business hours and social media links to the Contact page and removed the "example only" map wording.
- Made each page's title its single `h1` and turned the site name into a paragraph.
- Added width/height, corrected `srcset` widths and lazy loading for images.
- Darkened the pink used for buttons and the tagline to improve text contrast.
- Grouped the contact-method radio buttons in a `fieldset`.
- Applied the proposal's Poppins heading font.

### Part 2 corrections carried forward
- Kept the shared external stylesheet and responsive grid layouts.
- Kept responsive image variants and internal navigation corrections.
- Specific lecturer feedback for Part 2 was not available for this update. Add any actual feedback items here if your lecturer supplied them.

## References
- Mozilla Developer Network (MDN) (n.d.) *HTML forms*. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms (Accessed: 28 October 2026).
- Mozilla Developer Network (MDN) (n.d.) *JavaScript*. Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript (Accessed: 28 October 2026).
- Mozilla Developer Network (MDN) (n.d.) *The viewport meta tag*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag (Accessed: 28 October 2026).
- Leaflet (n.d.) *Leaflet — a JavaScript library for interactive maps*. Available at: https://leafletjs.com/ (Accessed: 28 October 2026).
- OpenStreetMap contributors (n.d.) *OpenStreetMap*. Available at: https://www.openstreetmap.org/ (Accessed: 28 October 2026).
- Google Fonts (n.d.) *Poppins*. Available at: https://fonts.google.com/specimen/Poppins (Accessed: 2 November 2026).
- Schema.org (n.d.) *Bakery*. Available at: https://schema.org/Bakery (Accessed: 2 November 2026).

## Commit history
Record the actual commit hashes and dates from your GitHub repository after committing. Do not invent commit hashes.
