# Put this site on GitHub Pages

Your GitHub repository is `mkmcdon/mkmcdon.github.io`.

## Easiest upload method
1. Open the repository in GitHub.
2. Open the **main** branch.
3. Upload the contents of this folder so that `index.html` is at the **root** of the repository.
4. Keep the included `CNAME` file. It should contain `www.turnkeyelectricaldesign.com`.
5. Commit the changes.
6. GitHub Pages should publish the new site automatically.

The resulting repository should look roughly like:

```text
CNAME
README.md
START-HERE.md
index.html
css/
  style.css
js/
  main.js
images/
  turnkey-key.png
  logo-source.png
```

## Updating images later
Put your replacement image in `images/` and update the corresponding image reference in `index.html` or CSS. We can also simplify this further later by creating a small image/config area specifically for routine edits.

## Current design note
The site uses the key-shaped PCB mark from the provided logo as a temporary clean web mark, while the wordmark is rendered as text so it says **TURNKEY ELECTRICAL DESIGN**. This keeps the brand aligned with the business name while leaving room to refine the formal logo later.
