# Ugray Consulting Website Revert Plan

This file documents the plan and checklist for reverting the local website files to match the current live version at https://ugrayconsulting.com.

## Steps

1. Overwrite local index.html with the HTML from the live site.
2. Overwrite all images in /images/ with the versions from the live site.
3. Overwrite any other assets (CSS, JS, PDFs) if they differ from the live site.
4. Test the site locally to ensure it matches the live version visually and functionally.

## Notes
- The local index.html and images/ directory already appear to match the live site based on a comparison of structure and filenames.
- If you want to ensure a perfect match, download each image and asset from the live site and overwrite the local versions.
- If you want to automate this, use a website downloader tool (like wget or HTTrack) to mirror the live site, then copy the files into your local workspace.

## Checklist
- [ ] index.html matches live site
- [ ] All images in /images/ match live site
- [ ] css/styles.css matches live site
- [ ] js/main.js matches live site
- [ ] PDFs in Blog and Resources/ match live site
- [ ] Manual visual check complete

---

If you want me to overwrite your local files with the exact HTML and asset references from the live site, please confirm and I will proceed with the changes.