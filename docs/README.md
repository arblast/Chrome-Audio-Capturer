## Chrome Audio Capturer

### Background

This Chrome extension will allow users to capture any audio playing on the current active tab and save the audio into a file.


### Functionality & MVP

With this extension, users will be able to:

- [ ] Have a basic interface to start and stop capturing audio
- [ ] Download the resulting file to the chrome Downloads folder
- [ ] Able to see an indication to see whether or not a capture is happening

### Wireframes

![Wireframe](/docs/AudioCapture.png)

### Technologies & Implementation

This extension will be implemented using the standard Chrome extension technology: Javascript, HTML, and CSS. There will be a `manifest.json` and `package.json` as with every extension. In addition, there will be two scripts for handling the logic of the extension:

-`capture.js`: will handle the logic for capture the audio from the chrome tab.
-`save.js`: will handle the logic for saving the audio files on the hard drive or cloud.

To display the menu and content, there will be two files:

- `menu.html`: the file that renders and displays the menu for audio capturing.
- `menu.css`: the file that contains css for the menu.

### Implmentation Timeline

**Day 1**: Learn the basics of how to create a chrome extension and have the basic files and structure of the program completed. (`package.json` and `manifest.json`)

**Day 2**: Work on the main menu of the extension and all the visual displays that is necessary for the extension to function properly. By the end of the day, I will have:

- A visually-appealing menu with buttons that will link to functions of the extension

**Day 3**: Work on getting the audio capture to work. By the end of the day, I will have:

- A way to capture audio into some kind of data that is stored in the browser temporarily
- A way to display the current status of the capture

**Day 4**: Work on turning the audio data into a file that can be saved on the computer. By the end of the day, I will have:

- A way to convert the audio data into a common audio format such as .wav or .mp3
- A way to save this file on the computer or cloud
