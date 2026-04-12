# birthday-archive

A small AO3/Tumblr-inspired birthday gift page built as a single static HTML file.

## Files

- `index.html` — the main page
- `images/` — put your commissioned artwork here

## Image filenames

The page currently expects these files:

- `images/art-1.jpg`
- `images/art-2.jpg`
- `images/art-3.jpg`
- `images/art-4.jpg`
- `images/art-5.jpg`

If your files use different names or extensions, update the `<img src="...">` paths in `index.html`.

## Text placeholders to replace

Search for and replace these in `index.html`:

- `[her name here]`
- `[birthday date]`
- `put your first caption here`
- `put your second caption here`
- `put your third caption here`
- `put your fourth caption here`
- `put your final caption here`

You should also replace the placeholder curator notes with your own memory-lane text.

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, choose:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Save.
5. Wait a minute or two for the site to publish.

Your site URL should then be:

`https://codexprofit.github.io/birthday-archive/`

## Suggested next edits

- Add the commissioned images to `images/`
- Personalize the captions and curator notes
- Change the byline text if you want it less jokey
- Replace any placeholder text before sending the link
