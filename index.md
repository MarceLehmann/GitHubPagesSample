---
title: "Jekyll Minimal Mistakes Showcase"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-bg.jpg
  actions:
    - label: "Showcase ansehen"
      url: "/showcase/"
      class: "btn--primary btn--large"
    - label: "GitHub Repository"
      url: "https://github.com/username/username.github.io"
      class: "btn--inverse btn--large"
excerpt: "Entdecke alle verfügbaren visuellen Komponenten und Elemente des Jekyll Minimal Mistakes Themes auf einer einzigen übersichtlichen Seite."

intro: 
  - excerpt: 'Diese Website demonstriert **alle verfügbaren visuellen Elemente** des Jekyll Minimal Mistakes Themes. Von einfachen Buttons bis hin zu komplexen Feature Rows - hier findest du alles an einem Ort. {: .text-center}'

feature_row:
  - image_path: /assets/images/feature-components.jpg
    alt: "Visual Components"
    title: "Visuelle Komponenten"
    excerpt: "Buttons, Notice Boxes, Typography, Galleries und vieles mehr."
    url: "/showcase/#components"
    btn_label: "Entdecken"
    btn_class: "btn--primary"
  - image_path: /assets/images/feature-layouts.jpg
    alt: "Layouts"
    title: "Layout-Optionen"
    excerpt: "Splash, Single, Archive, Collections und weitere Layout-Varianten."
    url: "/showcase/#layouts"
    btn_label: "Ansehen"
    btn_class: "btn--primary"
  - image_path: /assets/images/feature-helpers.jpg
    alt: "Helpers & Includes"
    title: "Helpers & Includes"
    excerpt: "Feature Rows, Galleries, Figure, Video Embeds und weitere Helpers."
    url: "/showcase/#helpers"
    btn_label: "Erkunden"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/feature-navigation.jpg
    alt: "Navigation"
    title: "Navigation & Menüs"
    excerpt: 'Das Theme bietet flexible **Navigation-Optionen** inklusive Masthead, Breadcrumbs, Table of Contents und Sidebar-Menüs. Alle Elemente sind responsiv und vollständig anpassbar.'
    url: "/showcase/#navigation"
    btn_label: "Mehr erfahren"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/feature-customization.jpg
    alt: "Customization"
    title: "Vollständig anpassbar"
    excerpt: 'Mit über **10 verschiedenen Skins**, unzähligen Konfigurationsoptionen und Custom CSS kannst du das Theme genau nach deinen Vorstellungen gestalten.'
    url: "/showcase/#customization"
    btn_label: "Anpassen"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

## Was findest du hier?

Diese Demonstrationsseite zeigt dir **alle verfügbaren visuellen Elemente** des Jekyll Minimal Mistakes Themes. Perfekt für:

- 🎨 **Designer** die alle verfügbaren Komponenten sehen möchten
- 👩‍💻 **Entwickler** die Implementation-Details benötigen  
- 📝 **Content-Creators** die ihre Optionen erkunden wollen
- 🔧 **Theme-Customizer** die Anpassungsmöglichkeiten suchen

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

## Quick Start

1. **Fork** dieses Repository
2. **Anpassen** der `_config.yml` mit deinen Daten
3. **Deployen** auf GitHub Pages
4. **Erkunden** aller verfügbaren Elemente

{: .notice--info}
**Tipp:** Schau dir den [Showcase](/showcase/) an, um alle Komponenten in Aktion zu sehen!

---

## Neueste Updates

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}

**[Alle Posts ansehen](/posts/){: .btn .btn--primary}**
