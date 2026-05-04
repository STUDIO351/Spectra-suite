# ⬡ SPECTRA SUITE
### Forensic Intelligence Tools — Audio · Image · Video

> **ONE SYSTEM. MULTIPLE MODES.**  
> Professional-grade forensic media analysis. No downloads. No installs. Works on any phone, right now.

🔗 **[Launch SPECTRA SUITE →](https://yourusername.github.io/spectra-suite)**

---

## The Suite

| Tool | Version | Purpose |
|------|---------|---------|
| **SPECTRA** | v4.6 | Forensic Audio — EQ, noise removal, transcription |
| **LENS** | v4.6 | Forensic Image — enhancement, stacking, zoom analysis |
| **PRISM** | v1.0 | Forensic Video — frame stepping, filters, AI description |

---

## What It Does

**SPECTRA — Forensic Audio**
- 8-band parametric EQ tuned to human voice frequencies
- Real-time spectrum analyzer with hum / static / voice zone markers
- Noise filters: hum removal, static reduction, voice isolation, reverb reduction
- Playback speed control 0.25× – 2×
- Snippet capture and WAV export
- AI-powered transcription via Claude
- Live transcription via Web Speech API

**LENS — Forensic Image**
- Synthetic image stacking (1–100 layers) to reduce noise and reveal detail
- Deglare and surface flattening for reflective surfaces and screen photos
- Unsharp mask sharpening + Sobel edge recovery
- Moveable zoom loupe up to 8× magnification
- Draggable before/after split view
- Offset layer with pixel-nudge for alignment
- Lossless PNG export

**PRISM — Forensic Video**
- Frame-by-frame stepping (±1, ±5, ±10 frames)
- Real-time speed control (0.25× – 2×)
- Touch scrubber with loop region playback
- Zoom loupe on live video frames
- Visual enhancement filters: brightness, contrast, saturation, sharpen, denoise
- Forensic presets: Night Shot, License Plate, Face Detail, and more
- Frame burst capture and PNG/JPEG export
- Timestamp embed on exported frames
- AI frame description via Claude

---

## Key Features

- **Zero uploads** — all processing happens on your device. Files never leave your phone.
- **No installs** — open a link and start working. Nothing to download.
- **Mobile-first** — built for phones. Touch-optimized UI, 50px tap targets, no horizontal scroll.
- **No account required** — free during beta, no sign-up needed.
- **PWA ready** — add to Home Screen on iOS or Android for near-native experience.
- **Evidence protection** — built-in guards against accidental evidence loss on page reload or desktop/mobile toggle.

---

## Who It's For

- 🔍 Private investigators needing field analysis without a lab
- ⚖️ Legal professionals and self-represented parties documenting evidence
- 📰 Journalists and reporters cleaning field recordings and photos
- 👨‍👩‍👧 Families documenting custody violations or abuse
- 🏛️ Law enforcement needing quick supplemental analysis
- 🎙️ Content creators needing fast audio cleanup and image enhancement

---

## Technical Architecture

```
spectra-suite/
├── index.html            ← Suite homepage
├── SPECTRA_v4_6.html     ← Forensic Audio tool
├── LENS_v4_6.html        ← Forensic Image tool
└── PRISM_v1_2.html       ← Forensic Video tool
```

**Stack:**
- Vanilla JavaScript — zero frameworks, zero npm dependencies
- Web Audio API (SPECTRA)
- Canvas 2D API (LENS)
- HTMLVideoElement (PRISM)
- Anthropic Claude API for AI features (user-initiated only)
- Single HTML file per tool — drag-and-drop deployable

**Privacy:**
- Zero-upload architecture
- No cookies, no analytics, no telemetry
- All media processed client-side in browser memory
- Only external calls: Google Fonts + Anthropic API (optional, user-triggered)
- Closing the tab destroys all session data

---

## Deploying Your Own Instance

1. Fork or download this repository
2. Upload all files to any static host (Netlify, Vercel, GitHub Pages)
3. No build step. No configuration. It just works.

**GitHub Pages:**
- Settings → Pages → Deploy from branch → main → / (root) → Save
- Live at `https://yourusername.github.io/spectra-suite`

**Vercel:**
- Import this repo at vercel.com → auto-deploys on every push

---

## Roadmap

- [x] SPECTRA v4.6 — Audio forensics
- [x] LENS v4.6 — Image forensics  
- [x] PRISM v1.2 — Video forensics
- [ ] SPECTRA v4.7 — Batch clip export, waveform zoom
- [ ] LENS v4.7 — EXIF metadata display, multi-image compare
- [ ] PRISM v1.1 — Motion detection, frame diff overlay
- [ ] TRACE — Metadata forensics, GPS mapping, device fingerprint
- [ ] Suite Portal — Case management, saved sessions, team sharing

---

## Beta

SPECTRA SUITE is currently in **open beta**. Core tools are free.  
Feedback, bug reports, and feature requests welcome via GitHub Issues.

---

*Built with precision. Deployed with purpose.*  
**SPECTRA SUITE — ONE SYSTEM. MULTIPLE MODES.**
