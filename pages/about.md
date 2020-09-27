---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I've been studying Computer Science at the University of British Columbia since 2016. I am currently in the co-op program, and I will be graduating with a Bachelor of Science in May 2021.

I started programming in high school after taking an online course, and I have never stopped since then. Video games also spark my interest in programming. In my free time, I like learning about game development :video_game:, drawing pixel art :art:, listening to EDM :headphones:.

Below are my resume and some of my working experience. If you have any questions or you'd like to get in touch, feel free to contact me. Cheers :smiley:

- Email: [cheeyew.lim@outlook.com](mailto:cheeyew.lim@outlook.com)
- Github: [github.com/knox153](github.com/knox153)

{% capture resume_link %}{{ site.url }}/assets/file/resume.pdf{% endcapture %}

<p class="text-center">
{% include elements/button.html link=resume_link text="Resume" size="lg" %}
</p>

<div class="row">
{% include about/timeline.html %}
</div>