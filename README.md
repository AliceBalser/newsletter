# Newsletter Studio

A single-file personal newsletter and journal timeline for GitHub Pages.

## Publish on GitHub Pages

1. Create a new GitHub repository named something like `newsletter`.
2. Put `index.html` and this `README.md` in that repository.
3. In GitHub, open the repository settings.
4. Go to **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/root`, then save.

GitHub will give you a public URL after the first deploy finishes.

## Use It

- The page opens to a login screen.
- Guest can view and download newsletters.
- Admin can add, edit, delete, download, change timeline/settings theme colors, and set newsletter-specific page/text colors.
- The page opens to a timeline of saved newsletter issues.
- Use **Add New** to open the writing space.
- Write directly in the newsletter body.
- Use the component buttons for journal sections, links, lists, photo notes, quotes, and sign-offs.
- Add line, dot, or space breaks, move selected blocks up/down, and change a section font from the editor.
- Edit the title, kicker, date, and intro in the left panel.
- Drafts and timeline entries save automatically in the current browser.
- Use the gear button to change the app theme colors.
- Use **Download** to export a clean published version.

GitHub Pages is static hosting, so browser autosave is local to the device you are using.

The login is client-side because GitHub Pages is static hosting. It controls the page experience, but it is not strong security because the passwords are still present in the page source.
