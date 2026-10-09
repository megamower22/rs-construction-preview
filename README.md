# RS Construction Concepts & Home Repair Services – preview website

This is a free preview website for **RS Construction Concepts & Home Repair Services** (La Crosse, WI), built by Hudson | Lacrosse Lawn & Landscape.
It is plain HTML and CSS: no build step, no monthly fees for hosting.

Live preview: https://megamower22.github.io/rs-construction-preview/

## How to change text on the site (on github.com)

1. Go to this repo on github.com and sign in.
2. Click **index.html**.
3. Click the **pencil icon** (Edit this file) at the top right of the file.
4. Find the words you want to change and type the new text. Only change the words between the tags, not the `<` `>` parts.
5. Scroll down (or click the green **Commit changes...** button), add a short note like "Update hours", and click **Commit changes**.
6. Wait about a minute, then refresh the website. Your change will be live.

## Good to know

- **Colors** are at the top of `style.css` (look for `--rasp`, `--eggplant` and `--butter`).
- **Fonts** come from Google Fonts: **Bungee** for headings and buttons, **Figtree** for body text (`--font-display` and `--font-body` in `style.css`).
- Anything in yellow highlight that says **[Owner to confirm]** still needs real info from the owner. Once it's confirmed, delete the whole `<span class="placeholder">...</span>` part.
- **Reviews:** the neighbor messages are inside `class="chat"`. Add more `bubble` blocks for new approved reviews.
- The phone number appears in several places. Search for `799-9306` (and `+16087999306` in the call links) to update all of them.
- The email appears in several places. Search for `casalocowalu@gmail.com` to update it.
- To remove the "Preview site" banner once the owner approves, delete the line with `class="preview-banner"` in `index.html`.
