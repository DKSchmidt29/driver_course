Here’s a consolidated list of all the resources/URLs referenced in the course, annotated with the relevant **Phase** and **section** (Topics/Resources/Projects). Where something is a talk or PDF tied to multiple phases, I’ve noted all relevant uses.

***

## Phase 1 – Linux driver fundamentals

### Apriorit Linux driver tutorial

- URL: `https://www.apriorit.com/dev-blog/195-simple-driver-for-linux-os`[1]
- Phase: 1 – Resources  
- Step: “Apriorit’s Linux driver development tutorial for a practical C-based starting point.”

### Linux driver video courses (general)

- URL (example course): `https://www.youtube.com/watch?v=iSiyDHobXHA`[2]
  - Title: “Linux Device Drivers Development Course for Beginners”  
  - Phase: 1 – Resources  
  - Step: “A beginner-oriented Linux driver video course for seeing the development flow end to end.”

- URL (graphics-focused clip): `https://www.youtube.com/watch?v=WKH25Iz6Z3M`[3]
  - Title: “Learning Linux Device Drivers Development: Talking about Graphic Drivers”  
  - Phase: 1 – Resources  
  - Step: Same slot; another example of driver-dev video material.

***

## Phase 2 – DRM/KMS foundations

### Xilinx DRM/KMS subsystem guide

- URL: `https://docs.amd.com/r/en-US/ug1442-vck190-base-trd/DRM/KMS-Kernel-Subsystem`[4]
- Phase: 2 – Resources  
- Step: “Xilinx’s DRM/KMS subsystem documentation for a concrete explanation of pipelines and memory handling.”

### Linux GPU Driver Developer’s Guide (Freedesktop)

- URL:  
  - `https://docs.kernel.org/5.19/gpu/index.html`[5]
  - `https://dri.freedesktop.org/docs/drm/gpu.html`[6]
- Phase: 2 – Topics/Resources  
  - Used for GEM/CMA/PRIME/DMABUF, memory management, and synchronization.  
- Also referenced in:
  - Phase 1 – Resources: “begin learning kernel graphics-driver expectations and terminology.”  
  - Phase 4 – Resources: memory sharing and sync analogs.  
  - Phase 5 – Topics: logging/tracing and fault triage.  
  - “Best public resources” table.

### Maxime Ripard – Introduction to Linux DRM subsystem

- URL (talk video): `https://www.youtube.com/watch?v=LbDOCJcDRoo`[7]
- Phase: 2 – Resources  
- Step: “Maxime Ripard’s Linux DRM introduction talk for a conceptual end-to-end map of the stack.”

### Paul Kocialkowski – DRM/KMS driver-side APIs

- URL (talk video): `https://www.youtube.com/watch?v=nNY7NjUIJRA`[8]
- URL (article/summary): `https://mind.be/eoss2023-a-current-overview-of-the-drm-kms-driver-side-apis-paul-kocialkowski-bootlin/`[9]
- URL (slides/PDF): `https://bootlin.com/pub/conferences/2023/eoss/kocialkowski-current-overview-drm-kms-driver-side-apis/kocialkowski-current-overvi...` (truncated in search; full Bootlin PDF link)[10]
- Phase: 2 – Resources  
  - “Paul Kocialkowski’s overview of current DRM/KMS driver-side APIs for modern kernel patterns.”  
- Also referenced in:
  - Phase 3 – Resources (panel/bridge handling, DSI).  
  - “Best public resources” table.

***

## Phase 3 – Panel drivers and MIPI DSI

### Toradex – MIPI DSI driver development webinar

- URL (LinkedIn promo, with replay link): `https://www.linkedin.com/posts/toradex_on-demand-webinar-bringing-displays-to-life-activity-7366863450175692803-AuX6`[11]
  - The actual replay link is accessed from this page (“Replay it clicking here”) and is what you’d watch.  
- Phase: 3 – Resources  
- Step: “Toradex’s MIPI DSI driver-development webinar for practical debugging and integration tactics.”

### Bootlin / EOSS DRM KMS APIs (same as Paul Kocialkowski resource above)

- URLs: same `mind.be` + Bootlin PDF + YouTube talk set[8][9][10]
- Phase: 3 – Resources  
  - “Bootlin and EOSS material on DRM/KMS driver APIs, including panel and bridge handling.”

***

## Phase 4 – GPU and Apple-style graphics concepts

### Macinternals – Apple GPU and Metal driver

- URL: `https://www.macinternals.app/en/blog/apple-gpu-and-metal`[12]
- Phase: 4 – Resources  
- Step: “Macinternals’ Apple GPU and Metal driver article for a public explanation of unified-memory behavior in practice.”  
- Also referenced in:
  - Course intro (bridging to Apple GPU/Metal/unified memory).  
  - “Best public resources” table.  
  - “What this prepares you for” section to tie to Apple-silicon concepts.

***

## General / conceptual DRM/KMS overviews

