# SmashWiiUSinglesOverlayStep1

Not actively in development, use the Livestream Production Manager instead for the latest and greatest: https://github.com/Gogoku7/LivestreamProductionManager

Step 1 of a project to create a dynamically editable overlay for Super Smash Bros. Wii U Singles usable for any tournament streamer using HTML, JavaScript, CSS and C#.

**How to use in Open Broadcaster Software (OBS Studio):**
- Add a new Browser source to your scene.

![alt img](https://i.imgur.com/Pewt3lD.png)

- Check the Local file checkbox and click Browse.

![alt img](https://i.imgur.com/uYsFNKt.png)

- Select gameOverlay.html of this project.
- Set the resolution and framerate. (1920 x 1080 at 60 frames per second recommended)
- Check Refresh browser when scene becomes active checkbox.

![alt img](https://i.imgur.com/o7NIol0.png)

You are now ready to stream with the overlay.

As the streamed set(s) progress, you can update the overlay by changing
- #player1NameText:before (the name of player 1)
- #player2NameText:before (the name of player 2)
- #roundBoxText:before (the current round)

at the bottom of styles.css

At this step, the overlay doesn't dynamically update whenever the css is altered, you have to move back and forward between the scene with the overlay and another scene to show an updated overlay.
