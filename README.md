# Chrome Tab Screen Recorder

A simple browser-based screen recording application that allows you to capture your screen, record audio, and save recordings for later use. This application runs entirely in the browser using modern web technologies.

## Author

**longmvd**

## Features

- **High-quality screen recording** with multiple resolution options:
  - Standard (720p)
  - Full HD (1080p)
  - Ultra HD (4K) (if supported by your device)
- **Audio recording** capabilities
- **Persistent storage** of recordings using IndexedDB
- **Recording management** with options to play, download, rename, and delete recordings
- **Responsive design** that works on various screen sizes

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Media Capture and Streams API
- MediaRecorder API
- IndexedDB for local storage

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Edge, or Firefox recommended)
- For best results, use Chrome as it has the most complete implementation of the required APIs

### Installation

1. Clone this repository:

   ```
   git clone https://github.com/yourusername/screen-recorder.git
   ```

2. Open `index.html` in your web browser

No additional installation or dependencies are required as this is a client-side only application.

## Usage

1. Select your desired recording quality from the dropdown menu
2. Click "Start Recording" and choose which screen/window/tab you want to capture
3. Allow audio access if prompted
4. Perform the actions you want to record
5. Click "Stop Recording" when finished
6. Your recording will automatically be saved and can be accessed in the Recording History panel
7. Use the Play, Download, or Delete buttons to manage your recordings

## Notes

- Recordings are stored locally in your browser and are not uploaded to any server
- Clearing your browser cache will delete your saved recordings
- Recording quality and duration may be limited by your device's capabilities
- Ultra HD (4K) recording requires appropriate hardware support

## License

This project is licensed under the MIT License - see the LICENSE file for details.
