# 📚 Webnovel Vault

A self-hosted, multi-novel reading site built for GitHub Pages.

## Folder Structure
```
webnovel-vault/
├── index.html           ← Homepage (novel grid)
├── library.json         ← Master list of all novels
├── novels/              ← One .json + .html per novel
│   └── novel-id.json
│   └── novel-id.html
└── chapters/            ← Chapter pages per novel
    └── novel-id/
        └── chapter-001.html
```

## Setup
1. Create a public GitHub repo
2. Upload all files keeping the structure above
3. Go to Settings → Pages → Deploy from branch → main / root
4. Done — live at `https://YOUR-USERNAME.github.io/REPO-NAME`

## Adding a Novel
1. Click **+ New Novel** on the homepage
2. Fill in details → click **Generate Files**
3. Copy and upload the 3 generated files to GitHub
4. Commit → live in ~30 seconds

## Adding a Chapter
1. Open the novel's info page
2. Click **+ Add Chapter**
3. Paste your translated text → click **Generate Files**
4. Copy and upload the 3 generated files to GitHub
5. Commit → live in ~30 seconds
 
