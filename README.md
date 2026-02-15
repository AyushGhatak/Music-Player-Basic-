# Web Music Player 

A fully functional browser-based music player developed using pure HTML, CSS, and vanilla JavaScript — without any external libraries or APIs. <br>
The player implements advanced playback features and dynamic UI updates using the native HTML5 <audio> element.

🔗 Live Demo: [music-player-basic](https://ayushghatak.github.io/Music-Player-Basic-/)

 ## Features
* Play / Pause
* Next / Previous track
* Repeat mode
* Shuffle mode
* Volume slider
* Seek bar (jump to any timestamp)
* Click-to-play from playlist
* Dynamic album art switching
* Responsive design
* GitHub Pages deployment

## How It Works (No External APIs)
This music player is built using:
* Native HTML5 <audio> element
* Pure JavaScript for:
   * Playback control
   * Track switching
   * Shuffle logic
   * Repeat functionality
   * Seek bar synchronization
   * Volume adjustment
   * UI state updates

Note: No frameworks, no libraries, and no third-party APIs were used.

## Core Implementation Highlights

**🎵 Track Management** <br> 
Songs are stored in a JavaScript array.
Selecting a song dynamically updates:
* Audio source
* Song title
* Cover image
* Active track styling

**🔀 Shuffle Logic** <br>
Random index generation ensures non-sequential track selection.

**🔁 Repeat Mode** <br>
On ended event, the same track is replayed automatically when repeat is enabled.

**⏩ Seek Bar** <br>
Updates dynamically using timeupdate event.
Allows manual dragging to control currentTime

## Tech Stack
* HTML
* CSS
* Vanilla JavaScript

## Repository Structure
├── index.html <br>
├── player.html <br>
├── Welcome.css <br>
├── player.css <br>
├── player.js <br>
├── *.mp3 (audio files) <br>
├── *.jpg (cover images)

Note: This is a basic music player (web version)  demonstrating core frontend development concepts including DOM manipulation, event handling, and media control APIs.
