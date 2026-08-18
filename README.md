# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

I also build practical browser tools that use the browser as a lightweight local application runtime. Many of these tools are distributed as a **single self-contained HTML file** and are designed to process files, media, sensor data, and other user content locally without requiring an application backend.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a growing collection of my browser-based tools.

## 🐱 Browser tools

I like exploring how far a browser can go as an application platform.

Depending on the problem, these projects use browser-native APIs, WebAssembly, Web Workers, Canvas, local storage, cameras, microphones, sensors, SQLite, FFmpeg, and on-device machine learning.

Most recent projects share a few principles:

* Local-first processing
* Single-HTML distribution
* No account required
* Minimal or no runtime network access
* Japanese / English UI
* Smartphone-friendly interfaces where appropriate
* Reproducible builds and automated verification

### 📄 Documents, images & privacy

| Project                                                                                          | What it does                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Submission PDF Scanner](https://github.com/ttomohisa/htmlapps-document-scanner)                 | Turn photos of paper documents into submission-ready PDFs with perspective correction, multi-page organization, A4 output, B&W conversion, and file-size targets. |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                                 | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                                                                             |
| [PDF Compare](https://github.com/ttomohisa/htmlapps-pdf-compare)                                 | Compare two PDF revisions, align corresponding pages, and detect inserted, removed, visual, and text differences.                                                 |
| [Image Compressor & Converter](https://github.com/ttomohisa/htmlapps-image-compressor-converter) | Compress, resize, convert, compare, and export PNG, JPEG, and WebP images, including batch and target-size workflows.                                             |
| [Face Redactor](https://github.com/ttomohisa/htmlapps-face-redactor)                             | Detect faces locally with YuNet + ONNX Runtime Web and hide them using pixelation, blur, fills, eye bars, emoji, or custom images.                                |
| [Photo Privacy Inspector](https://github.com/ttomohisa/htmlapps-photo-privacy-inspector)         | Inspect what GPS, timestamps, device information, creator fields, and other hidden photo metadata could reveal before sharing an image.                           |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor)           | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                                                                           |
| [GIF Optimizer](https://github.com/ttomohisa/htmlappps-gif-optimizer)                            | Optimize animated GIFs directly in the browser to reduce file size.                                                                                               |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)                      | Convert images to WebP and generate Base64 data URIs.                                                                                                             |

### 🎬 Video & media

| Project                                                                              | What it does                                                                                                                           |
| ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)     | Compress video locally with a dedicated FFmpeg WebAssembly build, with controls for resolution, bitrate, frame rate, codec, and audio. |
| [Lossless Video Cutter](https://github.com/ttomohisa/htmlapps-lossless-video-cutter) | Cut MP4, MOV, MKV, and WebM video without re-encoding by remuxing the original compressed streams in the browser.                      |
| [Music Practice Kit](https://github.com/ttomohisa/htmlapps-music-practice-kit)       | Combine a tuner, metronome, TAP BPM, drone tone, practice timer, recorder, and spectrum analyzer in one browser app.                   |

### 🗃️ Data & developer tools

| Project                                                                                | What it does                                                                                                                            |
| -------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [SQLite Explorer](https://github.com/ttomohisa/htmlapps-sqlite-explorer)               | Explore SQLite databases locally with table browsing, schema and relationship views, profiling, read-only SQL, and query-plan analysis. |
| [JSON / YAML / CSV Viewer](https://github.com/ttomohisa/htmlapps-json-yaml-csv-viewer) | Inspect, search, profile, check, and convert JSON, YAML, CSV, TSV, and JSON Lines locally.                                              |
| [HTML Parquet Viewer](https://github.com/ttomohisa/html-parquet-viewer)                | Inspect Parquet schemas and browse data as a table without uploading the file.                                                          |
| [Markdown Preview Lab](https://github.com/ttomohisa/htmlapps-markdown-preview-lab)     | Write Markdown locally and compare GitHub-, Qiita-, and Zenn-inspired previews and compatibility hints.                                 |
| [Temporary Links](https://github.com/ttomohisa/htmlapps-temporary-links)               | Keep a disposable local work queue of web links, `file:///` URLs, Windows paths, and UNC paths.                                         |

### 📱 Pocket & everyday utilities

| Project                                                                          | What it does                                                                                                             |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [QR Reader](https://github.com/ttomohisa/htmlapps-qr-reader)                     | Scan QR codes from a live camera or existing images, with smartphone-first controls and local scan history.              |
| [Pocket Level](https://github.com/ttomohisa/htmlapps-pocket-level)               | Turn a smartphone into a spirit level / inclinometer with zeroing, hold, averaging, and two-point calibration.           |
| [Way Back](https://github.com/ttomohisa/htmlapps-way-back)                       | Save a location and find your way back using a large direction arrow and straight-line distance without requiring a map. |
| [Pocket Teleprompter](https://github.com/ttomohisa/htmlapps-pocket-teleprompter) | Paste a script and use your phone as an installation-free teleprompter with automatic scrolling and local saving.        |
| [Signal Screen](https://github.com/ttomohisa/htmlapps-signal-screen)             | Turn a phone or computer display into a highly visible sign using large text, arrows, colors, and QR codes.              |
| [Tap Counter](https://github.com/ttomohisa/htmlapps-tap-counter)                 | A smartphone-friendly tally counter for people, inventory, laps, repetitions, and multiple simultaneous categories.      |
| [Pomodoro Timer](https://github.com/ttomohisa/htmlapps-pomodoro-timer)           | A local-first focus timer with Picture-in-Picture, distraction counting, flow overtime, and local session history.       |

### 🧪 Small experiments

| Project                                                            | What it does                                                                                                   |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------- |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo) | Create customizable offline meeting-jargon bingo cards, including a floating Document Picture-in-Picture mode. |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)   | Play Minesweeper in a normal page or floating Document Picture-in-Picture window.                              |

## 🏗️ Building single-HTML apps

Some projects are infrastructure for the apps themselves.

| Project                                                                          | What it does                                                                                                                                                               |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template)       | A reusable repository template for building, verifying, packaging, and publishing self-contained browser applications.                                                     |
| [FFmpeg WASM Builder](https://github.com/ttomohisa/htmlapps-ffmpeg-wasm-builder) | Build small, purpose-specific FFmpeg WebAssembly cores directly from pinned FFmpeg / Emscripten sources instead of embedding the full general-purpose FFmpeg distribution. |

### FFmpeg WASM Builder

Rather than shipping the full FFmpeg CLI for every video tool, I'm experimenting with **application-specific FFmpeg WebAssembly builds**.

Each profile starts from `--disable-everything` and enables only the components required by that application.

Current profiles include:

* **Video Compressor** — H.264 + AAC encoding using x264
* **Lossless Video Cutter** — stream-copy cutting without decoders or encoders

The generated cores run in Web Workers, do not require pthreads, `SharedArrayBuffer`, COOP / COEP headers, or a backend server, and are tested with real browser smoke tests.

## 💡 Development approach

* **Local-first processing**
  Keep user-selected files, media, database contents, sensor readings, and application data on the device whenever the browser platform allows it.

* **Self-contained delivery**
  Prefer a downloadable HTML artifact that remains useful independently of a permanently hosted application stack.

* **Use the browser as an application runtime**
  Take advantage of WebAssembly, Web Workers, File APIs, Canvas, IndexedDB, Web Audio, camera / microphone / sensor APIs, Document Picture-in-Picture, and other browser capabilities when they provide practical value.

* **Purpose-specific dependencies**
  Libraries and WebAssembly are welcome when useful, but unnecessary runtime dependencies are avoided.

* **Reproducible builds**
  Pin third-party versions and source revisions, embed only required assets, and record hashes and licensing information where appropriate.

* **Minimal runtime network use**
  Avoid runtime CDNs, remote APIs, analytics, telemetry, and cloud processing where practical.

* **Simple maintenance**
  Favor readable source, Windows-friendly PowerShell / `.bat` workflows, automated checks, real-browser smoke tests, and GitHub Pages deployment.

## 🛠 Skills & interests

* **Cloud & data engineering:** Azure, Databricks, Parquet, MLflow, IoT
* **Browser applications:** HTML, CSS, JavaScript, WebAssembly, Web Workers
* **Local processing:** PDFs, images, video, audio, SQLite, structured data
* **Browser APIs:** File APIs, Canvas, Web Audio, Media Capture, sensors, IndexedDB, Picture-in-Picture
* **Build & automation:** PowerShell, GitHub Actions, GitHub Pages, reproducible standalone builds
* **WebAssembly:** FFmpeg / Emscripten, ONNX Runtime Web, purpose-specific WASM builds

## 📫 Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
