# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

Outside of that, I build practical browser tools and experiment with how far the browser can go as a **local application runtime**.

Many of my projects are distributed as a **single self-contained HTML file**. Files, images, videos, databases, camera frames, sensor readings, and other user data are processed locally whenever possible, without requiring an application backend.

I'm also interested in using HTML not only as a web page, but as a **portable application and container format** — a file that can carry both content and the specialized viewer needed to work with it.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a growing collection of my browser-based tools.

## 🐱 Browser tools

Depending on the problem, these projects use browser-native APIs, WebAssembly, Web Workers, WebCodecs, Canvas, Web Audio, cameras, microphones, sensors, WebRTC, SQLite, DuckDB, FFmpeg, OpenCV, and on-device machine learning.

Most recent projects share a few principles:

* **Local-first processing**
* **Single-HTML distribution**
* **No account required**
* **Minimal runtime network access**
* **Japanese / English UI**
* **Desktop and smartphone UX where appropriate**
* **Pinned dependencies and reproducible builds**
* **Automated verification and real-browser testing where practical**

### 📄 Documents, images & publishing

| Project                                                                                          | What it does                                                                                                                                     |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| [OneFile Album](https://github.com/ttomohisa/htmlapps-onefile-album)                             | Package images, chapters, comments, and a responsive viewer into one portable HTML album that can later be reopened and edited.                  |
| [Submission PDF Scanner](https://github.com/ttomohisa/htmlapps-document-scanner)                 | Turn photos of paper documents into submission-ready PDFs with perspective correction, page organization, A4/B&W presets, and file-size targets. |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                                 | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                                                            |
| [PDF Compare](https://github.com/ttomohisa/htmlapps-pdf-compare)                                 | Compare two PDF revisions and review inserted, removed, visual, and text differences.                                                            |
| [PPTX Diff](https://github.com/ttomohisa/htmlapps-pptx-diff)                                     | Compare two PowerPoint files with slide matching, semantic change detection, and high-fidelity visual comparison.                                |
| [Max Text Print](https://github.com/ttomohisa/htmlapps-max-text-print)                           | Fit text to the largest practical size on A4, split it across sheets when needed, and print directly from the browser.                           |
| [Image Compressor & Converter](https://github.com/ttomohisa/htmlapps-image-compressor-converter) | Compress, resize, convert, compare, and export PNG, JPEG, and WebP images, including batch and target-size workflows.                            |
| [Image Counter](https://github.com/ttomohisa/htmlapps-image-counter)                             | Manually count objects in photos with point or rectangle markers and export annotated results or a portable HTML viewer.                         |
| [Smart Image Sorter](https://github.com/ttomohisa/htmlapps-smart-image-sorter)                   | Sort batches of images into predefined categories with local TinyCLIP-based AI and review uncertain results before export.                       |
| [Face Redactor](https://github.com/ttomohisa/htmlapps-face-redactor)                             | Detect faces locally and hide them with pixelation, blur, fills, eye bars, emoji, or custom images.                                              |
| [Photo Privacy Inspector](https://github.com/ttomohisa/htmlapps-photo-privacy-inspector)         | Inspect GPS, timestamps, device information, creator fields, and other hidden photo metadata before sharing an image.                            |
| [Same Spot Diff](https://github.com/ttomohisa/htmlapps-same-spot-diff)                           | Align Before / After photos taken from slightly different positions and highlight the places that actually changed.                              |
| [Photo Re-Enactor](https://github.com/ttomohisa/htmlapps-photo-re-enactor)                       | Recreate an earlier photo composition using a live-camera reference overlay and compare the resulting Before / After images.                     |
| [Handwriting Font Maker](https://github.com/ttomohisa/htmlapps-handwriting-font-maker)           | Draw characters directly in the browser and turn the vector strokes into a downloadable TrueType font.                                           |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor)           | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                                                          |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)                      | Convert images to WebP and generate Base64 data URIs.                                                                                            |

### 🎬 Video, audio & presentations

| Project                                                                                    | What it does                                                                                                                             |
| ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)           | Compress video locally with purpose-built FFmpeg WebAssembly, including H.264/AAC MP4 and VP9/Opus WebM workflows.                       |
| [Lossless Video Cutter](https://github.com/ttomohisa/htmlapps-lossless-video-cutter)       | Cut video without re-encoding by remuxing the original compressed streams in the browser.                                                |
| [Video Speed Changer](https://github.com/ttomohisa/htmlapps-video-speed-changer)           | Change video speed from 0.25× to 4×, control audio behavior, preview the result, and export MP4 locally.                                 |
| [Video Face Redactor](https://github.com/ttomohisa/htmlapps-video-face-redactor)           | Detect faces in videos locally, review masks frame by frame, and export a redacted H.264 MP4.                                            |
| [Media Inspector](https://github.com/ttomohisa/htmlapps-media-inspector)                   | Inspect containers, codecs, bitrate, FPS, HDR/color information, audio, subtitles, chapters, rotation, and metadata.                     |
| [Video Contact Sheet](https://github.com/ttomohisa/htmlapps-video-contact-sheet)           | Sample frames across an entire video and combine them into one zoomable PNG/JPEG overview image.                                         |
| [Video to GIF / WebP](https://github.com/ttomohisa/htmlapps-video-to-gif-webp)             | Trim and crop a video and convert the selected range into an animated GIF or WebP.                                                       |
| [One Second Montage](https://github.com/ttomohisa/htmlapps-one-second-montage)             | Turn mixed photos and videos into an MP4 montage using one second from each item, with optional music and year dividers.                 |
| [Audio Cutter & Joiner](https://github.com/ttomohisa/htmlapps-audio-cutter-joiner)         | Trim, split, reorder, join, preview, and export multiple audio clips locally.                                                            |
| [Presentation Remote](https://github.com/ttomohisa/htmlapps-presentation-remote)           | Open a local PPTX or PDF on a computer and control it from a phone over direct WebRTC, including Presenter View.                         |
| [Presentation Video Maker](https://github.com/ttomohisa/htmlapps-presentation-video-maker) | Turn a PPTX deck into a narrated MP4 using speaker notes, local speech, recordings, audio files, subtitles, and BGM.                     |
| [Gesture Presentation](https://github.com/ttomohisa/htmlapps-gesture-presentation)         | Present PDFs or images and move between pages with local hand-gesture recognition or a direct WebRTC phone remote.                       |
| [FFmpeg Filter Builder](https://github.com/ttomohisa/htmlapps-ffmpeg-filter-builder)       | Build FFmpeg video/audio/text filter graphs as editable nodes, preview them locally, render video, and generate desktop FFmpeg commands. |
| [Music Practice Kit](https://github.com/ttomohisa/htmlapps-music-practice-kit)             | Combine a tuner, metronome, TAP BPM, drone tone, practice timer, recorder, and spectrum analyzer in one app.                             |

### 🗃️ Data, databases & developer tools

| Project                                                                                                                                                 | What it does                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [SQLite Explorer](https://github.com/ttomohisa/htmlapps-sqlite-explorer)                                                                                | Explore SQLite databases with table browsing, schema and relationship views, profiling, read-only SQL, and query-plan analysis.                 |
| [Database Explorer for DuckDB](https://github.com/ttomohisa/htmlapps-duckdb-explorer)                                                                   | Explore local DuckDB databases with schema inspection, paged data, column profiling, guarded SQL, data dictionaries, and structural comparison. |
| [JSON / YAML / CSV Viewer](https://github.com/ttomohisa/htmlapps-json-yaml-csv-viewer)                                                                  | Inspect, search, profile, check, and convert JSON, YAML, CSV, TSV, and JSON Lines locally.                                                      |
| [JSONL Viewer](https://github.com/ttomohisa/htmlapps-jsonl-viewer)                                                                                      | Inspect JSONL / NDJSON files, find malformed lines, review field/type consistency, and page through records without materializing everything.   |
| [HTML Parquet Viewer](https://github.com/ttomohisa/html-parquet-viewer)                                                                                 | Inspect Parquet schemas and browse data as a table without uploading the file.                                                                  |
| [ORC Viewer](https://github.com/ttomohisa/htmlapps-orc-viewer)                                                                                          | Inspect Apache ORC schema, stripes, statistics, metadata, compression, and paged data.                                                          |
| [Arrow Viewer](https://github.com/ttomohisa/htmlapps-arrow-viewer)                                                                                      | Inspect Apache Arrow IPC File / Stream schema, metadata, record batches, dictionaries, and paged data.                                          |
| [Avro Viewer](https://github.com/ttomohisa/htmlapps-avro-viewer)                                                                                        | Inspect Avro Object Container Files, including schema, metadata, block layout, logical types, codecs, and records.                              |
| [DBF Viewer](https://github.com/ttomohisa/htmlapps-dbf-viewer)                                                                                          | Inspect DBF structures and records, switch legacy text encodings, and read DBT/FPT memo data.                                                   |
| [Archive Explorer](https://github.com/ttomohisa/htmlapps-archive-explorer)                                                                              | Explore, preview, analyze, and extract files from ZIP, 7z, RAR5, TAR, GZIP, CAB, ISO, and LZH/LHA archives.                                     |
| [Schema Diff](https://github.com/ttomohisa/htmlapps-schema-diff)                                                                                        | Compare schemas across Parquet, CSV, TSV, JSONL, and NDJSON files and flag potentially breaking changes.                                        |
| [Test Data Generator](https://github.com/ttomohisa/htmlapps-test-data-generator)                                                                        | Generate reproducible normal, missing, boundary, and invalid test data at large scale from a configurable schema and seed.                      |
| [Developer Toolbox](https://github.com/ttomohisa/htmlapps-developer-toolbox) / [original repo](https://github.com/ttomohisa/httpapps-developer-toolbox) | Put Base64, JSON, JWT, cron, regex, hashes, timestamps, text conversion, and dozens of developer utilities into one HTML file.                  |
| [Engineering Calculator](https://github.com/ttomohisa/htmlapps-engineering-calculator)                                                                  | Provide mechanical, manufacturing, fluid, thermal, electrical, tolerance, and unit-conversion calculations with parameter sweeps and graphing.  |
| [Text Inspector](https://github.com/ttomohisa/htmlapps-text-inspector)                                                                                  | Go beyond character counting with composition analysis, frequent words, long-sentence detection, writing checks, and an X-Ray view.             |
| [Markdown Preview Lab](https://github.com/ttomohisa/htmlapps-markdown-preview-lab)                                                                      | Write Markdown locally and compare GitHub-, Qiita-, and Zenn-inspired previews and compatibility hints.                                         |
| [Handy Convert](https://github.com/ttomohisa/htmlapps-handy-convert)                                                                                    | Handle everyday date differences, date arithmetic, time zones, Japanese eras, kana conversion, and full-/half-width text conversion.            |
| [Temporary Links](https://github.com/ttomohisa/htmlapps-temporary-links)                                                                                | Keep a disposable local work queue of web links, `file:///` URLs, Windows paths, and UNC paths.                                                 |

### 📱 Device, field & everyday utilities

| Project                                                                          | What it does                                                                                                                                  |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| [Wireless Sensor](https://github.com/ttomohisa/htmlapps-wireless-sensor)         | Connect up to four smartphones as synchronized wireless motion sensors over direct WebRTC, with FFT, impact timing, experiments, and reports. |
| [Device Check](https://github.com/ttomohisa/htmlapps-device-check)               | Check camera, microphone, speakers, display, keyboard, pointer/touch input, gamepads, and motion sensors in one place.                        |
| [QR Reader](https://github.com/ttomohisa/htmlapps-qr-reader)                     | Scan QR codes from a live camera or existing images, with smartphone-first controls and local history.                                        |
| [Wi-Fi Share](https://github.com/ttomohisa/htmlapps-wifi-share)                  | Share Wi-Fi details by QR code and related methods, create an A4 Wi-Fi sign, and optionally write NFC tags on supported devices.              |
| [Pocket Level](https://github.com/ttomohisa/htmlapps-pocket-level)               | Turn a smartphone into a spirit level / inclinometer with zeroing, hold, averaging, and two-point calibration.                                |
| [Way Back](https://github.com/ttomohisa/htmlapps-way-back)                       | Save a location and find your way back using a direction arrow and straight-line distance without requiring a map.                            |
| [Pocket Teleprompter](https://github.com/ttomohisa/htmlapps-pocket-teleprompter) | Use a phone as an installation-free teleprompter with automatic scrolling and local script saving.                                            |
| [Signal Screen](https://github.com/ttomohisa/htmlapps-signal-screen)             | Turn a phone or computer display into a highly visible sign using large text, arrows, colors, and QR codes.                                   |
| [Tap Counter](https://github.com/ttomohisa/htmlapps-tap-counter)                 | A smartphone-friendly tally counter for people, inventory, laps, repetitions, and multiple categories.                                        |
| [Pomodoro Timer](https://github.com/ttomohisa/htmlapps-pomodoro-timer)           | A local-first focus timer with Picture-in-Picture, distraction counting, flow overtime, and local session history.                            |

### ✅ Workflow, events & group tools

| Project                                                                           | What it does                                                                                                                            |
| --------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [Check-in Desk](https://github.com/ttomohisa/htmlapps-check-in-desk)              | Maintain a reusable roster, run check-in or entry/exit sessions, review attendance history, and export CSV/JSON locally.                |
| [Pop-up Face Check-in](https://github.com/ttomohisa/htmlapps-popup-face-check-in) | Run temporary event reception with local face matching, manual fallback, attendance history, and encrypted portable registration files. |
| [Pass-the-Phone Vote](https://github.com/ttomohisa/htmlapps-pass-the-phone-vote)  | Pass one phone around a group for private voting and reveal only aggregate results after everyone has voted.                            |
| [Task Packing](https://github.com/ttomohisa/htmlapps-task-packing)                | Give tasks a physical size and fit only what actually fits onto a finite-capacity visual board.                                         |
| [Restock List](https://github.com/ttomohisa/htmlapps-restock-list)                | Manage recurring household purchases with simple In stock / Low / Out states that automatically build the shopping list.                |
| [Random Picker](https://github.com/ttomohisa/htmlapps-random-picker)              | Pick candidates, randomize order, create balanced teams, or run an animated wheel from a simple list.                                   |

### 🧪 Experiments

| Project                                                                   | What it does                                                                                                   |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| [Optical File](https://github.com/ttomohisa/htmlapps-optical-file-camera) | Turn a small file into an Animated QR WebP and reconstruct it by camera scanning or direct WebP decoding.      |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo)        | Create customizable offline meeting-jargon bingo cards, including a floating Document Picture-in-Picture mode. |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)          | Play Minesweeper in a normal page or floating Document Picture-in-Picture window.                              |

## 🧩 WebAssembly & build infrastructure

The applications are only one side of the work.

I'm also building infrastructure to compile native software for browsers, reduce WebAssembly runtimes for specific applications, verify the resulting binaries, and distribute them reproducibly.

| Project                                                                          | What it does                                                                                                                                                                                                     |
| -------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template)       | A reusable repository template for building, verifying, packaging, and publishing self-contained browser applications.                                                                                           |
| [FFmpeg WASM Builder](https://github.com/ttomohisa/htmlapps-ffmpeg-wasm-builder) | Build application-specific FFmpeg WebAssembly cores from pinned sources, including video compression, cutting, inspection, speed changes, animation export, and filter-graph processing.                         |
| [OpenCV WASM Builder](https://github.com/ttomohisa/htmlapps-opencv-wasm-builder) | Compose logical OpenCV components into purpose-specific OpenCV.js / WASM profiles for browser applications.                                                                                                      |
| [DuckDB WASM Builder](https://github.com/ttomohisa/htmlapps-duckdb-wasm-builder) | Build and validate pinned DuckDB-Wasm bundles tailored to DuckDB Explorer while measuring size reductions against upstream-equivalent builds.                                                                    |
| [WASM Zoo](https://github.com/ttomohisa/wasm-zoo)                                | Build and distribute current upstream native software for WebAssembly with reproducible recipes, browser smoke tests, capability metadata, checksums, provenance, SBOMs, corresponding source, and npm packages. |

### Purpose-specific WASM

For application runtimes, I prefer to include only the native functionality the tool actually needs.

**FFmpeg WASM Builder** currently covers profiles for:

* Video compression
* Video speed changes
* Lossless cutting
* Media inspection
* Video contact sheets
* Animated GIF / WebP generation
* Visual FFmpeg filter graphs

Most profiles are deliberately single-threaded so they remain usable in ordinary single-HTML applications without requiring `SharedArrayBuffer` or cross-origin isolation. The Filter Builder also has a multi-thread variant for environments where cross-origin isolation is available.

**OpenCV WASM Builder** follows a component model around capabilities such as image processing, feature matching, geometry, calibration, optical flow, markers, face processing, and stitching.

**DuckDB WASM Builder** keeps the DuckDB browser runtime internally consistent by producing the JavaScript wrapper, Worker, and WASM from the same pinned source build rather than swapping a WASM binary in isolation.

### WASM Zoo

**[WASM Zoo](https://github.com/ttomohisa/wasm-zoo)** takes the opposite approach.

Purpose-specific builders intentionally remove unnecessary functionality. WASM Zoo instead aims to preserve a broad, recognizable upstream program/API shape when a reusable distribution is more useful.

Current package families include:

| Package         | Distribution focus                                  |
| --------------- | --------------------------------------------------- |
| **FFmpeg**      | Broad browser FFmpeg CLI builds                     |
| **libarchive**  | `bsdtar`, `bsdcpio`, `bsdcat`, and `bsdunzip`       |
| **ImageMagick** | Browser build of the upstream `magick` CLI          |
| **libvips**     | Browser-oriented libvips builds                     |
| **Ghostscript** | Browser build for PostScript/PDF processing         |
| **jq**          | Browser build of the jq command-line JSON processor |

All six package families are also being distributed through the **`@wasm-zoo` npm scope**.

A Zoo package is expected to provide more than a `.wasm` binary:

* Exact upstream source and toolchain revisions
* Reproducible build scripts
* Real browser runtime smoke tests
* Machine-readable manifests and capability information
* Upstream freshness tracking
* Release-health monitoring
* SHA-256 checksums
* License notices
* Corresponding source archives
* in-toto / SLSA provenance
* CycloneDX SBOMs
* Interactive browser playgrounds

## 💡 Development approach

* **Local-first processing**
  Keep user-selected files, media, database contents, camera frames, sensor readings, and application data on the device whenever the browser platform allows it.

* **Self-contained delivery**
  Prefer downloadable artifacts that remain useful independently of a permanently hosted application stack.

* **HTML can be more than a page**
  A single HTML file can act as an application, viewer, report, album, or specialized container carrying both content and the software needed to inspect it.

* **Use the browser as an application runtime**
  Take advantage of WebAssembly, Web Workers, WebCodecs, File APIs, Canvas, IndexedDB, Web Audio, camera / microphone / sensor APIs, WebRTC, Document Picture-in-Picture, and other browser capabilities when they provide practical value.

* **Build locally useful AI**
  Small vision and recognition models can be useful when they solve a focused task without requiring image or video uploads.

* **Build small when the application needs small**
  For video, database, and computer-vision tools, purpose-built WebAssembly can reduce unnecessary runtime code and dependencies.

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

* **Cloud & data engineering:** Azure, Databricks, Parquet, ORC, Arrow, Avro, DuckDB, SQLite
* **Browser applications:** HTML, CSS, JavaScript, WebAssembly, Web Workers, WebCodecs
* **Local processing:** PDFs, Office files, images, video, audio, archives, databases, structured data
* **Computer vision & local AI:** OpenCV, ONNX Runtime Web, YuNet, SFace, TinyCLIP
* **Browser APIs:** File APIs, Canvas, Web Audio, Media Capture, sensors, WebRTC, IndexedDB, Picture-in-Picture
* **WebAssembly:** FFmpeg, OpenCV, DuckDB, Emscripten, libarchive, ImageMagick, libvips, Ghostscript, jq
* **Build & automation:** PowerShell, Docker, GitHub Actions, GitHub Pages, reproducible builds, browser smoke testing

## 📫 Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
