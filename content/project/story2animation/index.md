---
title: Animation Synthesis from Story Scripts
summary:
tags:
date: "2021-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

<figure>
    <img src="/project/story2animation/system_overview.jpg" alt="system overview" />
    <figcaption>Figure 1. Synthesis Pipeline</figcaption>
</figure>

As shown in Figure 1, we develop an automated production tool that can efficiently generate animations from natural language-described story scripts. The synthesis pipeline contains two stages:

* Utilizing our animation model, which is a complex system that integrates NLP analysis and a Unity-based graphics engine, to generate an animation clip from a story script.
* Making further adjustments to the animation using an interactive editing tool, such as CapCut for TikTok.



Below are several animation demos created by our system from story scripts written in Chinese:

<figure>
  <video controls>
    <source src="/project/story2animation/naming.mp4" type="video/mp4">
  </video>
  <figcaption>Video 1. Animation generated from a story script about Naming.</figcaption>
</figure>

<figure>
  <video controls>
    <source src="/project/story2animation/rent_collection.mp4" type="video/mp4">
  </video>
  <figcaption>Video 2. Animation generated from a story script about Rent Collection.</figcaption>
</figure>

<figure>
  <video controls>
    <source src="/project/story2animation/inspection.mp4" type="video/mp4">
  </video>
  <figcaption>Video 3. Animation generated from a story script about the Chairman's Inspection.</figcaption>
</figure>

<figure>
  <video controls>
    <source src="/project/story2animation/Peppa_pig.mp4" type="video/mp4">
  </video>
  <figcaption>Video 4. Animation generated from a story script about Peppa Pig.</figcaption>
</figure>

<figure>
  <video controls>
    <source src="/project/story2animation/castle_dinner.mp4" type="video/mp4">
  </video>
  <figcaption>Video 5. Animation generated from a description of a scene about a Castle Dinner.</figcaption>
</figure>

<figure>
  <video controls>
    <source src="/project/story2animation/ultraman.mp4" type="video/mp4">
  </video>
  <figcaption>Video 6. Animation generated from a story script about Ultraman.</figcaption>
</figure>



Besides, we generated more animation videos using an earlier version of our product and shared them on Douyin (ID: [heidongdonghua](https://www.douyin.com/user/MS4wLjABAAAATN0Pe89ypRCMYmnQ-8lClIsT0nBKxFOawYvVwlNS0H8)) -- the Chinese TikTok, on an irregular basis.