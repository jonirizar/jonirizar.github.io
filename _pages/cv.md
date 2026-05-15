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
  .cv-pages {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.25rem;
    margin: 1rem 0 1.5rem;
  }
  .cv-pages img {
    display: block;
    width: 100%;
    max-width: 850px;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.18);
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
    border: 1px solid var(--global-theme-color, #b509ac);
    color: var(--global-theme-color, #b509ac);
    background: transparent;
    transition: background 0.15s ease, color 0.15s ease;
  }
  .cv-actions .cv-btn.cv-btn-primary {
    background: var(--global-theme-color, #b509ac);
    color: #fff;
  }
  .cv-actions .cv-btn:hover {
    background: var(--global-theme-color, #b509ac);
    color: #fff;
    text-decoration: none;
  }
</style>

<div class="cv-pages">
  <img src="{{ '/assets/img/cv_page_1.png' | relative_url }}" alt="CV page 1" loading="eager" />
  <img src="{{ '/assets/img/cv_page_2.png' | relative_url }}" alt="CV page 2" loading="lazy" />
</div>

<div class="cv-actions">
  <a class="cv-btn cv-btn-primary" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" target="_blank" rel="noopener">Open PDF</a>
  <a class="cv-btn" href="{{ '/assets/pdf/cv_jonirizaramuchastegui.pdf' | relative_url }}" download>Download PDF</a>
</div>
