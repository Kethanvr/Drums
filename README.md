# Drum Kit

A small browser drum pad built with HTML, CSS, and vanilla JavaScript. Click a pad or press its matching key to play a drum sample.

| Key | Sound |
| --- | --- |
| `w` | Tom 1 |
| `a` | Tom 2 |
| `s` | Tom 3 |
| `d` | Tom 4 |
| `j` | Snare |
| `k` | Crash |
| `l` | Kick bass |

## Run locally

No package install is required. Open `index.html` in a browser, or serve the folder with a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`. The sound files are read from `sounds/` relative to the page.
