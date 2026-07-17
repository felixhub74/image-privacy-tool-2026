# Image Privacy Guard v2.5-beta.1 - privacy tool 2026

> **Browser-based image privacy for 2026.** Image Privacy Guard examines image metadata right in your browser and helps you strip out sensitive information from JPG, PNG, and TIFF files without sending them to a server.

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.5-beta.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felixhub74/image-privacy-tool-2026?style=flat-square)](https://github.com/felixhub74/image-privacy-tool-2026)

---

<p align="center">
  <a href="https://felixhub74.github.io/image-privacy-tool-2026/">
    <img src="https://img.shields.io/badge/Download-Image%20Privacy%20Guard%20Latest-brightgreen?style=for-the-badge" alt="Download Image Privacy Guard">
  </a>
</p>

> **[Direct Download - Image Privacy Guard v2.5-beta.1](https://felixhub74.github.io/image-privacy-tool-2026/)**

---

[Download Latest Build](https://felixhub74.github.io/image-privacy-tool-2026/)

---

## What Image Privacy Guard Does

Image Privacy Guard is a privacy-focused browser utility for checking image metadata and clearing out details you may not want attached to a file. Since all processing happens locally in the browser, you can inspect images before they are shared or published.

It is aimed at anyone working with photos or graphics who needs a fast way to cut down metadata exposure without depending on a backend service. The layout stays minimal so the main tasks, scanning and removal, remain easy to access when needed.

---

## Key Capabilities

- Operates fully in the browser for local image analysis
- Finds metadata stored in supported image files
- Removes sensitive metadata with one action
- Keeps files off a server during the workflow
- Works with JPG, PNG, and TIFF images
- Presents a straightforward interface for fast review and cleanup
- Helps prepare images for sharing with less embedded detail

---

## Installation

1. Open the project in a modern web browser, or clone the repository if you are hosting it yourself:
   - `git clone https://github.com/felixhub74/image-privacy-tool-2026.git
2. Serve the files through your preferred static host or open the web app entry point in a browser.
3. Launch the page and load an image to begin analysis.

If you are deploying the app locally, make sure the browser can access the built HTML assets without server-side processing.

---

## Using the App

1. Open Image Privacy Guard in your browser.
2. Add a JPG, PNG, or TIFF image.
3. Review the detected metadata.
4. Use the remove action to strip sensitive fields.
5. Download or save the cleaned image after verification.

Typical workflow:

- inspect before sharing
- remove metadata you do not want embedded
- export the updated file for upload or archiving

---

## Configuration

Configuration is expected to live in the browser-side app settings or static project files, depending on how the repository is deployed.

Example layout:

    {
      "analysis": true,
      "metadataRemoval": true,
      "supportedFormats": ["jpg", "png", "tiff"]
    }

If your deployment does not expose a settings screen, adjust the static app files or build-time options used by your host.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Enough local memory and disk space to open and process image files
- Supported formats: JPG, PNG, TIFF

No server upload is required for the core workflow.

---

## FAQ

**Does it upload my images?**  
No. The workflow is browser-based and does not require uploading files to a server.

**Which file types are supported?**  
JPG, PNG, and TIFF are supported.

**How do I update it?**  
Replace your local deployment with the latest build from the project release location or hosting source.

**Where are settings stored?**  
Settings, when available, are kept in the browser-side app or in the static files used by your deployment.

**What if a file does not load?**  
Check that the image format is supported and confirm you are using a current browser session with enough local resources.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
