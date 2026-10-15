---
title: "Web-DICOM-Viewer"
collection: portfolio
permalink: /portfolio/web-dicom-viewer/
excerpt: "An OHIF and Orthanc-based medical imaging viewer with DICOM upload, study browsing, and browser-based image viewing through DICOMweb."
---

Web-DICOM-Viewer integrates the OHIF Viewer with Orthanc to support a web-based medical imaging workflow: upload local DICOM studies, browse the study list, and open images in the browser through DICOMweb.

[View repository and documentation](https://github.com/singularityzhangzekai/Web-DICOM-Viewer)

## Functionality

- Local DICOM upload and testing with Orthanc.
- Study list browsing and browser-based medical image viewing.
- Custom OHIF configuration for an Orthanc DICOMweb data source.
- A documented Nginx static-hosting and reverse-proxy architecture connecting the browser, OHIF, Orthanc, and DICOM storage.

## Technologies and implementation

**OHIF Viewer, Orthanc, DICOMweb, Nginx, Yarn, and Bun.** The repository documents an Orthanc development workflow and a production build using a custom OHIF configuration. DICOMweb requests use the `/pacs/dicom-web` and `/pacs/wado` proxy paths.

The README records local OHIF–Orthanc integration, DICOM upload testing, and verification of the study list and viewer workflow. Deployment configuration, custom branding, toolbar optimization, and authentication/HTTPS support remain on its roadmap.

## Screenshot

<figure>
  <img src="https://github.com/user-attachments/assets/c9a00481-8fdf-4f06-8575-9481c500e57b" alt="OHIF viewer displaying CT slices and a three-dimensional rendering in a multi-panel layout" loading="lazy">
  <figcaption>Viewer interface reproduced from the project's README preview.</figcaption>
</figure>

## Source

Description, technologies, implementation details, and screenshot: [project README](https://github.com/singularityzhangzekai/Web-DICOM-Viewer/blob/8e59fcaf5ac2d8bc1a63f9e57f9c83c7da854ab7/README.md).
