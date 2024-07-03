# Spotify Clone Project

## Overview

This project is a Spotify-inspired music streaming application designed to provide users with a seamless and interactive music listening experience. While not an exact clone, it incorporates many key features of Spotify, including custom audio playback controls, dynamic playlist management, and an intuitive user interface.

## Features

- **Custom Audio Player**: Utilizes the `Audio` object in JavaScript to handle music playback with custom controls.
- **Dynamic Playlists**: Automatically loads and displays songs from a server, allowing users to easily browse and play their favorite tracks.
- **SVG Icons**: Employs scalable vector graphics (SVGs) for play, pause, and volume control buttons to enhance the visual appeal of the user interface.
- **Formatted Time Display**: Provides a user-friendly display of the current playback time and total duration of the track.
- **Album Art**: Checks for and displays album art when available; otherwise, defaults to a generic music icon.
- **Interactive Elements**: Includes a seek bar for navigating through songs and a responsive slider for volume control.
- **Library Integration**: Fetches songs from folders in the library, allowing users to organize their music collections efficiently.

## Project Structure

### HTML

The HTML structure includes the left sidebar, main content area, and playbar at the bottom. Here's an overview of the main sections:

#### Left Sidebar

- **Close Button**: Allows users to close the sidebar.
- **Navigation Links**: Includes links to Home and Search pages.
- **Library Section**: Contains buttons for Your Library and Add Playlist.
- **Footer Links**: Provides links to legal, privacy, and accessibility pages.

#### Main Content

- **Header**: Contains the hamburger menu, navigation arrows, and sign-up/log-in buttons.
- **Main Sections**:
  - **Playlist Container**: Displays the user's playlists.
  - **Artist Container**: Shows popular artists with play buttons and artist details.

#### Playbar

- **Seekbar**: Shows the current playback progress and allows users to seek through the song.
- **Control Buttons**: Includes play, pause, next, and previous buttons.
- **Volume Control**: Allows users to adjust the volume.
- **Time Display**: Shows the current time and total duration of the song.

### CSS

The project uses two CSS files:
- **utility.css**: Contains utility classes for common styles.
- **sportify.css**: Contains specific styles for the Spotify clone.

### JavaScript

The `sportify.js` file contains the JavaScript code to handle audio playback, dynamic content loading, and user interactions.
