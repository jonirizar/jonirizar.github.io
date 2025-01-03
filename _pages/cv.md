---
layout: page
title: "cv"
permalink: /cv/
nav: true
nav_order: 5
cv_pdf: assets/pdf/cv_jonirizaramuchastegui.pdf
description: "You can find my CV here"
toc: sidebar
---

<style>
  .responsive-iframe {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%; /* 16:9 aspect ratio */
    height: 0;
  }
  .responsive-iframe iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }
  @media (max-width: 768px) {
    .responsive-iframe {
      padding-top: 75%; /* 4:3 aspect ratio for mobile devices */
    }
  }
</style>

<div class="responsive-iframe">
  <iframe src="{{ site.baseurl }}/assets/pdf/cv_jonirizaramuchastegui.pdf">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="{{ site.baseurl }}/assets/pdf/cv_jonirizaramuchastegui.pdf">Download PDF</a>
  </iframe>
</div>

<p>If you are having trouble viewing the PDF, you can download it directly <a href="{{ site.baseurl }}/assets/pdf/cv_jonirizaramuchastegui.pdf">here</a>.</p>
