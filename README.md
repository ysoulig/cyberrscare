# Red and Black Cyber // Bento Template

A dark, editorial, bento-box landing page featuring custom cyberpunk anime graphics, an interactive audio player, tab-switching navigation, and a live signal guestbook. Designed for personal portfolios, character lores, and aesthetic link hubs.

---

## File Structure

your-template-folder/
├── index.html       # The complete website (HTML, CSS, and JS all in one file)
└── README.md        # Setup guide and instructions

---

## Quick Start Guide

### Step 1: Open the Code
1. Download or clone this folder.
2. Open index.html using any code editor (VS Code, Sublime Text, Notepad++, etc.) or a plain text editor.

### Step 2: Customize Your Content
Inside index.html, look for comments marked with <!-- CHANGE THIS: ... -->. Everything is neatly grouped by section:

* Browser Tab Title: Find <title>...</title> near the top to change the browser tab name.
* Header & Titles: Look for .header-title and .header-sub to change the main display name and tagline.
* Updating Links & Socials: Look inside the tab sections (id="tab-dossier", id="tab-comms", etc.) to update button text and destination handles.

### Step 3: Test Locally
Double-click your index.html file to open it instantly in any web browser (Chrome, Safari, Firefox, Edge). Click through the tabs, test the copy-to-clipboard buttons, and check out the layout live.

---

## Changing Colors & Theme

To tweak the color palette (e.g., swapping the crimson red accent for purple or steel blue), look at the :root variables at the very top of the <style> block in index.html:

:root {
  --bg-void: #060607;          /* Outer page background */
  --bg-panel: #0d0d0f;         /* Box background */
  --accent-crimson: #9e1b29;   /* Primary accent border/button color */
  --accent-crimson-bright: #d92638; /* Highlight / hover state color */
}

Simply paste your preferred Hex color codes into those variables, and the entire template will update automatically.

---

## How to Publish & Host for Free

You can host this site for free in under 2 minutes:

1. GitHub Pages: Create a public GitHub repository, upload your index.html file, go to your repository Settings > Pages, and set the source branch to main. Your site will go live instantly.
2. Netlify Drop: Drag and drop your project folder onto Netlify Drop (https://drop.netlify.com/), and it will give you a live shareable URL right away.
