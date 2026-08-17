# Wenhao Software

A lightweight static software-download website featuring EasyY2H.

## Current release

- EasyY2H 1.5.0
- Windows 64-bit portable ZIP
- Download size: 86.3 MB
- SHA-256: `AD2582D83535A193B264E45D9535DF6137627EE855CCF6F65837D5F7879413DC`

The download button uses the verified public EasyY2H download hosted at
`wenhao-software.zwh961550678.chatgpt.site`. The large software archive is
therefore not duplicated in this repository.

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
