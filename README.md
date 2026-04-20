# Media Player

A modern, feature-rich HTML/CSS/JavaScript media player for video and audio playback.

## Features

- **File Selection**: Select local video or audio files for playback
- **Drag & Drop**: Drag and drop media files directly into the player
- **Native Controls**: Uses browser's native media controls for playback, volume, seeking, and fullscreen
- **Dynamic Sizing**: Media automatically scales to fill 100% of width or height (whichever reaches 100% first) while maintaining aspect ratio
- **Keyboard Shortcuts**: Comprehensive keyboard controls for navigation and volume
- **Touch Gestures**: Full touch support for mobile devices with swipe and tap gestures
- **Double-Tap Fullscreen**: Double-tap on media to toggle fullscreen mode
- **Speed Toggle**: Click the Keyboard Shortcuts box to toggle playback speed between 2x and 4x
- **Auto-Hide UI**: File selection controls hide when media is loaded for a clean viewing experience
- **Keyboard Shortcuts Display**: Shows available shortcuts (hidden during playback, shown when paused)

## Usage

### Opening the Player

Simply open `MediaPlayer.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

### Loading Media

1. **File Selection**: Click "Select Media" and choose a video or audio file
2. **Drag & Drop**: Drag a media file and drop it onto the media container

### Controls

#### Keyboard Shortcuts

- **← (Left Arrow)**: Back 10 seconds
- **→ (Right Arrow)**: Forward 30 seconds
- **↑ (Up Arrow)**: Volume up (+10%)
- **↓ (Down Arrow)**: Volume down (-10%)
- **Space**: Pause/Resume
- **F**: Toggle Fullscreen

#### Touch Gestures (Mobile/Tablet)

- **Tap**: Toggle play/pause
- **Swipe Right**: Forward 30 seconds
- **Swipe Left**: Back 10 seconds
- **Swipe Up**: Volume up (+10%)
- **Swipe Down**: Volume down (-10%)
- **Double-Tap**: Toggle fullscreen

#### Mouse Controls

- **Double-Click**: Toggle fullscreen

## Supported Formats

### Video
- MP4, WebM, OGG, MOV, AVI, MKV
- (Support depends on browser capabilities)

### Audio
- MP3, WAV, OGG, FLAC, AAC, M4A
- (Support depends on browser capabilities)

## Browser Compatibility

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Opera: Full support

## Technical Details

### Architecture

The media player is built as a single HTML file containing:
- **HTML Structure**: Semantic markup for media container and controls
- **CSS Styling**: Dark theme with responsive design
- **JavaScript**: Vanilla JavaScript for all functionality (no external dependencies)

### Key Features Implementation

- **Dynamic Sizing**: Calculates aspect ratio and scales media to fit either width or height
- **Touch Detection**: Implements custom touch event handling for swipe and tap gestures
- **Keyboard Handling**: Global keyboard event listeners for media control
- **Drag & Drop**: HTML5 Drag and Drop API for file loading
- **Fullscreen**: Uses Fullscreen API for immersive viewing

## License

This project is open source and available for personal and commercial use.

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.
