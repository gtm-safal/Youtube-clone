# YouTube Clone Webpage

## Overview
This project is a front-end implementation of a simplified YouTube-like user interface using HTML and CSS. It features a classic YouTube-style layout including:

- A **header** with navigation elements such as hamburger menu, logo, search bar, voice search, upload, notifications, and user profile.
- A **sidebar** with primary navigation links (Home, Explore, Subscriptions, Originals, YouTube Music, Library).
- A **video grid** displaying video previews with thumbnails, video duration, channel pictures, titles, authors, and view stats.

## Features
- Responsive and organized layout structured with semantic HTML.
- Integration of Google Fonts (`Roboto`) for clean typography.
- Modular CSS architecture with separate stylesheets for general, header, video, and sidebar styles.
- Use of SVG icons and local image assets for a visually consistent interface.
- Video previews include metadata like views and upload age, mimicking a real YouTube experience.

## Project Structure
```
/Icons/                # SVG icons used in header and sidebar
/Thumbnails/           # Video thumbnail images
/Channel Pictures/     # Channel profile pictures
/Styles/               # CSS stylesheets
  general.css
  header.css
  video.css
  sidebar.css
index.html             # Main HTML file
```

## How to Use
1. Clone or download this repository.
2. Make sure all referenced assets (images, icons, CSS) are correctly placed in their folders.
3. Open `index.html` in any modern web browser to view the webpage.
4. Customize videos, icons, or styling by modifying the respective folders and CSS files.

## Technologies Used
- HTML5
- CSS3
- Google Fonts (Roboto)

## Future Enhancements
- Add JavaScript functionality for search, voice input, and dynamic notifications.
- Make the layout fully responsive for mobile and tablet devices.
- Implement video playback and interaction.
- Integrate APIs to load real YouTube data dynamically.
