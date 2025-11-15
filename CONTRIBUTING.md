# Contributing to Video to MP4 Converter

Thank you for your interest in contributing! This project is a client-side web application that uses `ffmpeg.wasm` to convert videos.

### Prerequisites

- Node.js and npm (for `npx`)

### Running Locally

1.  Clone the repository:
    ```bash
    git clone https://github.com/client-side-apps/video-to-mp4.git
    cd video-to-mp4
    ```

2.  Start a local server:
    ```bash
    npx serve
    ```

3.  Open your browser at the URL provided (usually `http://localhost:3000`).

## Architecture

- **`index.html`**: The main entry point, containing the UI and the logic to drive `ffmpeg.wasm`.
- **`sw.js`**: The Service Worker. It caches resources for offline use and, crucially, intercepts fetch requests to add `COOP` and `COEP` headers.
- **`icons/`**: Contains the application icons and assets.

## Making Changes

1.  Fork the repository.
2.  Create a new branch for your feature or fix.
3.  Make your changes.
4.  Test locally using `npx serve`.
5.  Submit a Pull Request.

