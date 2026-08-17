# Wenhao Software

A lightweight static software-download website featuring EasyY2H.

## Current release

- EasyY2H 1.5.0
- Windows 64-bit portable ZIP
- Download size: 86.3 MB
- SHA-256: `AD2582D83535A193B264E45D9535DF6137627EE855CCF6F65837D5F7879413DC`

The release archive is stored at
`downloads/EasyY2H-v1.5.0-Windows-x64-portable.zip`, so the download button
uses a relative URL and does not depend on another website.

## Upload this repository

The EasyY2H archive is 86.3 MB. GitHub's browser uploader accepts only files up
to 25 MiB, so upload this package with GitHub Desktop or Git on the command
line. The archive is below GitHub's 100 MiB command-line file limit.

## Deploy on Netlify from GitHub

1. Upload all files from this package to the root of a GitHub repository.
2. In Netlify, choose **Add new project** and import the repository.
3. Netlify will use `netlify.toml`; no build command is required.

After this one-time connection, every commit pushed to the production branch
(normally `main`) triggers a new Netlify deployment automatically.

## Update the page

Edit `index.html` for software details and `styles.css` for presentation.
When a new release is available, update the version, size, checksum, and
download URL together.
