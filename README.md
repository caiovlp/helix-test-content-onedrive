# Test content for Helix Pages

This repo defines content for an [Helix Pages](adobe/helix-pages) project and it is used in the context of Helix-Pages smoke tests. It contains 3 branches: `main (default)`, `master` and `abranch` with some various combinations of content and static overrides. Branches are mounted to different Sharepoint and Google Drive folders in order to run tests against various setup:

- static html file
- Helix Pages static (`head.html`, `styles.css`) overrides
- md file + html file
- md file + html file + Sharepoint docx / Google Drive gdoc file
- md file + html file + Sharepoint docx / Google Drive gdoc file + Sharepoint md / Google Drive md file