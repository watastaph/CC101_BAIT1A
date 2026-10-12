# BAIT-1A · Score Lookup

Score lookup page for BAIT-1A (Dr. Ezekiel R. Borja).
Students enter their student number to see their midterm-period scores.

## Deploy on GitHub Pages

1. Create a new repository on GitHub (it can be private if your plan allows Pages for private repos; otherwise public).
2. Upload `index.html` and `.nojekyll` to the root of the repository (Add file → Upload files → Commit).
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Updating scores

Replace `index.html` with the new version and commit. The page updates within a minute or two.

## Notes

- The page is a single static file with no server or database.
- Each student's scores are stored encrypted inside `index.html` and unlocked with their student number, so names and scores are not readable in the source. Anyone who types a valid student number can see that student's scores.
- `noindex` is set so search engines don't list the page.
