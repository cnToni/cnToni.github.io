---
layout: page
title: Cantonese Wordles
description: A daily Cantonese Jyutping puzzle migrated from Next.js to static JavaScript for GitHub Pages.
img: assets/img/10.jpg
importance: 10
category: Work
---

This is a Cantonese wordle game updated everyday.
Enjoy your Cantonese time!

<style>
  .cantonese-wordles-embed {
    margin-top: 1.5rem;
  }

  .cantonese-wordles-embed iframe {
    width: 100%;
    min-height: 980px;
    border: 0;
    border-radius: 24px;
    background: #fff9f0;
    box-shadow: 0 16px 36px rgba(46, 36, 18, 0.14);
  }

  @media (max-width: 640px) {
    .cantonese-wordles-embed iframe {
      min-height: 1080px;
      border-radius: 18px;
    }
  }
</style>

<div class="cantonese-wordles-embed">
  <iframe
    src="{{ '/assets/games/cantonese-wordles/index.html' | relative_url }}"
    title="Cantonese Wordles"
    loading="lazy"
  ></iframe>
</div>
