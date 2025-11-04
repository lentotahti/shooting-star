---
title: "Palvelut"
layout: splash
permalink: /palvelut/
author_profile: false
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/promo/running-trail.jpg
  actions:
    - label: "Download"
      url: "/"
  caption: "Photo credit: [**Mira Kylliäinen**](https://www.instagram.com/miratms/)"
excerpt: "Valmennusta ja sen sellaista. Erittäin kova tietotaito."
intro: 
  - excerpt: 'Tässä jotain introa: Centered with `type="center"`'
feature_row:
  - image_path: assets/images/logos/lentotahti-logo-punainen-koko_1.svg
    alt: "placeholder image 1"
    title: "Valmennus mini light 1"
    excerpt: "Treeniohjelmat **Markdown** formatting."
    url: "/hinnasto/ohjelmointi/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/logos/lentotahti-logo-vihrea-koko.svg
    alt: "placeholder image 2"
    title: Valmennus mini 2
    excerpt: "Valmennusta, kevyt seuranta **Markdown** formatting."
    url: "/hinnasto/valmennus_mini/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/logos/lentotahti-logo-valkoinen-koko.svg
    image_caption: "PRO!"
    title: "Valmennus pro 3"
    excerpt: "Seuranta ja live ohjelmat **Markdown** formatting."
    url: "/hinnasto/valmennus_plus/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/logos/lentotahti-logo-vihrea.svg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
feature_row3:
  - image_path: /assets/images/logos/lentotahti-logo-punainen.svg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
feature_row4:
  - image_path: /assets/images/logos/lentotahti-logo-vihrea-mark.svg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}