# SmashWiiUSinglesOverlayStep1
Step 1 of a project to create a dynamically editable overlay for Super Smash Bros. Wii U Singles usable for any tournament streamers using HTML, CSS and C#.

How to use in Open Broadcaster Software (OBS Studio):
- Add a new Browser source to your scene.
- Check the Local file checkmark.
- Select gameOverlay.html of this project.
- Set the resolution and framerate (1920 x 1080 at 60 frames per second reccommended)
You are now ready to stream with the overlay.

As the streamed set(s) progress, you can update the overlay by changing
- player1NameText:before
- player2NameText:before
- #roundBoxText:before

at the bottom of styles.css

At this step, the overlay doesn't dynamically update whenever the css is altered, you have to move back and forward between the scene with the overlay and another scene to show an updated overlay.
