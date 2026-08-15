# Hi, I'm Tomohisa 👋

I work in cloud architecture and data engineering, mainly with Azure and Databricks.

I also build small, privacy-conscious browser tools that solve practical problems without requiring an application server. Most projects are distributed as a self-contained HTML file and process files and data locally on the user's device.

🌐 **[Browser Kitty](https://browser-kitty.com/)** — a growing collection of my browser-based tools.

## Browser tools

The goal is not to use only “vanilla” technology. I prefer the simplest architecture that keeps an app portable, inspectable, and easy to preserve. Depending on the problem, a project may embed libraries, WebAssembly binaries, workers, fonts, or machine-learning models directly into the generated HTML.

Many projects include Japanese and English interfaces, downloadable standalone HTML files, and GitHub Pages demos.

### Documents, images, and media

| Project                                                                                | What it does                                                                                                   |
| -------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| [PDF Organizer](https://github.com/ttomohisa/html-pdf-organizer)                       | Reorder, rotate, remove, merge, preview, and export PDF pages locally in the browser.                          |
| [QR Reader](https://github.com/ttomohisa/htmlapps-qr-reader)                           | Scan QR codes from a live camera or existing images, with local history and smartphone-first controls.         |
| [Local Video Compressor](https://github.com/ttomohisa/htmlapps-video-compressor)       | Compress video locally with ffmpeg.wasm, including resolution, codec, bitrate, frame-rate, and audio controls. |
| [Office Image Extractor](https://github.com/ttomohisa/htmlapps-office-image-extractor) | Extract embedded images from Word, Excel, and PowerPoint files in bulk.                                        |
| [Private Face Redactor](https://github.com/ttomohisa/htmlapps-private-face-redactor)   | Detect and redact faces locally using YuNet and ONNX Runtime Web, with automatic and manual masks.             |
| [GIF Optimizer](https://github.com/ttomohisa/htmlappps-gif-optimizer)                  | Optimize animated GIFs directly in the browser to reduce file size.                                            |
| [Image to WebP / Base64](https://github.com/ttomohisa/image-to-webp-base64)            | Convert images to WebP and generate Base64 data URIs.                                                          |

### Data, writing, and workflow

| Project                                                                                | What it does                                                                                            |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| [JSON / YAML / CSV Viewer](https://github.com/ttomohisa/htmlapps-json-yaml-csv-viewer) | Inspect, search, profile, check, and convert JSON, YAML, CSV, TSV, and JSON Lines locally.              |
| [HTML Parquet Viewer](https://github.com/ttomohisa/html-parquet-viewer)                | Inspect Parquet schemas and browse data as a table without uploading the file.                          |
| [Markdown Preview Lab](https://github.com/ttomohisa/htmlapps-markdown-preview-lab)     | Write Markdown locally and compare GitHub-, Qiita-, and Zenn-inspired previews and compatibility hints. |
| [Temporary Links](https://github.com/ttomohisa/htmlapps-temporary-links)               | Keep a disposable local queue of web links, file URLs, Windows paths, and UNC paths.                    |

### Small experiments and utilities

| Project                                                            | What it does                                                                                            |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| [Jargon Bingo](https://github.com/ttomohisa/htmlapps-jargon-bingo) | Create customizable offline meeting-jargon bingo cards, including a floating-window mode.               |
| [Mine Window](https://github.com/ttomohisa/htmlapps-mine-window)   | Play a self-contained Minesweeper game in a normal page or floating Document Picture-in-Picture window. |

### For building more single-HTML apps

| Project                                                                    | What it does                                                                                                                                                           |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Single HTML App Template](https://github.com/ttomohisa/htmlapps-template) | A reusable repository template for building, verifying, packaging, and publishing self-contained browser apps, including an optional gzip self-extracting HTML output. |

## Development approach

* **Self-contained delivery:** Prefer a downloadable HTML file over a permanently hosted application stack.
* **Local-first processing:** Keep user-selected files and application data on the device whenever the browser platform allows it.
* **Reproducible builds:** Pin third-party dependencies, embed only required assets, and record hashes or notices where appropriate.
* **Browser capabilities first:** Use WebAssembly, Web Workers, File APIs, Canvas, IndexedDB, camera APIs, and Document Picture-in-Picture when they provide practical value.
* **Minimal runtime dependencies:** Avoid runtime CDNs, remote APIs, analytics, and telemetry where practical.
* **Simple maintenance:** Favor readable source, Windows-friendly build scripts, automated checks, and GitHub Pages deployment.

## Skills and interests

* **Cloud and data:** Azure, Databricks, Parquet, MLflow, IoT, data engineering
* **Browser applications:** HTML, CSS, JavaScript, WebAssembly, Web Workers, local file processing
* **Delivery and automation:** GitHub Actions, GitHub Pages, PowerShell-based standalone builds

## Contact

Bug reports, feature ideas, and pull requests are welcome in the relevant repository.
