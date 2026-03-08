# Duxbury High School Student Council Website

This folder contains a simple, static website for the Duxbury High School Student Council, built with only HTML, CSS, and a small amount of JavaScript.

## Structure

- `index.html` – Home
- `about.html` – About & mission/constitution info
- `executive-board.html` – Executive Board, class leaders, and advisors
- `events.html` – Events and initiatives
- `contact.html` – Contact information
- `assets/css/styles.css` – Shared styles, layout, and colors
- `assets/js/main.js` – Small script for mobile navigation toggle and footer year
- `assets/img/` – Place any logo or photos here (not required for the site to work)

## Editing content

You can open any `.html` file in a text editor (or in Cursor) and edit the text directly. Look for:

- Names and roles on `executive-board.html`
- Event titles, descriptions, and `Date: TBD` text on `events.html`
- Mission text and constitution section on `about.html`
- Contact email and Instagram handle on `contact.html` and in the footer on all pages

### Colors and fonts

Colors and typography are defined in `assets/css/styles.css` at the top of the file:

- `--primary-color` – Kelly green-style primary color
- `--primary-dark` – Darker green for hover states
- `--secondary-color`, `--accent-color`, `--text-color`, `--background-color` – supporting colors

Update these values if you want to match official Duxbury colors exactly.

## How to view the site locally

1. Make sure this whole folder (for example `duxbury-stuco-site/`) stays together.
2. Double-click `index.html` or open it in your browser (Chrome, Edge, Safari, etc.).
3. Use the navigation links at the top to move between pages.

## How to give this to school IT

1. Zip the entire `duxbury-stuco-site` folder.
2. Send the zip file to your school IT contact or advisor.
3. Ask them to host it as a static website and give you the URL to share.

They only need to:

- Unzip the folder on a school web server.
- Make sure the folder is served so that `index.html` is the home page.

## Hosting with GitHub Pages (optional, student-managed)

If your school allows it, you can also host this via GitHub Pages:

1. Create a GitHub account (if you do not already have one).
2. Create a new public repository (for example `duxbury-stuco-site`).
3. Upload all files from this folder to the repository.
4. In the repository settings, enable **GitHub Pages** and select the `main` branch and `/ (root)` folder.
5. GitHub will give you a URL like `https://username.github.io/duxbury-stuco-site`.

You can then share that URL or later work with IT to point a custom school address to it.

