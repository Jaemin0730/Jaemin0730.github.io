---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: /assets/pdf/cv.pdf # you can also use external links here
cv_format: jsonresume # options: rendercv, jsonresume
description: Curriculum vitae of Jaemin Kim.
toc:
  sidebar: left
---

<style>
  /* Wrap the location text inside the narrow date column instead of overflowing */
  .location,
  .date-column .location {
    overflow-wrap: anywhere;
    word-break: break-word;
    white-space: normal;
    line-height: 1.3;
  }
  /* The CV date/location table can force its own min width and spill out; let it shrink */
  .table-cv,
  .date-column .table-cv,
  .date-column {
    width: 100%;
    max-width: 100%;
    table-layout: fixed;
  }
  /* Let grid columns shrink so long words wrap rather than push the layout wider */
  .list-group-item .row > [class*="col-"] {
    min-width: 0;
  }
  /* Long titles / descriptions in the wider column should wrap cleanly too */
  .list-group-item h6,
  .list-group-item p,
  .list-group-item li {
    overflow-wrap: anywhere;
  }
</style>

