# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

I also build practical browser tools that use the browser as a lightweight local application runtime. Many of these tools are distributed as a **single self-contained HTML file** and process files, media, databases, sensor data, and other user content locally without requiring an application backend.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a growing collection of my browser-based tools.

## 🐱 Browser tools

I like exploring how far the browser can go as an application platform.

Depending on the problem, these projects use browser-native APIs, WebAssembly, Web Workers, Canvas, WebCodecs, Web Audio, local storage, cameras, microphones, sensors, SQLite, FFmpeg, and on-device machine learning.

Most recent projects share a few principles:

* **Local-first processing**
* **Single-HTML distribution**
* **No account required**
* **Minimal or no runtime network access**
* **Japanese / English UI**
* **Smartphone-friendly interfaces where appropriate**
* **Reproducible builds and automated verification**

### 📄 Documents, images & privacy

| Project                                                                                          | What it does                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Submission PDF Scanner](https://github.com/ttomohisa/htmlapps-document-scanner)                 | Turn photos of paper documents into submission-ready PDFs with perspective correction, multi-page organization, A4 output, B&W conversion, and file-size targets. |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                                 | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                                                                             |
| [PDF Compare](https://github.com/ttomohisa/htmlapps-pdf-compare)                                 | Compare two PDF revisions, align corresponding pages, and detect inserted, removed, visual, and text differences.                                                 |
| [Image Compressor & Converter](https://github.com/ttomohisa/htmlapps-image-compressor-converter) | Compress, resize, convert, compare, and export PNG, JPEG, and WebP images, including batch and target-size workflows.                                             |
| [Face Redactor](https://github.com/ttomohisa/htmlapps-face-redactor)                             | Detect faces locally with YuNet + ONNX Runtime Web and hide them using pixelation, blur, fills, eye bars, emoji, or custom images.                                |
| [Photo Privacy Inspector](https://github.com/ttomohisa/htmlapps-photo-privacy-inspector)         | Inspect GPS, timestamps, device information, creator fields, and other hidden photo metadata before sharing an image.                                             |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor)           | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                                                                           |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)                      | Convert images to WebP and generate Base64 data URIs.                                                                                                             |

### 🎬 Video & audio

| Project                                                                              | What it does                                                                                                                                                     |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)     | Compress video locally with a purpose-built FFmpeg WebAssembly core, including resolution, bitrate, frame-rate, and audio controls.                              |
| [Lossless Video Cutter](https://github.com/ttomohisa/htmlapps-lossless-video-cutter) | Cut MP4, MOV, MKV, and WebM video without re-encoding by remuxing the original compressed streams in the browser.                                                |
| [Video Face Redactor](https://github.com/ttomohisa/htmlapps-video-face-redactor)     | Detect faces in videos locally, review and correct masks frame by frame, and export redacted H.264 MP4 video.                                                    |
| [Media Inspector](https://github.com/ttomohisa/htmlapps-media-inspector)             | Inspect containers, codecs, bitrate, FPS, HDR/color information, audio, subtitles, chapters, rotation, and metadata, with browser-specific playback diagnostics. |
| [Video Contact Sheet](https://github.com/ttomohisa/htmlapps-video-contact-sheet)     | Sample 12, 24, or 48 frames across an entire video and combine them into a zoomable PNG/JPEG overview image.                                                     |
| [Video to GIF / WebP](https://github.com/ttomohisa/htmlapps-video-to-gif-webp)       | Trim and crop a local video and convert the selected range into an animated GIF or WebP using compact FFmpeg WASM cores.                                         |
| [Music Practice Kit](https://github.com/ttomohisa/htmlapps-music-practice-kit)       | Combine a tuner, metronome, TAP BPM, drone tone, practice timer, recorder, and spectrum analyzer in one browser app.                                             |

### 🗃️ Data, writing & workflow

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

### 🧪 Experiments

| Project                                                                   | What it does                                                                                                                                     |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Optical File](https://github.com/ttomohisa/htmlapps-optical-file-camera) | Turn a file up to 1 MiB into an Animated QR WebP and reconstruct it by scanning the animation with another device or decoding the WebP directly. |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo)        | Create customizable offline meeting-jargon bingo cards, including a floating Document Picture-in-Picture mode.                                   |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)          | Play Minesweeper in a normal page or floating Document Picture-in-Picture window.                                                                |

## 🧩 WebAssembly & build infrastructure

Browser apps are only part of the project.

I'm also working on the tooling needed to build, verify, package, and distribute browser-friendly WebAssembly.

| Project                                                                          | What it does                                                                                                                                                                  |
| -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template)       | A reusable repository template for building, verifying, packaging, and publishing self-contained browser applications.                                                        |
| [FFmpeg WASM Builder](https://github.com/ttomohisa/htmlapps-ffmpeg-wasm-builder) | Build small, purpose-specific FFmpeg WebAssembly cores directly from pinned FFmpeg / Emscripten sources.                                                                      |
| [WASM Zoo](https://github.com/ttomohisa/wasm-zoo)                                | Build and publish current upstream native software for WebAssembly with reproducible recipes, capability manifests, checksums, source archives, and real browser smoke tests. |

### FFmpeg WASM Builder

Instead of embedding the full general-purpose FFmpeg CLI into every tool, I build **application-specific FFmpeg WebAssembly cores**.

Each profile starts from `--disable-everything` and enables only the demuxers, muxers, codecs, filters, and libraries actually required by the application.

Current profiles include:

| Profile                 | Purpose                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------ |
| `video-compressor`      | H.264 + AAC video compression using x264                                                         |
| `lossless-video-cutter` | Stream-copy cutting without video/audio decoding or encoding                                     |
| `media-inspector`       | Container, codec, bitrate, FPS, HDR, audio, subtitle, chapter, rotation, and metadata inspection |
| `video-contact-sheet`   | Seek through a video and decode only the frames needed for 12 / 24 / 48-frame overview sheets    |
| `video-to-gif`          | Trim, crop, resize, and encode animated GIFs                                                     |
| `video-to-webp`         | Trim, crop, resize, and encode animated WebP using libwebp                                       |

The cores run in Web Workers and are designed to work without pthreads, `SharedArrayBuffer`, COOP / COEP headers, or a backend server.

Every release profile is compiled from pinned source revisions and exercised by a **real browser smoke test**, not just checked for successful compilation.

### WASM Zoo

**[WASM Zoo](https://github.com/ttomohisa/wasm-zoo)** takes a different approach.

While FFmpeg WASM Builder produces deliberately small, application-specific cores, WASM Zoo aims to provide **broad, upstream-shaped WebAssembly distributions of native software** with explicit capability reporting.

Current packages include:

| Package            | Browser build                                                     |
| ------------------ | ----------------------------------------------------------------- |
| **FFmpeg 9**       | Broad FFmpeg CLI builds, including an optional GPL / x264 profile |
| **libarchive 3.8** | `bsdtar`, `bsdcpio`, `bsdcat`, and `bsdunzip`                     |
| **ImageMagick 7**  | Browser build of the upstream `magick` CLI                        |

Each Zoo package aims to provide:

* Exact upstream and toolchain revisions
* Reproducible build scripts
* Real browser runtime smoke tests
* Machine-readable manifests and feature inventories
* SHA-256 checksums
* License notices
* Corresponding source archives
* Interactive browser playgrounds

The next candidates currently being explored include **libvips** and **Ghostscript**.

## 💡 Development approach

* **Local-first processing**
  Keep user-selected files, media, database contents, sensor readings, and application data on the device whenever the browser platform allows it.

* **Self-contained delivery**
  Prefer downloadable artifacts that remain useful independently of a permanently hosted application stack.

* **Use the browser as an application runtime**
  Take advantage of WebAssembly, Web Workers, WebCodecs, File APIs, Canvas, IndexedDB, Web Audio, camera / microphone / sensor APIs, Document Picture-in-Picture, and other browser capabilities when they provide practical value.

* **Purpose-specific dependencies**
  Libraries and WebAssembly are welcome when they solve a real problem. The goal is not “vanilla only”; it is to keep the runtime understandable and avoid unnecessary dependencies.

* **Build small when the application needs small**
  For tools such as video processing, build dedicated WebAssembly profiles containing only the features the application actually uses.

* **Preserve upstream shape when generality matters**
  Projects such as WASM Zoo take the opposite approach and expose broad upstream functionality when a reusable general-purpose distribution is more useful.

* **Reproducible builds**
  Pin third-party versions and source revisions, publish corresponding source where appropriate, and record hashes and licensing information.

* **Minimal runtime network use**
  Avoid runtime CDNs, remote APIs, analytics, telemetry, and cloud processing where practical.

* **Test the real runtime**
  Compilation is not enough for WebAssembly. Build pipelines should exercise meaningful functionality in an actual browser.

* **Simple maintenance**
  Favor readable source, Windows-friendly PowerShell / `.bat` workflows, automated checks, and GitHub Pages deployment.

## 🛠 Skills & interests

* **Cloud & data engineering:** Azure, Databricks, Parquet, MLflow, IoT
* **Browser applications:** HTML, CSS, JavaScript, WebAssembly, Web Workers, WebCodecs
* **Local processing:** PDFs, images, video, audio, SQLite, structured data
* **Browser APIs:** File APIs, Canvas, Web Audio, Media Capture, sensors, IndexedDB, Picture-in-Picture
* **WebAssembly:** FFmpeg, Emscripten, libarchive, ImageMagick, ONNX Runtime Web
* **Build & automation:** PowerShell, GitHub Actions, GitHub Pages, reproducible builds, browser smoke testing

## 📫 Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
