---
layout: page
title: Cantonese Wordles
description: A daily Cantonese Jyutping puzzle designed for school media.
img: assets/img/10.jpg
importance: 10
category: Work
---

Let's play a round of super brain-training Wordle! Following the classic Wordle rules, draw lines to connect adjacent letters (up, down, diagonal) with your finger to form a Jyutping syllable! 
After a successful connection, you will see some trivia about this syllable! Each Wordle puzzle can form many different Jyutping syllables! Try to find all the hidden Jyutping syllables!

来玩一局超级锻炼大脑的Wordle吧！遵循经典Wordle玩法，用手指把相邻（上、下、斜）的字母划线连接，来组成一个粤语拼音！
成功连接后，你会看到关于这个拼音的一些小知识！每一个Wordle都可以组成很多个粤语拼音哦！试着把所有隐藏的粤语拼音都找出来吧！

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
