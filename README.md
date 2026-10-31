# Charmaine Chui — `incubated-geek-cc`

**Offline-first, zero-install tooling.** Software that runs in a browser tab or a single
executable, needs no server, no account, and no licence — because the environments I build
for often can't have any of those.

Data Analyst and software developer, seven years embedded at Singapore's Ministry of Health.
Most of what I ship publicly is the generalised, non-confidential form of a problem I hit at
work: extracting data from files nobody wants to open by hand, running a model where there's
no GPU, or replacing a commercial licence with 200 lines of JavaScript. I keep the use-cases
deliberately generic so they're reusable — that's the point of publishing them.

📍 Singapore · [Medium](https://medium.com/@geek-cc) · [LinkedIn](https://www.linkedin.com/in/chui-charmaine-15133282) · [Tableau Public](https://public.tableau.com/app/profile/charmaine.chui/vizzes)

---

## Featured work

### 🎙️ [whisper-onnx](https://github.com/incubated-geek-cc/whisper-onnx)
Speech-to-text that never leaves your machine. Runs OpenAI Whisper as ONNX models in the
browser on WebGPU, falling back to WebAssembly where WebGPU isn't available. Genuinely
offline — the ONNX Runtime artifacts are bundled rather than fetched from a CDN, which is
why most published examples still break without a network connection.
`TypeScript · onnxruntime-web · WebGPU · WASM`

### 🗃️ [SQLiteBrowserUtility](https://github.com/incubated-geek-cc/SQLiteBrowserUtility)
Inspect a `.sqlite` file by dragging it into a browser tab. No install, no server, no admin
rights — which matters on locked-down corporate and government machines where you can't get
DB Browser approved but still need to read a database today.
`JavaScript · sql.js (WASM)`

### 🔊 [Text-To-Speech-App](https://github.com/incubated-geek-cc/Text-To-Speech-App)
Point it at an image of text and it reads the text aloud. Tesseract.js OCR feeding the Web
Speech API, packaged as a portable offline app. Built as an accessibility tool that works
without connectivity.
`JavaScript · Tesseract.js · Web Speech API`

### 🚌 [sg-transportation](https://github.com/incubated-geek-cc/sg-transportation)
Live bus arrival times and route geometry for Singapore, on a map, from LTA's open API.
A working reference for anyone wiring a realtime transit feed to a Leaflet frontend.
`JavaScript · Leaflet · LTA DataMall API`

### 🧠 [mindful-predictions](https://github.com/incubated-geek-cc/mindful-predictions)
Predicts likelihood of seeking mental-healthcare treatment from survey features. A deployed
regression model rather than a notebook — mental-health analytics is a long-running interest
of mine, and this is the publicly shareable version of it.
`Python · Flask · scikit-learn`

### ☕ [Tess4JOcrApp](https://github.com/incubated-geek-cc/Tess4JOcrApp) · [data-extraction-with-Java](https://github.com/incubated-geek-cc/data-extraction-with-Java)
The Java pair I reference most often across my writing. Portable Tesseract OCR via Tess4J, and
programmatic extraction from Excel and Outlook files. Together they cover the unglamorous
backbone of most automation work: getting text out of formats that resist it, on a machine
where you can't install anything.
`Java · Tess4J · Apache POI`

---

## What I write about

**Close to 100 posts since 2020, and still going.** Most start from something I hit at work
and couldn't solve with what was already installed, so I publish the generalised,
non-confidential version — **79% ship a linked repository or a live demo**, because a post
without runnable code hasn't really explained anything.

In *Towards Data Science*, *JavaScript in Plain English*, *Data Science Collective*,
*Geek Culture* and *Webtips*.

| Theme | What it covers |
|---|---|
| **Java tooling** | OCR, file extraction, runnable JAR packaging, Swing desktop apps |
| **Client-side JS utilities** | Canvas, SVG, encoding/decoding, format conversion — all browser-only |
| **Browser & offline ML** | ONNX and WASM inference, Whisper, math OCR, local LLMs |
| **DevOps & deployment** | Packaging, deployment, API key handling, Git workflow |
| **Geospatial** | Leaflet, Turf.js, offline basemaps, format conversion, Tableau mapping |

📓 **[26 live browser demos](https://github.com/incubated-geek-cc?tab=repositories)** — QR and
barcode generation, HTML entity encoding, SVG→PNG, raster→vector tracing, geospatial format
conversion (KML/SHP/GeoJSON), and more. All client-side, all runnable without a backend.

---
