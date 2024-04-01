---
title: '15 segundos diários'
menu: true
lang: pt
layout: post-other
type: gifs sonoros
data: 2014 ~ hoje
permalink: segundos
cover: /assets/cover/segundos.png
ref: 15segundos
---


<div class="video-grid">
    {% for video in site.data.segundosdiarios %} 
      <div class="video-wrapper-1x1">     
        <iframe src="https://player.vimeo.com/video/{{ video.videonumber }}?loop=1&title=0&byline=0&portrait=0" width="640" height="640" frameborder="0" ></iframe>
      </div>
    {% endfor %}
</div>