# MarkItDown App Updates

This repository contains release builds for the MarkItDown Converter desktop application.

It does not contain source code.

## What is this?

The MarkItDown Converter is a desktop application that allows you to:

- Drag and drop files anywhere in the window
- Convert files into Markdown format
- View conversion progress in real time
- Use a simple desktop interface
- Receive update notifications automatically

## Downloads

Latest versions are available under the Releases section:

https://github.com/NeedlerCR/MarkItDown-App-Updates/releases

## Auto Update System

The application checks this repository using the GitHub Releases API:

https://api.github.com/repos/NeedlerCR/MarkItDown-App-Updates/releases/latest

If a newer version is available, the app will notify you when it starts.

## Versioning

- v1.0.0 Initial release
- v1.0.1 Bug fixes
- v1.1.0 New features
- v2.0.0 Major updates

## How to publish a release

1. Build the app using PyInstaller
2. Zip the application:

zip -r MarkItDownApp.zip dist/MarkItDownApp.app

3. Go to GitHub Releases
4. Create a new release
5. Set a tag (example: v1.0.1)
6. Upload the zip file
7. Publish the release

## Notes

This repository is only used for compiled application releases.
