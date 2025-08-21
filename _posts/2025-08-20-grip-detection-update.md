---
layout: post
title: "Grip Detection Update: Curl Logic in Action"
date: 2025-08-20
---

Today I refactored the grip detection logic to focus on **finger curl** instead of thumb-index proximity. This change dramatically improves detection for rotated wrists and non-standard grips.

<div style="text-align: center;">
  <img src="/assets/images/intro_photo.png" alt="Intro Photo" width="400">
  <p><em>This is Brush Hero in action</em></p>
</div>


### 🔍 What’s Working
- Curl-based detection is more robust across hand postures
- Overlay rendering is centralized and extensible

### 🧠 Next Steps
- Add transition logging for grip state changes
- Refactor naming for semantic clarity
