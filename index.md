---
layout: page
title: About
permalink: /index.html
---

I am studying Generative AI from technology to applications at ByteDance. 

Previously, I was leading a team of engineers and PMs at Momenta.ai to build data infra and simulation for autonomous driving. Whthin my 3 years tenure, we built the largest simulation platform in China in terms of scale from scratch.

Prior to Momenta.ai, I was working on strategy & investment in AI and Infrastructure. I have also founded/co-founded various startups and organizations, including GGU Consulting, MIT CEO, MIT Energy Hackathon. 

I obtained my PhD from MIT and my bachelors from Tsinghua University. 

During my spare time, I like trail running and skiing. I am currently training for UTMB. 


# Recent Writings
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) <br>
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}


