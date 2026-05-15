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
  .cv-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.25rem;
    padding: 1.5rem;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-radius: 8px;
    background: var(--global-card-bg-color, transparent);
    margin: 1rem 0 2rem;
  }
  .cv-card a.cv-thumb {
    display: block;
    line-height: 0;
    max-width: 100%;
    transition: transform 0.15s ease, box-shadow 0.15s ease;
  }
  .cv-card a.cv-thumb:hover {
    transform: translateY(-2px);
  }
  .cv-card img.cv-thumb-img {
    max-width: 100%;
    width: 420px;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.18);
    background: #fff;
  }
  .cv-card .cv-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    justify-content: center;
  }
  .cv-card .cv-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.55rem 1.1rem;
    border-radius: 6px;
    font-weight: 500;
    text-decoration: none;
    border: 1px solid var(--global-theme-color, #b509ac);
    color: var(--global-theme-color, #b509ac);
    background: transparent;
    transition: background 0.15s ease, color 0.15s ease;
  }
  .cv-card .cv-btn.cv-btn-primary {
    background: var(--global-theme-color, #b509ac);
    color: #fff;
  }
  .cv-card .cv-btn:hover {
    background: var(--global-theme-color, #b509ac);
    color: #fff;
    text-decoration: none;
  }
</style>

<div class="cv-card">
  <a class="cv-thumb" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" target="_blank" rel="noopener" aria-label="Open CV PDF in a new tab">
    <img class="cv-thumb-img" src="{{ '/assets/img/cv_thumbnail.png' | relative_url }}" alt="Preview of the first page of the CV" loading="lazy" />
  </a>
  <div class="cv-actions">
    <a class="cv-btn cv-btn-primary" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" target="_blank" rel="noopener">Open CV</a>
    <a class="cv-btn" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" download>Download PDF</a>
  </div>
</div>
