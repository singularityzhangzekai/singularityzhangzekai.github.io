---
title: "Space-Acoustic-Analyzer"
collection: portfolio
permalink: /portfolio/space-acoustic-analyzer/
excerpt: "A browser-based room acoustics tool with 3D room visualization, spectral-response analysis, diagnostic reports, acoustic-treatment suggestions, and recommended EQ adjustments."
---

Space-Acoustic-Analyzer is a browser-based room acoustics project that combines a three-dimensional room view with spectral-response analysis and diagnostic reporting. Users enter room dimensions, reverberation time, and speaker and listener positions to explore modeled room modes and associated treatment and equalizer suggestions.

[View repository and documentation](https://github.com/singularityzhangzekai/Space-Acoustic-Analyzer)

## Functionality

- An interactive 3D room view with speaker and listener positions, rotation, and zoom.
- Spectral-response visualization of modeled axial, tangential, and oblique room modes, with a Schroeder-frequency marker.
- Diagnostic reports for significant modeled peaks and nulls, including acoustic-treatment and placement suggestions.
- Recommended EQ cuts for modeled peaks and text export of filter parameters for REW/DSP workflows.
- A Chinese and English interface.

## Technologies and implementation

**HTML, CSS, JavaScript, ECharts, and Three.js with OrbitControls.** The application is implemented in a standalone HTML file. JavaScript calculates room-mode frequencies and speaker/listener coupling; ECharts renders the spectral chart, while Three.js provides the room visualization.

The displayed response and recommendations come from the application's room model and user-entered geometry and reverberation time. The repository does not report measured acoustic improvements or validation results.

## Screenshots

<figure>
  <img src="https://github.com/user-attachments/assets/c225a3f2-d177-4c79-a6de-a2e7a5926b23" alt="Space Acoustic Analyzer showing a 3D room, speaker and listener positions, and room-dimension inputs" loading="lazy">
  <figcaption>Room visualization and input interface from the project's README.</figcaption>
</figure>

<figure>
  <img src="https://github.com/user-attachments/assets/1213aa26-44e0-412f-88cd-108427d53fb3" alt="Spectral-response chart and diagnostic cards with acoustic-treatment and EQ recommendations" loading="lazy">
  <figcaption>Spectral analysis and diagnostic report from the project's README.</figcaption>
</figure>

## Sources

- [Project README and screenshots](https://github.com/singularityzhangzekai/Space-Acoustic-Analyzer/blob/9e796f2ebdcbdca8a1029823c66bbbc70bd78b90/README.md).
- [Application source](https://github.com/singularityzhangzekai/Space-Acoustic-Analyzer/blob/9e796f2ebdcbdca8a1029823c66bbbc70bd78b90/index.html), supporting the technology and implementation details above.
