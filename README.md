# Science in Motion — Website Package v4

This package contains the updated bilingual website for **Science in Motion**.

## New in v4
- Fixed the broken **Movement Analysis** image with the newly uploaded image.
- Upgraded the **Blog & Insights** section so it is easier to manage.
- Added **3 extra blog cover images**.
- The blog is now driven by a `blogPosts` array in `script.js`.
- Supports image posts and can also support **YouTube / Vimeo embeds** by adding an `embed` URL.
- Added a more premium visual treatment to the blog section.

## How to update blog content
Open `script.js` and find: `const blogPosts = [...]`

Each item has:
- `type`
- `image`
- `link`
- `embed`
- `el.title`, `el.text`
- `en.title`, `en.text`

### To add a video embed
Replace:
```js
embed: ""
```
with a valid embed URL, for example a YouTube embed link.

## What to upload to GitHub
Upload the **contents** of `scienceinmotion_site_v4/` to the root of your repository:
- `index.html`
- `styles.css`
- `script.js`
- `README.md`
- `assets/`

## GitHub Pages
Then enable:
`Settings → Pages → Deploy from a branch → main → /root`
