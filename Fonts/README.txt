# Tom's Font Vault

Put `index.html` in your GitHub Pages repo.

Expected setup:

Fonts/
├── fonts/
│   ├── index.html
│   ├── EagleLake.ttf
│   ├── OpenDyslexic-Regular.ttf
│   └── whatever.otf

Then open:

https://tprivitor.github.io/Fonts/fonts/

If your repo, branch, or folder names are different, edit this section inside index.html:

const GITHUB_USER = "tprivitor";
const REPO_NAME = "Fonts";
const FONT_FOLDER = "fonts";
const BRANCH = "main";

This page automatically reads the files in the GitHub repo folder through the GitHub API, so you do NOT need to edit the HTML every time you add a font.
