# Spotify Clone

A static Spotify-inspired web UI built with HTML and CSS. This project recreates the look and feel of the Spotify web player, including the sidebar, content library, featured cards, and the bottom music player bar.

## Features

- Spotify-style dark theme layout
- Left navigation sidebar with library section
- Responsive content area with playlist and chart cards
- Fixed bottom player bar with playback controls
- Local image assets and external icon/font support

## Tech Stack

- HTML
- CSS
- Font Awesome for icons
- Google Fonts (Montserrat)

## Project Structure

```text
index1.html
style1.css
Assets/
```

## How to Run

1. Open `index1.html` in a browser.
2. Make sure the `Assets` folder stays in the same directory as the HTML file.
3. The page loads the stylesheet from `style1.css` and uses external CDN links for icons and fonts.

If you want to serve it locally from the project folder, use:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/index1.html` in your browser.

## Notes

- This is a front-end clone only; there is no JavaScript playback logic yet.
- The current layout is designed for desktop-sized screens and includes a fixed bottom player.
- Asset names such as `card1img.jpeg`, `backward_icon.png`, and `forward_icon.png` must remain unchanged unless the HTML is updated accordingly.
