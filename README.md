# JAX & KING — Website

The official website for **JAX & KING**, La Jolla's award-winning hair salon.

🌐 **[View the live website →](https://walksalot.github.io/jax-and-king-website/)**

---

## About JAX & KING

JAX & KING is an intimate, design-forward salon set inside a charming La Jolla beach bungalow on Herschel Avenue. Founded by Jaylin Seng and Paul Miller, the studio specializes in customized color, Hollywood highlights, balayage, precision cuts, and extensions.

- 📍 **7861 Herschel Avenue, La Jolla, CA 92037**
- 📞 **(858) 459-5464**
- 📧 **jaxandking@gmail.com**
- 📸 [@jaxandking](https://www.instagram.com/jaxandking/)

---

## How to Edit This Website

This is a single HTML file (`index.html`) — everything lives in one place: the layout, styling, and interactive behavior. You don't need to install anything special to edit it.

### Option 1: Edit with Claude Code (Recommended)

[Claude Code](https://docs.anthropic.com/en/docs/claude-code) is a command-line tool that lets you describe changes in plain English and have AI make them for you. It's the easiest way to update this site without knowing how to code.

**Getting started:**

1. **Install Claude Code** (one-time setup):
   - Open the **Terminal** app on your Mac (search for "Terminal" in Spotlight)
   - Paste this command and press Enter:
     ```
     npm install -g @anthropic-ai/claude-code
     ```
   - If you don't have `npm`, you'll need to install [Node.js](https://nodejs.org/) first (download the LTS version and run the installer)

2. **Download this website to your computer:**
   - Click the green **"Code"** button at the top of this GitHub page
   - Click **"Download ZIP"**
   - Unzip the downloaded file — you'll get a folder called `jax-and-king-website`

3. **Open the project in Claude Code:**
   - In Terminal, navigate to the folder:
     ```
     cd ~/Downloads/jax-and-king-website
     ```
   - Start Claude Code:
     ```
     claude
     ```

4. **Tell Claude what to change!** Just describe what you want in plain English. Examples:
   - *"Change the phone number to (858) 555-1234"*
   - *"Add a new service card for Men's Grooming"*
   - *"Change the gold color to a deep teal"*
   - *"Add a photo gallery section with placeholder images"*
   - *"Update the hours — we're now closed on Sundays"*
   - *"Add an online booking link that goes to our Vagaro page"*
   - *"Make the testimonial section show 4 reviews instead of 3"*

   Claude will make the edits to the HTML file for you. You can preview the changes by opening `index.html` in your browser.

### Option 2: Edit Directly in GitHub

1. Click on `index.html` in the file list above
2. Click the **pencil icon** (✏️) to edit
3. Make your changes
4. Click **"Commit changes"** to save

The live website will update automatically within a minute or two.

### Option 3: Edit Locally with Any Text Editor

1. Download the ZIP (green "Code" button → "Download ZIP")
2. Open `index.html` in any text editor (TextEdit, VS Code, Sublime Text, etc.)
3. Make changes and save
4. Open the file in your browser to preview

---

## Quick Reference: What's Where in the Code

The `index.html` file is organized into clear sections you can search for:

| Section | What to search for | What it controls |
|---|---|---|
| **Navigation** | `<!-- NAV -->` | Top menu bar and "Book Now" button |
| **Hero** | `class="hero"` | The big landing section with the salon name |
| **Credentials** | `class="credential-bar"` | "Award Winning · As Seen on E!" bar |
| **About** | `<!-- ABOUT -->` | Studio description and stats |
| **Services** | `<!-- SERVICES -->` | The 4 service cards |
| **Reviews** | `<!-- TESTIMONIALS -->` | Client testimonials |
| **Hours** | `<!-- HOURS & LOCATION -->` | Business hours and map |
| **Call to Action** | `<!-- CTA -->` | "Your best hair starts here" section |
| **Footer** | `<!-- FOOTER -->` | Bottom of page with social links |
| **Colors** | `:root {` | All the color values (gold, black, cream, etc.) |

---

## Updating the Live Website

Any changes committed to this repository will automatically update the live site at:

**https://walksalot.github.io/jax-and-king-website/**

Changes typically take 1–2 minutes to appear.

---

*Built with ❤️ using [Claude](https://claude.ai)*
