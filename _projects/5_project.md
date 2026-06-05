---
layout: page
title: Birdwatching and broad language learning
description: A combination of fun and bioacoustic research.
img: assets/img/young-birdwatcher.jpg
importance: 3
category: fun
---

Started bird watching from age of 10 as a junior volunteer of Guangzhou Nature Association, now actively involved in avian conservation and bioacoustic research.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/junior-bird-watchers-20180520.jpg" title="Junior volunteer in 2018" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dedicated-bird-conservationist.png" title="Urban nests survey of swallows and swifts" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dedicated-bird-conservationist-2.png" title="Raising awareness for swallow and swift conservation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Started bird watching from age of 10 as a junior volunteer of Guangzhou Nature Association, now actively involved in avian conservation and bioacoustics research.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/observe-n-tackle-climate-change.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    As a junior volunteer, joined the observation of floral phenology in Guangzhou amidst climate change.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
