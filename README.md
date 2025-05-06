# Google Chat Takeout Viewer

[A standalone HTML viewer for Google Chat/Hangouts takeout exports.](https://creedofman.github.io/google-chat-takeout-viewer/)

## Overview

This tool allows you to view your Google Chat conversations from Google Takeout exports in a modern, user-friendly chat interface. The viewer works entirely in your browser - no data is sent to any server.

![Screenshot of the Google Chat Takeout Viewer](screenshot.png)

## Features

- **Single HTML File**: No installation required, just open the HTML file in your browser
- **Modern Chat Interface**: Message bubbles with alternating colors for different senders
- **Media Support**: View images, videos, and audio directly in the interface
- **Image Preview**: Click on images to view them in full size
- **Download Links**: Easily download any media files from the conversation
- **Privacy-Focused**: All processing happens locally in your browser
- **No Dependencies**: Standalone file with no external dependencies (except for zip.js)

## How to Use

1. **Download Your Google Chat Data**:
   - Go to [Google Takeout](https://takeout.google.com/)
   - Select only "Google Hangouts" or "Google Chat" data
   - Create and download the export

2. **Use the Viewer**:
   - Download the `index.html` file from this repository
   - Open the HTML file in any modern web browser
   - Click "Select Takeout ZIP File" and choose your downloaded Takeout ZIP file
   - Browse your conversations in the left sidebar

## Technical Details

The viewer uses:
- Pure JavaScript for parsing and displaying the data
- [zip.js](https://gildas-lormeau.github.io/zip.js/) for ZIP file extraction
- CSS3 for styling the modern chat interface

## Limitations

- Only designed for Google Chat/Hangouts exports
- Large exports may take a moment to process
- Some older or specialized message types may not display correctly

## Privacy

This tool runs entirely in your browser. No data is sent to any server, and your conversation data never leaves your computer.

## Acknowledgments

- Google for providing data exports through Takeout
- The creators of zip.js for the excellent ZIP processing library
