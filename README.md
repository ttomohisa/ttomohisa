# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

Outside of that, I build practical browser tools that keep as much processing as possible on the user's device. Many of them are distributed as a self-contained HTML file, so they can be opened directly, used without an account, and kept around without depending on a backend service.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a collection of my browser-based tools.

## Browser tools

I like treating the browser as a lightweight local application runtime: files, cameras, sensors, audio, databases, WebAssembly, workers, and local storage are all useful building blocks when they make a tool simpler to use and easier to distribute.

Recent projects generally share a few ideas: local-first processing, self-contained delivery, Japanese / English UI, reproducible builds, and GitHub Pages demos.

### Documents, images, and media

| Project                                                                                          | What it does                                                                                                                              |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| [Submission PDF Scanner](https://github.com/ttomohisa/htmlapps-document-scanner)                 | Capture paper documents, correct perspective, organize pages, apply A4 / B&W / file-size requirements, and export a submission-ready PDF. |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                                 | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                                                     |
| [Image Compressor & Converter](https://github.com/ttomohisa/htmlapps-image-compressor-converter) | Compress, resize, convert, compare, and export PNG, JPEG, and WebP images, including batch and target-size workflows.                     |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)                 | Compress video locally with ffmpeg.wasm, including resolution, codec, bitrate, frame-rate, and audio controls.                            |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor)           | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                                                   |
| [Private Face Redactor](https://github.com/ttomohisa/htmlapps-private-face-redactor)             | Detect and redact faces locally using YuNet and ONNX Runtime Web, with automatic and manual masks.                                        |
| [QR Reader](https://github.com/ttomohisa/htmlapps-qr-reader)                                     | Scan QR codes from a live camera or existing images, with local history and smartphone-first controls.                                    |
| [GIF Optimizer](https://github.com/ttomohisa/htmlappps-gif-optimizer)                            | Optimize animated GIFs directly in the browser to reduce file size.                                                                       |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)                      | Convert images to WebP and generate Base64 data URIs.                                                                                     |

### Data, writing, and workflow

| Project                                                                                | What it does                                                                                                                            |
| -------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [SQLite Explorer](https://github.com/ttomohisa/htmlapps-sqlite-explorer)               | Explore SQLite databases locally with table browsing, schema and relationship views, profiling, read-only SQL, and query-plan analysis. |
| [JSON / YAML / CSV Viewer](https://github.com/ttomohisa/htmlapps-json-yaml-csv-viewer) | Inspect, search, profile, check, and convert JSON, YAML, CSV, TSV, and JSON Lines locally.                                              |
| [HTML Parquet Viewer](https://github.com/ttomohisa/html-parquet-viewer)                | Inspect Parquet schemas and browse data as a table without uploading the file.                                                          |
| [Markdown Preview Lab](https://github.com/ttomohisa/htmlapps-markdown-preview-lab)     | Write Markdown locally and compare GitHub-, Qiita-, and Zenn-inspired previews and compatibility hints.                                 |
| [Temporary Links](https://github.com/ttomohisa/htmlapps-temporary-links)               | Keep a disposable local queue of web links, file URLs, Windows paths, and UNC paths.                                                    |

### Device and practice tools

| Project                                                                        | What it does                                                                                                    |
| ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- |
| [Pocket Level](https://github.com/ttomohisa/htmlapps-pocket-level)             | Turn a smartphone into a spirit level / inclinometer with zeroing, hold, averaging, and two-point calibration.  |
| [Music Practice Kit](https://github.com/ttomohisa/htmlapps-music-practice-kit) | Combine a tuner, metronome, TAP BPM, drone, practice timer, recorder, and spectrum analyzer in one browser app. |

### Small experiments

| Project                                                            | What it does                                                                                            |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo) | Create customizable offline meeting-jargon bingo cards, including a floating-window mode.               |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)   | Play a self-contained Minesweeper game in a normal page or floating Document Picture-in-Picture window. |

### Build your own single-HTML app

| Project                                                                    | What it does                                                                                                                                                           |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template) | A reusable repository template for building, verifying, packaging, and publishing self-contained browser apps, including an optional gzip self-extracting HTML output. |

## Development approach

* **Local-first processing:** Keep user-selected files, media, and application data on the device whenever the browser platform allows it.
* **Self-contained delivery:** Prefer a downloadable HTML artifact that remains useful independently of a hosted application stack.
* **Browser capabilities first:** Use WebAssembly, Web Workers, File APIs, Canvas, IndexedDB, camera / microphone / sensor APIs, and Document Picture-in-Picture where they provide practical value.
* **Reproducible builds:** Pin third-party dependencies, embed only required assets, and record hashes or notices where appropriate.
* **Minimal runtime network use:** Avoid runtime CDNs, remote APIs, analytics, and telemetry where practical.
* **Simple maintenance:** Favor readable source, Windows-friendly PowerShell builds, automated verification, and GitHub Pages deployment.

## Skills and interests

* **Cloud and data:** Azure, Databricks, Parquet, MLflow, IoT, data engineering
* **Browser applications:** HTML, CSS, JavaScript, WebAssembly, Web Workers, local file / media processing
* **Delivery and automation:** GitHub Actions, GitHub Pages, PowerShell-based standalone builds

## Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
