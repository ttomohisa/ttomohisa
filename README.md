# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

Outside of that, I build practical browser tools and experiment with how far the browser can go as a **local application runtime**.

Many of my projects are distributed as a **single self-contained HTML file**. Files, images, videos, databases, camera frames, sensor readings, and other user data are processed locally whenever possible, without requiring an application backend.

I'm also interested in using HTML not only as a web page, but as a **portable file/container format** — a file that can carry both the content and the specialized viewer needed to understand it.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a growing collection of my browser-based tools.

## 🐱 Browser tools

Depending on the problem, these projects use browser-native APIs, WebAssembly, Web Workers, WebCodecs, Canvas, Web Audio, cameras, microphones, sensors, SQLite, FFmpeg, OpenCV, and on-device machine learning.

Most recent projects share a few principles:

* **Local-first processing**
* **Single-HTML distribution**
* **No account required**
* **Minimal runtime network access**
* **Japanese / English UI**
* **Desktop and smartphone UX where appropriate**
* **Pinned dependencies and reproducible builds**
* **Automated verification instead of trusting the build blindly**

### 📄 Documents, images & privacy

| Project                                                                                          | What it does                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [OneFile Album](https://github.com/ttomohisa/htmlapps-onefile-album)                             | Package multiple images, chapters, comments, and a responsive viewer into one portable HTML album that can later be opened and re-edited.                         |
| [Submission PDF Scanner](https://github.com/ttomohisa/htmlapps-document-scanner)                 | Turn photos of paper documents into submission-ready PDFs with perspective correction, multi-page organization, A4 output, B&W conversion, and file-size targets. |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                                 | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                                                                             |
| [PDF Compare](https://github.com/ttomohisa/htmlapps-pdf-compare)                                 | Compare two PDF revisions, align corresponding pages, and detect inserted, removed, visual, and text differences.                                                 |
| [Image Compressor & Converter](https://github.com/ttomohisa/htmlapps-image-compressor-converter) | Compress, resize, convert, compare, and export PNG, JPEG, and WebP images, including batch and target-size workflows.                                             |
| [Face Redactor](https://github.com/ttomohisa/htmlapps-face-redactor)                             | Detect faces locally with YuNet + ONNX Runtime Web and hide them using pixelation, blur, fills, eye bars, emoji, or custom images.                                |
| [Photo Privacy Inspector](https://github.com/ttomohisa/htmlapps-photo-privacy-inspector)         | Inspect GPS, timestamps, device information, creator fields, and other hidden photo metadata before sharing an image.                                             |
| [Same Spot Diff](https://github.com/ttomohisa/htmlapps-same-spot-diff)                           | Automatically align Before / After photos taken from slightly different positions, then highlight the places that actually changed.                               |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor)           | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                                                                           |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)                      | Convert images to WebP and generate Base64 data URIs.                                                                                                             |

### 🎬 Video & audio

| Project                                                                              | What it does                                                                                                                                                     |
| ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)     | Compress video locally with a purpose-built FFmpeg WebAssembly core, including resolution, bitrate, frame-rate, and audio controls.                              |
| [Lossless Video Cutter](https://github.com/ttomohisa/htmlapps-lossless-video-cutter) | Cut MP4, MOV, MKV, and WebM video without re-encoding by remuxing the original compressed streams in the browser.                                                |
| [Video Face Redactor](https://github.com/ttomohisa/htmlapps-video-face-redactor)     | Detect faces in videos locally, review and correct masks frame by frame, and export a redacted H.264 MP4.                                                        |
| [Media Inspector](https://github.com/ttomohisa/htmlapps-media-inspector)             | Inspect containers, codecs, bitrate, FPS, HDR/color information, audio, subtitles, chapters, rotation, and metadata, with browser-specific playback diagnostics. |
| [Video Contact Sheet](https://github.com/ttomohisa/htmlapps-video-contact-sheet)     | Sample 12, 24, or 48 frames across an entire video and combine them into a zoomable PNG/JPEG overview image.                                                     |
| [Video to GIF / WebP](https://github.com/ttomohisa/htmlapps-video-to-gif-webp)       | Trim and crop a local video and convert the selected range into an animated GIF or WebP using compact FFmpeg WASM cores.                                         |
| [Music Practice Kit](https://github.com/ttomohisa/htmlapps-music-practice-kit)       | Combine a tuner, metronome, TAP BPM, drone tone, practice timer, recorder, and spectrum analyzer in one browser app.                                             |

### 🗃️ Data, developer & workflow tools

| Project                                                                                | What it does                                                                                                                                    |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [SQLite Explorer](https://github.com/ttomohisa/htmlapps-sqlite-explorer)               | Explore unfamiliar SQLite databases with table browsing, schema and relationship views, profiling, read-only SQL, and query-plan analysis.      |
| [JSON / YAML / CSV Viewer](https://github.com/ttomohisa/htmlapps-json-yaml-csv-viewer) | Inspect, search, profile, check, and convert JSON, YAML, CSV, TSV, and JSON Lines locally.                                                      |
| [HTML Parquet Viewer](https://github.com/ttomohisa/html-parquet-viewer)                | Inspect Parquet schemas and browse data as a table without uploading the file.                                                                  |
| [Archive Explorer](https://github.com/ttomohisa/htmlapps-archive-explorer)             | Explore, preview, analyze, and extract ZIP, 7z, RAR5, TAR, GZIP, CAB, ISO, and LZH/LHA archives locally.                                        |
| [Developer Toolbox](https://github.com/ttomohisa/httpapps-developer-toolbox)           | Put Base64, JSON, JWT, cron, regex, hashes, timestamps, text conversion, web utilities, and dozens of other developer tools into one HTML file. |
| [Text Inspector](https://github.com/ttomohisa/htmlapps-text-inspector)                 | Go beyond character counting with composition analysis, frequent words, long-sentence detection, writing checks, and an X-Ray view.             |
| [Markdown Preview Lab](https://github.com/ttomohisa/htmlapps-markdown-preview-lab)     | Write Markdown locally and compare GitHub-, Qiita-, and Zenn-inspired previews and compatibility hints.                                         |
| [Temporary Links](https://github.com/ttomohisa/htmlapps-temporary-links)               | Keep a disposable local work queue of web links, `file:///` URLs, Windows paths, and UNC paths.                                                 |
| [Task Packing](https://github.com/ttomohisa/htmlapps-task-packing)                     | Give tasks a physical size and fit only what actually fits onto a finite-capacity visual board.                                                 |
| [Random Picker](https://github.com/ttomohisa/htmlapps-random-picker)                   | Pick candidates, randomize order, create balanced teams, or run an animated wheel from a simple list.                                           |

### 📱 Camera, device & everyday utilities

| Project                                                                            | What it does                                                                                                                            |
| ---------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [Pop-up Face Check-in](https://github.com/ttomohisa/htmlapps-popup-face-check-in)  | Run temporary event reception with local face matching, manual fallback, attendance history, and encrypted portable registration files. |
| [Gesture Presentation](https://github.com/ttomohisa/htmlapps-gesture-presentation) | Present PDFs or images and move between pages with hand gestures, plus a serverless two-step QR WebRTC Air Remote.                      |
| [Device Check](https://github.com/ttomohisa/htmlapps-device-check)                 | Check camera, microphone, speakers, display, keyboard, touch/pointer input, gamepads, and motion sensors in one place.                  |
| [QR Reader](https://github.com/ttomohisa/htmlapps-qr-reader)                       | Scan QR codes from a live camera or existing images, with smartphone-first controls and local scan history.                             |
| [Pocket Level](https://github.com/ttomohisa/htmlapps-pocket-level)                 | Turn a smartphone into a spirit level / inclinometer with zeroing, hold, averaging, and two-point calibration.                          |
| [Way Back](https://github.com/ttomohisa/htmlapps-way-back)                         | Save a location and find your way back using a large direction arrow and straight-line distance without requiring a map.                |
| [Pocket Teleprompter](https://github.com/ttomohisa/htmlapps-pocket-teleprompter)   | Paste a script and use your phone as an installation-free teleprompter with automatic scrolling and local saving.                       |
| [Signal Screen](https://github.com/ttomohisa/htmlapps-signal-screen)               | Turn a phone or computer display into a highly visible sign using large text, arrows, colors, and QR codes.                             |
| [Tap Counter](https://github.com/ttomohisa/htmlapps-tap-counter)                   | A smartphone-friendly tally counter for people, inventory, laps, repetitions, and multiple simultaneous categories.                     |
| [Pomodoro Timer](https://github.com/ttomohisa/htmlapps-pomodoro-timer)             | A local-first focus timer with Picture-in-Picture, distraction counting, flow overtime, and local session history.                      |

### 🧪 Experiments

| Project                                                                   | What it does                                                                                                                                     |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Optical File](https://github.com/ttomohisa/htmlapps-optical-file-camera) | Turn a file up to 1 MiB into an Animated QR WebP and reconstruct it by scanning the animation with another device or decoding the WebP directly. |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo)        | Create customizable offline meeting-jargon bingo cards, including a floating Document Picture-in-Picture mode.                                   |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)          | Play Minesweeper in a normal page or floating Document Picture-in-Picture window.                                                                |

## 🧩 WebAssembly & build infrastructure

The applications are only one side of the work.

I'm also building the infrastructure needed to compile native software for browsers, reduce WASM size for specific applications, verify the resulting runtime, and distribute it reproducibly.

| Project                                                                          | What it does                                                                                                                                                                     |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template)       | A reusable repository template for building, verifying, packaging, and publishing self-contained browser applications.                                                           |
| [FFmpeg WASM Builder](https://github.com/ttomohisa/htmlapps-ffmpeg-wasm-builder) | Build small, application-specific FFmpeg WebAssembly cores directly from pinned FFmpeg / Emscripten sources.                                                                     |
| [OpenCV WASM Builder](https://github.com/ttomohisa/htmlapps-opencv-wasm-builder) | Compose logical OpenCV components into purpose-specific OpenCV.js / WASM profiles for Browser Kitty applications.                                                                |
| [WASM Zoo](https://github.com/ttomohisa/wasm-zoo)                                | Publish current upstream native software for WebAssembly with reproducible recipes, capability manifests, browser tests, provenance, SBOMs, checksums, and corresponding source. |

### FFmpeg WASM Builder

Instead of embedding the full general-purpose FFmpeg CLI into every video tool, **FFmpeg WASM Builder** produces application-specific cores.

Each profile starts from `--disable-everything` and enables only the components required by the application.

Current profiles:

| Profile                 | Purpose                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------ |
| `video-compressor`      | H.264 + AAC video compression using x264                                                         |
| `lossless-video-cutter` | Stream-copy cutting without video/audio decoding or encoding                                     |
| `media-inspector`       | Container, codec, bitrate, FPS, HDR, audio, subtitle, chapter, rotation, and metadata inspection |
| `video-contact-sheet`   | Seek through a video and decode only the frames required for a 12 / 24 / 48-frame overview       |
| `video-to-gif`          | Trim, crop, resize, and encode animated GIFs                                                     |
| `video-to-webp`         | Trim, crop, resize, and encode animated WebP using libwebp                                       |

The generated cores:

* Run in Web Workers
* Do not require pthreads
* Do not require `SharedArrayBuffer`
* Do not require COOP / COEP
* Can be embedded into a `file://`-compatible single HTML
* Are compiled from pinned source revisions
* Are exercised by real browser smoke tests

### OpenCV WASM Builder

**OpenCV WASM Builder** uses logical components instead of forcing each application to depend directly on OpenCV's changing module structure.

Components include:

* `core`
* `imgproc`
* `features`
* `geometry`
* `calibration`
* `video`
* `markers`
* `face`
* `stitching`

Application profiles can then request only what they need.

Examples include:

* `same-spot-diff`
* `gauge-reader`
* `marker-measure`
* `motion-analysis`
* `panorama`
* `face-recognition`
* `browser-kitty-full`

The builder resolves component dependencies, maps them to the appropriate OpenCV 4 / 5 modules, combines JavaScript bindings, and produces one statically linked OpenCV.js / WASM runtime per profile.

### WASM Zoo

**[WASM Zoo](https://github.com/ttomohisa/wasm-zoo)** takes a different approach.

Purpose-specific builders intentionally remove unnecessary functionality. WASM Zoo instead tries to preserve the **upstream program/API shape** when a broad reusable distribution is more useful.

Current packages:

| Package         | Current upstream |
| --------------- | ---------------- |
| **FFmpeg**      | 9.0.1            |
| **libarchive**  | 3.8.9            |
| **ImageMagick** | 7.1.2-30         |
| **libvips**     | 8.18.5           |
| **Ghostscript** | 10.07.1          |
| **jq**          | 1.8.2            |

WASM Zoo publishes more than binary `.wasm` files. A package is expected to include:

* Exact upstream source and toolchain revisions
* Reproducible build scripts
* Real browser runtime smoke tests
* Machine-readable manifests and capability information
* Upstream freshness tracking
* SHA-256 checksums
* License notices
* Corresponding source archives
* in-toto / SLSA provenance
* CycloneDX SBOMs
* Interactive browser playgrounds
* Release-health monitoring

## 💡 Development approach

* **Local-first processing**
  Keep user-selected files, media, database contents, camera frames, sensor readings, and application data on the device whenever the browser platform allows it.

* **Self-contained delivery**
  Prefer downloadable artifacts that remain useful independently of a permanently hosted application stack.

* **HTML can be more than a page**
  A single HTML file can also act as a portable application, viewer, report, album, or specialized container that carries both content and the software needed to inspect it.

* **Use the browser as an application runtime**
  Take advantage of WebAssembly, Web Workers, WebCodecs, File APIs, Canvas, IndexedDB, Web Audio, camera / microphone / sensor APIs, WebRTC, Document Picture-in-Picture, and other browser capabilities when they provide practical value.

* **Purpose-specific dependencies**
  Libraries and WebAssembly are welcome when they solve a real problem. The goal is not “vanilla only”; it is to keep the runtime understandable and avoid unnecessary dependencies.

* **Build small when the application needs small**
  For tools such as video and computer-vision processing, build dedicated WebAssembly profiles containing only the features the application actually needs.

* **Preserve upstream shape when generality matters**
  Projects such as WASM Zoo deliberately take the opposite approach and expose broad upstream functionality when a reusable distribution is more useful.

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
* **Local processing:** PDFs, images, video, audio, archives, SQLite, structured data
* **Computer vision:** OpenCV, ONNX Runtime Web, YuNet, SFace
* **Browser APIs:** File APIs, Canvas, Web Audio, Media Capture, sensors, WebRTC, IndexedDB, Picture-in-Picture
* **WebAssembly:** FFmpeg, OpenCV, Emscripten, libarchive, ImageMagick, libvips, Ghostscript, jq
* **Build & automation:** PowerShell, Docker, GitHub Actions, GitHub Pages, reproducible builds, browser smoke testing

## 📫 Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
