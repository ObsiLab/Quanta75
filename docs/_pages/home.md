---
layout: splash
permalink: /index.html
#hidden: true
header:
  overlay_color: "#30e3ca"
  overlay_image: /assets/images/homepage-image.png
  actions:
    - label: "<i class='<i class="fa-solid fa-keyboard"></i>'></i> Get started"
      url: "/docs/quick-start/"
excerpt:
  A DIY 75% ISO mechanical keyboard, with a rotary encoder and vertical USB A port.<br>
  <small><a href="https://github.com/ObsiLab/Quanta">Github repository</a></small>
feature_row:
  - image_path: /assets/images/keyboard-photo.jpg
    alt: "keyboard photo"
    title: "The Quanta"
    excerpt: "blablablabla bla blabla blabla."
    url: "/keyboard/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/firmware-code.png
    alt: "firmware code"
    title: "RMK Firmware"
    excerpt: "Fully open-source customizable firmware written in Rust."
    url: "/docs/firmware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/pcb.png
    alt: "PCB"
    title: "Open Hardware"
    excerpt: "Fully open-source hardware, get access to the KiCad Project PCB files."
    url: "/hardware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
---

{% include feature_row %}