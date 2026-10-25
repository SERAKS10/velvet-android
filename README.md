# Velvet — GitHub Pages build

## Included
- Live clock/date, graduation photo background, greeting
- Notes categories: Motivation Quotes, My 5-Year Plan, Bible Quotes, Movies/Series Quotes, Personal
- Add, edit, delete and search notes
- Birthday list with the supplied 16 birthdays and an add-birthday form
- Gallery with Family, Friends, Memories and Favourites folder filters
- X, LinkedIn, Facebook and TikTok links
- Credit Risk Model GitHub card, focus timer, web search and settings
- PWA manifest and service worker

## Important privacy note
You chose to make your photos and videos public. The media files in `assets/media/` and the graduation photo in `assets/lockscreen/` are included in this project. Anyone who can access a public GitHub Pages site may view or download them. HEIC images are included as uploaded but many browsers do not preview HEIC; convert them to JPG if you want universal browser support.

## Data behaviour
Notes and birthdays you add are stored in the current browser's local storage. They do not sync between devices. The starter notes and birthday names are in `index.html` and therefore visible in the public repository source.

## Deploy
Upload the *contents* of this folder to the root of your existing `velvet-android` GitHub repository, replacing the existing `index.html`, and add/replace `manifest.webmanifest`, `sw.js`, and the `assets` folder. Do not upload only the ZIP file. In GitHub Pages, the source should remain the repository branch/root already used by your working site.
