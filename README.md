# Ms. Donna L. Murphy Retirement Ceremony Landing Page

This folder is ready to upload to a GitHub repository for GitHub Pages.

## Files included
- `index.html` - main landing page
- `styles.css` - page styling

## Current event details on the page
- Honoree: Ms. Donna L. Murphy
- Date: Monday, 01 June 2026
- Time: 1330 - 1600
- Ceremony start: 1400
- Location: Herbert Hall, Top Floor, Association of Graduates Building
- Uniform: Military - Duty Uniform; Civilian - Business Casual
- RSVP deadline: Thursday, 14 May 2026
- RSVP form: https://forms.office.com/r/74NeGQ11FC

## Upload to GitHub
1. Create a new repository in GitHub.
2. Upload `index.html` and `styles.css` to the repository.
3. Commit the files.
4. In the repository, go to **Settings** > **Pages**.
5. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
6. Save.
7. GitHub will publish the page and give you the website link.

## To make future edits
### Update ceremony text
Open `index.html` and change the text in these sections:
- Hero title and subtitle
- Event Details
- Schedule
- RSVP section

### Change colors or fonts
Open `styles.css`.
- Main colors are near the top inside `:root`
- Fonts are loaded in the `<head>` section of `index.html`

### Change the RSVP link
In `index.html`, find this line and replace the link:
```html
<a class="button secondary" href="https://forms.office.com/r/74NeGQ11FC" target="_blank" rel="noopener noreferrer">
```

## Notes
- This is a static site, so it works well with GitHub Pages.
- The page is mobile-friendly.
- No extra software or build tools are required.
