---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /images/header/header.jpg
  cta_label: "Download"
  cta_label: "Διαβάστε ένα δωρεάν δείγμα"
  cta_url: "https://leanpub.com/pibook"
  caption: "Δικαιώματα εικόνας: [**SRI International**](https://www.sri.com)"
excerpt: 'Σχεδιασμός και κατασκευή συνεργατικών συστήματων για ένα οικοσύστημα χρηστών, συσκευών, και υπηρεσιών.'
---

<div class="feature__wrapper">

  {% assign random = site.time | date: "%s%N" | modulo: site.biography.size %}

  {% include feature_col.html id="biography" type="left" index=random %}

  {% assign random = site.time | date: "%s%N" | modulo: site.gallery.size %}

  {% include feature_col.html id="gallery" type="center" index=random %}

  <div><a class="twitter-timeline" href="https://twitter.com/38Alexandros?ref_src=twsrc%5Etfw" data-width="300" data-height="300" >Tweets by 38Alexandros</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8" ></script></div>

<div>
