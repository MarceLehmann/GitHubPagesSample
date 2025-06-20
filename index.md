---
title: "Jekyll Minimal Mistakes Showcase"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash-bg.svg
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
  - image_path: /assets/images/feature-components.svg
    alt: "Visual Components"
    title: "Visuelle Komponenten"
    excerpt: "Buttons, Notice Boxes, Typography, Galleries und vieles mehr."
    url: "/showcase/#components"
    btn_label: "Entdecken"
    btn_class: "btn--primary"
  - image_path: /assets/images/advanced-teaser.svg
    alt: "Advanced Components"
    title: "Advanced Components"
    excerpt: "Modern UI elements like progress bars, cards, enhanced forms, and interactive components."
    url: "/advanced-components/"
    btn_label: "Explore"
    btn_class: "btn--primary"
  - image_path: /assets/images/business-teaser.svg
    alt: "Business Components"
    title: "Business Features"
    excerpt: "Corporate-ready components including team sections, testimonials, and service showcases."
    url: "/business-components/"
    btn_label: "View Business"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/images/careers-teaser.svg
    alt: "Careers"
    title: "Careers & HR"
    excerpt: 'Professional **careers section** with job listings, application forms, benefits showcase, and company culture presentation.'
    url: "/careers/"
    btn_label: "View Careers"
    btn_class: "btn--primary"
  - image_path: /assets/images/partners-teaser.svg
    alt: "Partnerships"
    title: "Partners & Clients"
    excerpt: 'Comprehensive **partnership pages** featuring client testimonials, success stories, and partnership inquiry forms.'
    url: "/partners/"
    btn_label: "See Partners"
    btn_class: "btn--primary"
  - image_path: /assets/images/contact-teaser.svg
    alt: "Contact"
    title: "Contact & Support"
    excerpt: 'Multi-channel **contact solutions** with forms, global offices, support channels, and response time commitments.'
    url: "/contact/"
    btn_label: "Contact Us"
    btn_class: "btn--primary"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/feature-customization.svg
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

## 🎨 Design System Showcases

Entdecke verschiedene moderne Design-Systeme und UI-Frameworks, die mit Jekyll Minimal Mistakes umgesetzt wurden:

### Populäre UI-Frameworks
- **[Microsoft Fluent Design](https://marcelehmann.github.io/GitHubPagesSample/fluent-design/)** - Modernes Design System von Microsoft mit Fluent UI Komponenten
- **[Tailwind CSS Demo](https://marcelehmann.github.io/GitHubPagesSample/tailwind-demo/)** - Utility-first CSS Framework für schnelle und flexible Designs
- **[Material Design](https://marcelehmann.github.io/GitHubPagesSample/material-design/)** - Googles Design Language mit charakteristischen Elementen
- **[Bootstrap Demo](https://marcelehmann.github.io/GitHubPagesSample/bootstrap-demo/)** - Das beliebteste CSS Framework für responsive Websites

### Web-Standards & Specialized Frameworks
- **[CSS Grid & Flexbox](https://marcelehmann.github.io/GitHubPagesSample/css-grid-flexbox/)** - Moderne Layout-Techniken für responsive Designs
- **[Ant Design](https://marcelehmann.github.io/GitHubPagesSample/ant-design/)** - Enterprise-Class UI Design Language und React Components
- **[IBM Carbon Design](https://marcelehmann.github.io/GitHubPagesSample/carbon-design/)** - Open-Source Design System für digitale Produkte und Erlebnisse

{: .notice--primary}
**Hinweis:** Alle Showcases demonstrieren, wie verschiedene Design-Systeme und UI-Frameworks mit Jekyll Minimal Mistakes kombiniert werden können.

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
