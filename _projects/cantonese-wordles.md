---
layout: page
title: Cantonese Wordles
description: A Cantonese Jyutping puzzle designed for YueVoice (Cantonese) club weekly activities.
img: assets/img/cantonese-wordles.png
importance: 10
category: Work
---

Cantonese Wordles is a recurring warm-up activity for YueVoice’s weekly Cantonese club meetings. Displayed on the activity-room screen, it gives everyone an easy way to play and collaborate.

I developed the game using HTML, JavaScript, and AI-assisted tools, making it easy to run on the activity-room computer and play directly on this webpage.



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
