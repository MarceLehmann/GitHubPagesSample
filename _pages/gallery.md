---
title: "Gallery Showcase"
layout: single
permalink: /gallery/
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/gallery-header.jpg

# Gallery definitions
gallery_main:
  - url: /assets/images/gallery-1.jpg
    image_path: /assets/images/gallery-1-th.jpg
    alt: "Beispiel 1"
    title: "Natur Fotografie"
  - url: /assets/images/gallery-2.jpg
    image_path: /assets/images/gallery-2-th.jpg
    alt: "Beispiel 2"
    title: "Architektur"
  - url: /assets/images/gallery-3.jpg
    image_path: /assets/images/gallery-3-th.jpg
    alt: "Beispiel 3"
    title: "Portrait"
  - url: /assets/images/gallery-4.jpg
    image_path: /assets/images/gallery-4-th.jpg
    alt: "Beispiel 4"
    title: "Landschaft"
  - url: /assets/images/gallery-5.jpg
    image_path: /assets/images/gallery-5-th.jpg
    alt: "Beispiel 5"
    title: "Street Photography"
  - url: /assets/images/gallery-6.jpg
    image_path: /assets/images/gallery-6-th.jpg
    alt: "Beispiel 6"
    title: "Abstrakt"

gallery_grid:
  - url: /assets/images/grid-1.jpg
    image_path: /assets/images/grid-1-th.jpg
    alt: "Grid 1"
    title: "Grid Layout Beispiel 1"
  - url: /assets/images/grid-2.jpg
    image_path: /assets/images/grid-2-th.jpg
    alt: "Grid 2"
    title: "Grid Layout Beispiel 2"
  - url: /assets/images/grid-3.jpg
    image_path: /assets/images/grid-3-th.jpg
    alt: "Grid 3"
    title: "Grid Layout Beispiel 3"
  - url: /assets/images/grid-4.jpg
    image_path: /assets/images/grid-4-th.jpg
    alt: "Grid 4"
    title: "Grid Layout Beispiel 4"
---

## Gallery Layouts

Das Jekyll Minimal Mistakes Theme bietet verschiedene Gallery-Layouts für die optimale Präsentation deiner Bilder.

### Standard Gallery

{% include gallery id="gallery_main" caption="Standard Gallery Layout mit allen Bildern in einer Reihe." %}

### Half Layout Gallery

{% include gallery id="gallery_grid" layout="half" caption="Half Layout - Bilder werden in zwei Spalten angezeigt." %}

### Third Layout Gallery

{% include gallery id="gallery_grid" layout="third" caption="Third Layout - Bilder werden in drei Spalten angezeigt." %}

## Einzelne Figure mit Popup

{% include figure image_path="/assets/images/single-large.jpg" alt="Einzelbild" caption="Einzelnes Bild mit Popup-Funktionalität." popup=true %}

## Video in Gallery

Du kannst auch Videos in Galleries einbinden:

{% include video id="dQw4w9WgXcQ" provider="youtube" %}

**Hinweis:** Alle Bilder sind Platzhalter. Ersetze sie durch deine eigenen Bilder in dem `assets/images/` Verzeichnis.
{: .notice--info}
