Screen Recorder(Zoom clone)

A simple screen recorder application built using HTML, CSS, and JavaScript. This application allows users to record their screen and capture screenshots with various filters.

Features:

Record screen video with audio disabled
Capture screenshots with various filters (orange, brown, pink, and transparent)
Timer display during recording
Download recorded video and captured images

Usage:

Open the application in a web browser.
Click on the record button to start recording the screen.
Click on the capture button to capture a screenshot with the selected filter.
Click on the record button again to stop recording.
The recorded video and captured images will be downloaded automatically.


Technical Details:

The application uses the MediaRecorder API to record the screen.
The getUserMedia method is used to access the user's screen.
The recorded video is stored in chunks and converted to a blob for download.
The captured images are created using a canvas element and filtered using CSS styles.


Code Structure
The code is organized into three main files:

index.html: The main HTML file that contains the application structure.
style.css: The CSS file that styles the application.
index.js: The JavaScript file that contains the application logic.

Acknowledgments
This application was built using the following resources:

MDN Web Docs

W3Schools
