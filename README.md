# Neha Goyal — HTML and CSS Portfolio

This is my beginner-friendly portfolio website, created with plain HTML and CSS for my college assignment. It introduces me, shares the projects I completed during my course, and provides a link to my GitHub profile.

## Website sections

- **Home** — A friendly introduction and links to my projects and GitHub profile.
- **About** — A short description of my HTML and CSS learning journey.
- **Projects** — Four projects found in my course repository: Academy Cinemas, Explore Canada, Simple Recipes, and The Pet Shop.
- **Contact** — A styled practice form and a working link to my GitHub profile.
- **Footer** — Quick navigation, GitHub links, my `NG.` monogram, and a back-to-top link.

## Design features

- Navy, white, and teal colour palette
- Responsive layouts for desktop, laptop, tablet, and mobile screens
- Sticky navigation and smooth section scrolling
- Project cards with subtle hover effects
- Accessible form labels and clear keyboard focus styles
- Responsive three-column footer
- Reduced-motion support for visitors who prefer fewer animations
- Beginner-friendly comments throughout the HTML and CSS

## Files

- `index.html` contains the page structure and content.
- `portfolio.css` controls the colours, layout, hover effects, and responsive design.

## Preview the portfolio

Double-click `index.html` to open it in a web browser. Keep `index.html` and `portfolio.css` in the same folder so the styles load correctly.

## How the code is organised

The HTML uses semantic elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<form>`, and `<footer>`. The four main sections—Home, About, Projects, and Contact—each have an `id` that matches a navigation link. For example, `href="#projects"` moves the page to `id="projects"`.

The Projects section uses an `<article>` for each course project. The Contact section demonstrates labels, text inputs, an email input, and a message box. The footer groups related links so visitors can move around the page without returning to the navigation bar.

The CSS starts with reusable colour variables. Shared classes such as `.page-width`, `.section`, and `.button` avoid repeating the same rules. CSS Grid arranges the main columns and project cards, while Flexbox aligns navigation links, buttons, tags, and footer content. The media queries near the bottom stack columns and buttons on smaller screens.

## Practice exercise

1. In `index.html`, temporarily remove the line `<p class="eyebrow">Welcome to my corner of the web</p>`, save, and refresh the browser. The small label above the main heading should disappear. Restore the line and save again.
2. In `portfolio.css`, temporarily remove `background: var(--navy);` from the `.hero` rule, save, and refresh. The dark navy Home background should disappear. Restore the declaration and save again.

These are observation exercises only. The delivered files already contain both lines.

## About the contact form

The form is included for HTML and CSS practice, but its Send button is intentionally disabled. A static HTML/CSS page cannot deliver messages by itself, and no email address or form service was provided. Visitors can use the working GitHub contact link instead. If an email service or backend is added later, the form can be connected by adding its submission URL to the `<form>` element and enabling the button.

## Projects shown

The portfolio descriptions are based on work found in the [HTML and CSS course repository](https://github.com/NehaGoyal2296/HTML-and-CSS-Projects). No employment history, qualifications, or extra projects were invented.

1. **Academy Cinemas** — A responsive movie-theater page with film listings, showtimes, and deals.
2. **Explore Canada** — A one-page travel website with destination content, images, video, and navigation.
3. **Simple Recipes** — A recipe collection with cards, sticky navigation, and hover effects.
4. **The Pet Shop** — A multi-page pet website with category links, images, video, and a contact page.

## Publish with GitHub Pages

This portfolio is stored in the `portfolio` folder of the existing `HTML-and-CSS-Projects` repository.

1. Keep `index.html`, `portfolio.css`, and this `README.md` together inside the `portfolio` folder.
2. Commit the folder to the repository's `main` branch.
3. Open the repository's **Settings**, then select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. After GitHub finishes publishing, open:
   `https://nehagoyal2296.github.io/HTML-and-CSS-Projects/portfolio/`
7. Test the navigation and project links before submitting the live URL.

## Final checks before submission

- Confirm that `index.html`, `portfolio.css`, and `README.md` are together in the repository's `portfolio` folder.
- Open the live website and test the Home, About, Projects, and Contact links.
- Test the GitHub and course-project links.
- Check the page on both a desktop and a phone-sized screen.
- Copy the verified GitHub Pages URL for the assignment submission.

No stock image is included. The design uses a code sample as its visual focus, so it does not misrepresent a stock portrait as Neha.
