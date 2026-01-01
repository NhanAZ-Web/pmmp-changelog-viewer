# PocketMine-MP Changelog Viewer

Static web application for viewing and searching PocketMine-MP changelogs. Hosted on GitHub Pages.

**Live:** [https://nhanaz.github.io/pmmp-changelog-viewer/](https://nhanaz.github.io/pmmp-changelog-viewer/)

## Features

- Responsive design for desktop and mobile
- Search functionality with filtering
- Shareable links via URL parameters
- Search history
- Expandable/collapsible version groups

## Automated Updates

Changelogs are automatically updated daily from the official PocketMine-MP repository via GitHub Actions:

- Daily sync at 00:00 UTC
- Manual trigger available
- Automatic deployment to GitHub Pages

## Development

### Local Setup

```bash
npm install
npm start
```

### Project Structure

```
├── index.html          # Main HTML file
├── css/               # Stylesheets
├── js/                # JavaScript modules
│   ├── app.js        # Application entry point
│   ├── config.js     # Configuration
│   ├── search.js     # Search functionality
│   ├── versions.js   # Version management
│   └── render.js     # Markdown rendering
└── changelogs/        # Changelog markdown files
    ├── versions.json # Version list
    └── summary.md    # Changelog summary
```

## Technologies

- Bootstrap 5
- Marked.js
- highlight.js

## License

MIT
