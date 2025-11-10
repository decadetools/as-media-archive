# Autoškola Media Archive

This repository hosts the latest app ZIP file for public download via GitHub Releases.  
The actual app source code is stored elsewhere.

## Purpose

- Provide a public download link for the app
- Use GitHub Releases for free CDN hosting
- Keep a single place to fetch the newest version

## Download Link

Always use this link (automatically points to the latest release):

```
https://github.com/decadetools/as-media-archive/releases/latest/download/autoskola-media.zip
```

## How to Upload a New Version

### Via Web UI

1. Go to [Releases](https://github.com/decadetools/as-media-archive/releases/new)
2. Click **Draft a new release**
3. Enter:
   - **Tag version:** `v1.1` (or next version)
   - **Title:** Brief description
   - **Description:** What's new (optional)
4. Drag `autoskola-media.zip` into the upload area
5. Click **Publish release**

### Via Command Line

```bash
gh release create v1.1 autoskola-media.zip -t "App update" -n "Description"
```

## Notes

- File size limit: 2 GB per ZIP
- Free CDN hosting with global distribution
- Don't commit large files to Git — use Releases only
- Keep version tags consistent (v1.0, v1.1, v1.2, etc.)
