# Base64 Encoded Barcode Viewer

A simple web tool to view and display barcodes that are encoded in base64 format.

## Overview

This tool allows you to paste base64-encoded barcode images and instantly view them in your browser. It supports various image formats including PNG, JPEG, GIF, and SVG that contain barcode data.

## Features

- Paste any base64-encoded barcode image
- Auto-detection of image format
- Works with or without the data URI prefix (`data:image/png;base64,`)
- Simple, clean interface
- No server-side processing - everything happens in your browser
- Mobile-friendly design

## How to Use

1. Open the HTML file in any modern web browser
2. Paste your base64-encoded barcode string into the text area
3. Click the "View Barcode" button
4. Your barcode will be displayed in the results section below

## Use Cases

- Testing barcode generation systems
- Verifying base64-encoded barcode data
- Quickly converting base64 strings to visible barcodes
- Debugging applications that generate barcodes in base64 format

## Technical Details

The viewer automatically attempts to detect the image format from the base64 string. Supported formats include:
- PNG
- JPEG
- GIF
- SVG

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
