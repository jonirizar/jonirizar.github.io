---
layout: page
title: "cv"
permalink: /cv/
nav: true
nav_order: 5
cv_pdf: assets/pdf/cv_jonirizaramuchastegui.pdf
description: ""
toc: sidebar
---

<style>
  .cv-embed {
    display: block;
    width: 100%;
    max-width: 900px;
    height: 90vh;
    margin: 1rem auto 1.25rem;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 4px;
    background: #fff;
  }
  .cv-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    justify-content: center;
    margin-bottom: 2rem;
  }
  .cv-actions .cv-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.55rem 1.1rem;
    border-radius: 6px;
    font-weight: 500;
    text-decoration: none;
    border: 1px solid var(--global-theme-color);
    color: var(--global-theme-color);
    background: transparent;
    transition: background 0.15s ease, color 0.15s ease;
  }
  .cv-actions .cv-btn.cv-btn-primary {
    background: var(--global-theme-color);
    color: #fff;
  }
  .cv-actions .cv-btn:hover {
    background: var(--global-theme-color);
    color: #fff;
    text-decoration: none;
  }
</style>

<embed class="cv-embed" src="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" type="application/pdf" />

<div class="cv-actions">
  <a class="cv-btn cv-btn-primary" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" target="_blank" rel="noopener">Open PDF</a>
  <a class="cv-btn" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" download>Download PDF</a>
</div>