### High-level DRM/KMS blog overview

- URL: `https://jyos-sw.medium.com/drm-and-kms-0bb2f50c035d`[13]
- Phase: 2 – Topics  
  - Used as an additional conceptual overview of DRM/KMS (not explicitly named in the Markdown but part of the background material for mode setting and pipeline understanding).  

***

## Summary mapping (by phase)

To make it quick to cross-reference:

- **Phase 1 – Fundamentals**
  - Apriorit Linux driver tutorial: `https://www.apriorit.com/dev-blog/195-simple-driver-for-linux-os`  
  - Linux GPU Driver Developer’s Guide (intro): `https://docs.kernel.org/5.19/gpu/index.html`, `https://dri.freedesktop.org/docs/drm/gpu.html`  
  - Video course examples:  
    - `https://www.youtube.com/watch?v=iSiyDHobXHA`  
    - `https://www.youtube.com/watch?v=WKH25Iz6Z3M`  

- **Phase 2 – DRM/KMS**
  - Xilinx DRM/KMS subsystem: `https://docs.amd.com/r/en-US/ug1442-vck190-base-trd/DRM/KMS-Kernel-Subsystem`  
  - Linux GPU Driver Developer’s Guide: `https://docs.kernel.org/5.19/gpu/index.html`, `https://dri.freedesktop.org/docs/drm/gpu.html`  
  - Maxime Ripard DRM talk: `https://www.youtube.com/watch?v=LbDOCJcDRoo`  
  - Paul Kocialkowski DRM/KMS APIs:  
    - `https://www.youtube.com/watch?v=nNY7NjUIJRA`  
    - `https://mind.be/eoss2023-a-current-overview-of-the-drm-kms-driver-side-apis-paul-kocialkowski-bootlin/`  
    - Bootlin PDF link from `bootlin.com` (as in search result)  
  - Supplementary DRM/KMS blog: `https://jyos-sw.medium.com/drm-and-kms-0bb2f50c035d`  

- **Phase 3 – Panel/DSI**
  - Toradex MIPI DSI webinar: `https://www.linkedin.com/posts/toradex_on-demand-webinar-bringing-displays-to-life-activity-7366863450175692803-AuX6`  
  - Same Paul Kocialkowski / Bootlin links as above for panel/bridge handling.  

- **Phase 4 – Apple GPU / unified memory**
  - Macinternals Apple GPU & Metal driver: `https://www.macinternals.app/en/blog/apple-gpu-and-metal`  
  - Linux GPU Driver Developer’s Guide again for memory/fence analogs.  

If you’d like, I can also add a small “References” subsection to your Markdown file (just URLs and brief labels) so you can quickly click through them within the repo.

Sources
[1] Linux Device Drivers: Linux Driver Development Tutorial - Apriorit https://www.apriorit.com/dev-blog/195-simple-driver-for-linux-os
[2] Linux Device Drivers Development Course for Beginners - YouTube https://www.youtube.com/watch?v=iSiyDHobXHA
[3] Learning Linux Device Drivers Development : Talking about Graphic Drivers | packtpub.com https://www.youtube.com/watch?v=WKH25Iz6Z3M
[4] DRM/KMS Kernel Subsystem - 2020.2 English - UG1442 https://docs.amd.com/r/en-US/ug1442-vck190-base-trd/DRM/KMS-Kernel-Subsystem
[5] Linux GPU Driver Developer's Guide https://docs.kernel.org/5.19/gpu/index.html
[6] Linux GPU Driver Developer's Guide - Freedesktop.org https://dri.freedesktop.org/docs/drm/gpu.html
[7] Kernel Recipes 2017 - An introduction to the Linux DRM subsystem - Maxime Ripard https://www.youtube.com/watch?v=LbDOCJcDRoo
[8] A Current Overview of the DRM KMS Driver-Side APIs - Paul Kocialkowski, Bootlin https://www.youtube.com/watch?v=nNY7NjUIJRA
[9] EOSS2023 - A Current Overview of the DRM KMS Driver-Side APIs - Paul Kocialkowski, Bootlin - mind https://mind.be/eoss2023-a-current-overview-of-the-drm-kms-driver-side-apis-paul-kocialkowski-bootlin/
[10] [PDF] A Current Overview of the DRM KMS Driver-Side APIs - Bootlin https://bootlin.com/pub/conferences/2023/eoss/kocialkowski-current-overview-drm-kms-driver-side-apis/kocialkowski-current-overview-drm-kms-driver-side-apis.pdf
[11] Watch MIPI DSI Driver Development for Linux webinar on demand https://www.linkedin.com/posts/toradex_on-demand-webinar-bringing-displays-to-life-activity-7366863450175692803-AuX6
[12] The Apple GPU and Metal driver: unified memory in practice https://www.macinternals.app/en/blog/apple-gpu-and-metal
[13] Kms https://jyos-sw.medium.com/drm-and-kms-0bb2f50c035d

