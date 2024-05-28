---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#30e3ca"
  overlay_image: /assets/images/homepage_image.png
  actions:
    - label: "<i class='fas fa-keyboard'></i> Get Started"
      url: "/docs/quick-start/"
excerpt: >
  A 75% hotswap ISO mechanical keyboard, with rotary encoder and integrated USB hub with vertical USB A port.<br /> {::nomarkdown}<a class="github-button" href="https://github.com/ObsiLab/Quanta75" data-size="large" aria-label="Quanta on GitHub"> Github repository</a>{:/nomarkdown}
feature_row:
  - image_path: /assets/images/keyboard_photo.jpg
    alt: "keyboard photo"
    title: "The Quanta75"
    excerpt: "The Quanta75 is a 75%, hotswap, ISO layout, mechanical keyboard."
    url: "/keyboard/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/firmware_code.png
    alt: "firmware code"
    title: "RMK Firmware"
    excerpt: "Fully open-source customizable firmware written in Rust (MIT License)."
    url: "/docs/firmware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/quanta_pcb.png
    alt: "PCB"
    title: "Open Hardware"
    excerpt: "Fully open-source hardware (CERN-OHL-P v2). Access the KiCad Project PCB files."
    url: "/docs/pcb/" # "/hardware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
intro:
  - excerpt: 'Explore everything about the Quanta'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
