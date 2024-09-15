Welcome to the Spotify Clone project! This project aims to replicate the basic functionalities of Spotify's web player interface, allowing users to play, pause, and switch between songs.

Table of Contents
Features
Technologies Used
Project Structure
Installation & Setup
How to Use
Future Enhancements
Features
Play and pause songs with smooth animations.
Navigate through a list of songs in the "My Library" section.
Visual feedback while playing a song, including a progress bar and a playing GIF animation.
Forward and backward navigation between songs.
Responsive design and mobile-friendly layout using CSS Flexbox and media queries.
Technologies Used
HTML5: For creating the structure of the web pages.
CSS3: For styling the user interface, including responsive layouts and Flexbox.
JavaScript (ES6): For adding dynamic behavior to the music player, handling play/pause functionalities, progress bars, and song switching.
FontAwesome Icons: Used for adding interactive icons like play/pause buttons.
Google Fonts: For importing fonts to enhance the visual appeal.
Project Structure
The repository consists of the following files:

graphql
Copy code
Spotify Clone/
│
├── index.html          # Main HTML file for the structure of the page
├── style.css           # Main CSS file for styling the webpage
├── script.js           # JavaScript file for handling the audio player logic
├── songs/              # Directory containing MP3 files for the songs
│   ├── 1.mp3
│   ├── 2.mp3
│   └── ... (additional songs)
├── covers/             # Directory containing cover images for the songs
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ... (additional covers)
├── img/
│   └── logo.png        # Spotify logo image
└── sbg.jpg             # Background image for the main container
Installation & Setup
Follow these steps to set up the project on your local machine:

Clone the repository:

bash
Copy code
git clone https://github.com/vinitsittu/SpotifyClone.git
Navigate to the project directory:

bash
Copy code
cd SpotifyClone
Open the project in your browser:

Open the index.html file in your browser or use a live server extension (like Live Server for VSCode).

Add the necessary songs and cover images:

Ensure that you have the required audio files inside the songs/ directory (e.g., 1.mp3, 2.mp3, etc.).
Add cover images for each song inside the covers/ directory (e.g., 1.jpg, 2.jpg, etc.).
How to Use
Play a Song:

Click the play button on any song listed in the "My Library" section to start playing the song.
Pause/Play:

Use the central play/pause button or the one on the song list to control playback.
Navigate Between Songs:

Use the forward (⏭️) and backward (⏮️) buttons to switch between songs in the playlist.
Seek Through the Song:

Use the progress bar at the bottom to jump to different parts of the song.
Future Enhancements
Here are some features that could be added in the future:

Playlist Feature: Add the ability to create custom playlists and shuffle between songs.
Volume Control: Add volume adjustment controls.
Search Feature: Allow users to search for songs within the library.
Song Lyrics: Add an option to display song lyrics while playing.

