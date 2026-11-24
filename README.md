# Font Manipulator — PoseNet Setup

A webcam and PoseNet setup for a planned gesture-controlled font tool.

**Repository created:** 2022-08-05  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-08-04

## Features and implementation

- Camera capture.
- P5.js canvas.
- Model initialization.
- Pose callback scaffolding.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `main.js`: `gotPoses()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/font-manipulator-2.git
cd font-manipulator-2
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access and inspect model loading.

## Current status and limitations

The callback references an undeclared `results` parameter and the canvas does not render adjustable text yet.

## Related project snapshots

Other repositories in this project family:
- [font-manipulator-1](https://github.com/Avenger-Sonic123/font-manipulator-1) — repository created 2022-07-28
- [Font-manipulator3](https://github.com/Avenger-Sonic123/Font-manipulator3) — repository created 2022-08-28

---

Source reference: [`7ef203cc`](https://github.com/Avenger-Sonic123/font-manipulator-2/tree/7ef203cc56417100e25e1306baec4f9be3a1a92d) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
