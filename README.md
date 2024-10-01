# Text to Speech Converter

A simple and responsive web-based Text to Speech (TTS) converter. This application allows users to type text into a text area and convert it to speech using different available voice options.

## Features

- Convert typed text into speech with the click of a button.
- Select from multiple voices available on the user's device.
- Responsive design, compatible with different screen sizes.
- Simple and user-friendly interface.

## File Structure

```bash
├── index.html               # Main HTML file
├── styles.css               # CSS file for styling
├── script.js                # JavaScript logic for speech synthesis
```

## How to Use

1. Open the **index.html** file in your browser.
2. Type any text in the textarea field.
3. Select a voice from the dropdown menu if available.
4. Click the **Listen** button to hear the text spoken aloud.

## Notes

- The voices available in the dropdown depend on the browser and device used.
- Make sure your browser supports the Web Speech API for full functionality.

## Browser Support

- **Google Chrome**: Full support.
- **Mozilla Firefox**: Partial support (no onvoiceschanged event).
- **Safari**: Full support.
- **Edge**: Full support.
