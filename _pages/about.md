---
layout: single
title: "About"
permalink: /about/
---

I used to practice piano and violin, but now I just play music for fun~
<iframe width="200" height="315" src="https://www.youtube.com/embed/Sjv2bAbLLL8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
I also played in a band before. I am the vocalist in the first song and keyboardist in the third.
<div class="video-wrapper" onclick="playVideo(this)">
    <img src="{{ site.baseurl }}/assets/images/band_video.jpg" alt="Custom Thumbnail">
    <iframe width="200" height="113" src="https://www.youtube.com/embed/Fqqz8DCoEvc?start=58&end=320&autoplay=1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

![Fang Duo Tsai]({{ site.baseurl }}/assets/images/Me_and_jimmy.jpg)
My dog Jimmy and I.
![Fang Duo Tsai]({{ site.baseurl }}/assets/images/surfing.jpg)
Still a rookie.

<script>
    function playVideo(wrapper) {
        const iframe = wrapper.querySelector('iframe');
        const img = wrapper.querySelector('img');
        iframe.style.display = 'block';
        img.style.display = 'none';
    }
</script>

<style>
    .video-wrapper {
        position: relative;
        width: 200px; /* Match the width of the iframe */
        height: 315px; /* Match the height of the iframe */
        cursor: pointer;
    }
    .video-wrapper img {
        width: 100%;
        height: 100%;
    }
    .video-wrapper iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        display: none;
    }
</style>
