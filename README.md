# Meditation-web-app

Overview
This is a simple web-based Audio App that allows users to play audio with a synchronized video background. Users can select different audio and video combinations and set a timer for the playback duration.

Features
Timer Options: Choose between 2, 5, or 10 minutes for the audio and video playback.
Audio and Video Synchronization: The app plays selected background audio along with a looping video.
Sound Picker: Switch between different ambient sounds like rain or beach waves.
Custom Controls: Play, pause, and replay functionality is integrated with custom SVG controls for a modern look.
File Structure
index.html: The main HTML file for the app structure and layout.
style.css: Contains all the styles for the app.
app.js: The main JavaScript file responsible for app logic and interaction.
sounds/: A folder containing the different audio files (rain.mp3, beach.mp3).
video/: A folder containing the video files (rain.mp4, beach.mp4).
svg/: SVG images used for the control buttons (play, pause, replay, sound icons).
How to Use
Clone the Repository: Clone this project to your local machine.

bash
Copy code
git clone <repository-url>
Open the Project: Open index.html in any web browser.

Select Timer: Choose a playback duration by selecting one of the buttons (2, 5, or 10 minutes).

Pick Audio: Use the buttons at the bottom of the app to select different ambient sounds and matching videos.

Play Audio: Press the play button to start the audio and video. The track outline will animate to show the time left.

Technologies Used
HTML5
CSS3
JavaScript
SVG for custom controls
Google Fonts (Montserrat)
Future Enhancements
Add more ambient sounds and videos.
Include volume controls.
Add a progress bar for visual representation of time elapsed.
