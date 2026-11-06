# Marketing-Calendar-V1

A standalone, single-page planning app for GitHub Pages.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example `weston-marketing-planner`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub to publish the site. The URL will be shown in the Pages section.

## Included
- Monthly and weekly calendar
- Drag-and-drop ideas and scheduled items
- Campaigns with start/end dates and a campaign timeline
- Social posts and general marketing activity
- Image upload and image URL support
- Search/filter for unscheduled ideas
- Schedule list
- Excel export (two worksheets: Schedule and Calendar overview)
- JSON backup and restore

## Data and privacy
This version saves data in the browser's local storage on the device/browser where it is used. It does not sync between devices or browsers. Use **Backup data** regularly and keep the JSON backup somewhere safe. Imported image files are stored in browser storage too; very large images may exceed browser storage limits.

The Excel export uses SheetJS from a CDN. If that library is unavailable, the app fall
