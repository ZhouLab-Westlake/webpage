# Zhou Lab Website

Multiscale Molecular Organization and Function Lab at Westlake University, School of Life Sciences.

**PI:** Huabin Zhou, Ph.D.  
**Contact:** zhouhuabin@westlake.edu.cn

## About

Single-page lab website built with the Design Components (DC) framework. Self-contained in `Zhou Lab Website.dc.html` — no build step required.

## Viewing

```bash
open "Zhou Lab Website.dc.html"       # macOS
python3 -m http.server 8080           # any static server
```

Then visit `http://localhost:8080/Zhou%20Lab%20Website.dc.html`.

## Structure

```
Zhou Lab Website.dc.html    # Main site (HTML + React logic + inline styles)
support.js                  # DC framework runtime (generated, do not edit)
uploads/                    # Images referenced by the site
reference/                  # Source design files (poster PDF/PPTX)
```
