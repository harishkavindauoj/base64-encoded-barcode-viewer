# Base64 Encoded Image Viewer

A simple web tool to view and display any base64-encoded images, including barcodes, QR codes, and other image formats.

## Overview

This tool allows you to paste base64-encoded images and instantly view them in your browser. It works with any image format that your browser can render.

## Features

- Paste any base64-encoded image
- Auto-detection of common image formats
- Works with or without the data URI prefix (`data:image/png;base64,`)
- Simple, clean interface
- No server-side processing - everything happens in your browser
- Mobile-friendly design

## How to Use

1. Open the HTML file in any modern web browser
2. Paste your base64-encoded image string into the text area
3. Click the "View Image" button
4. Your image will be displayed in the results section below

## Use Cases

- Viewing base64-encoded barcodes or QR codes
- Testing image generation systems
- Verifying base64-encoded image data
- Quickly converting base64 strings to visible images
- Debugging applications that generate images in base64 format

## Technical Details

The viewer automatically attempts to detect the image format from the base64 string. Common formats that browsers can display include:
- PNG
- JPEG
- GIF
- SVG
- WebP
- And others supported by your browser

Note that this is a generic image viewer - it doesn't specifically process or validate barcode data. It simply displays whatever image is encoded in the base64 string you provide.

## Installation

No installation required. Simply download the HTML file and open it in your web browser.

## Browser Compatibility

Works with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This tool is free to use and modify.
