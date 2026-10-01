# Tyler Angerbauer Portfolio Website

This starter site is intentionally simple so you can maintain it without being an experienced coder.

## Files

- `index.html` — All of the words, links, project cards, and page sections.
- `styles.css` — Colors, fonts, spacing, sizes, and layout.
- `script.js` — Tiny optional JavaScript file. Right now it only updates the copyright year.
- `resume.pdf` — Put your resume PDF in this folder and give it exactly this name.
- `images/` — Create this folder and place photos/project thumbnails inside it.

## Easiest way to edit the site

### Option 1: Visual Studio Code
1. Download VS Code from https://code.visualstudio.com/
2. Open the `tyler_portfolio_site` folder.
3. Install the extension **Live Server**.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Your browser will automatically show the site.
6. Change text in `index.html`, save, and refresh the browser.

You do not need to understand everything in the HTML.

Look for obvious text such as:

    <h3>Baseball Play-by-Play</h3>

Change only the words between the opening and closing tags:

    <h3>YOUR NEW TITLE</h3>

## How to add an image

Create an `images` folder.

Then replace a placeholder like this:

    <div class="project-image placeholder-media">
      <span>BYUtv thumbnail</span>
    </div>

with:

    <img class="project-image" src="images/byutv.jpg" alt="Description of the image">

## How to change a link

Find:

    <a href="#" class="text-link">Watch project →</a>

Replace `#` with the actual webpage or video link:

    <a href="https://youtube.com/..." class="text-link" target="_blank">Watch project →</a>

## How to change colors

Open `styles.css`.

At the very top you will see:

    :root {
      --bg: #f5f3ee;
      --surface: #ffffff;
      --text: #111827;
      --muted: #5f6673;
      --accent: #174ea6;
      --dark: #0e1726;
    }

Those six values control nearly the entire color palette.

## Publishing

### Recommended: GitHub Pages
GitHub Pages is free and works well for a portfolio.

1. Create a GitHub account.
2. Create a new repository named `portfolio`.
3. Upload all website files.
4. Open Settings → Pages.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select your `main` branch and `/root`.
7. GitHub will give you a public website URL.

You can later connect a custom domain such as `tylerangerbauer.com`.

### Alternative: Netlify
For the easiest possible first publish:
1. Create a Netlify account.
2. Drag the entire website folder into Netlify's deployment area.
3. It publishes immediately.

Netlify is particularly simple if you don't want to learn GitHub yet.

## Recommended workflow

For now:

1. Edit in VS Code.
2. Preview with Live Server.
3. Keep all photos in `images/`.
4. Put your resume in the root folder as `resume.pdf`.
5. Publish with Netlify first.
6. Move to GitHub Pages later if you want version history and a more professional development workflow.

## Next step

Replace the placeholder content with:
- Your best headshot or broadcasting photo.
- 3–6 strongest projects.
- YouTube/Vimeo/article links.
- Your LinkedIn link.
- Your professional email.
- Resume PDF.

Once those are added, the portfolio can be expanded into separate Broadcasting, Production, and Writing pages.
