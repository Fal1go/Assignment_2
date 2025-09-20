# Copilot Instructions for AI Coding Agents

## Project Overview
This project is a simple static website, primarily focused on HTML and CSS. It includes a main landing page and a tribute page for Tom Ellis, with associated images and styles.

## Structure
- `index.html` and `style.css`: Main site entry point and global styles.
- `exercise1/index.html`: Tribute page for Tom Ellis.
- `exercise1/tribute_style.css`: Styles specific to the tribute page.
- `exercise1/Photos/`: Contains images used in the tribute page.

## Key Patterns & Conventions
- All HTML files use semantic HTML5 structure (header, main, footer, etc.).
- CSS is separated by page/function: `style.css` for the main site, `tribute_style.css` for the tribute page.
- Images are referenced with relative paths from the HTML files (e.g., `Photos/Tom_Ellis_(2016).jpg`).
- No JavaScript or build tools are present; all files are static and manually managed.

## Developer Workflows
- **Previewing**: Open HTML files directly in a browser to view changes. No build or test commands are required.
- **Styling**: Edit CSS files directly; changes are reflected on page reload.
- **Adding Images**: Place new images in `exercise1/Photos/` and reference them with relative paths in HTML.

## Project-Specific Advice
- Maintain clear separation between global and page-specific styles.
- Use descriptive alt text for images for accessibility.
- Keep file and folder names simple and descriptive; avoid spaces except where required for image names.
- When adding new pages, follow the existing structure: create a new HTML file and, if needed, a dedicated CSS file.

## Examples
- To add a new tribute page:
  1. Create `exercise1/new_tribute.html`.
  2. Create `exercise1/new_tribute_style.css` if custom styles are needed.
  3. Add images to `exercise1/Photos/`.
  4. Reference the new page from the main `index.html`.

## Integration Points
- No external dependencies or frameworks are used.
- All integration is via static file references (HTML/CSS/images).

---
For questions or unclear conventions, review existing HTML/CSS files for examples or ask for clarification.
