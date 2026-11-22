# CJMR Tech Company Website

Static website for CJMR Tech Company and **PETsalamat**, a reverse vending machine that verifies empty PET bottles with computer vision (YOLO) and a liquid sensor, and rewards residents with points on RFID cards that they can redeem for coins.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Adding photos

The placeholders disappear automatically once the image files exist.

| Section  | File path                                   | Recommended size     |
|----------|---------------------------------------------|----------------------|
| Founders | `assets/images/founders/founder-1.jpg` … `founder-4.jpg` | 600 × 600 (2×2 / square) |
| Events   | `assets/images/events/event-1.jpg`, `event-2.jpg`        | 1200 × 800 (3:2)     |

Founder names and event details are in `index.html`.

## Structure

```
index.html
css/styles.css
js/main.js
assets/images/
```
