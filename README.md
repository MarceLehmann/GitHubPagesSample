# Jekyll Minimal Mistakes Showcase

Eine **vollständige Demonstration** aller visuellen Elemente des Jekyll Minimal Mistakes Themes. Diese Seite zeigt jeden verfügbaren Komponenten, Layout und Helper auf einer einzigen übersichtlichen Seite.

## 🎯 Was ist das?

Diese Website ist ein **kompletter Showcase** des Jekyll Minimal Mistakes Themes mit:

- ✅ **Alle visuellen Komponenten** (Buttons, Notice Boxes, etc.)
- ✅ **Alle Layout-Optionen** (Splash, Single, Archive, etc.)  
- ✅ **Alle Helper-Funktionen** (Feature Rows, Galleries, etc.)
- ✅ **Deutsche Lokalisierung** 
- ✅ **GitHub Pages Ready**
- ✅ **Vollständig responsiv**

## 🚀 Quick Start

### 1. Repository Setup

```bash
# Repository klonen oder forken
git clone https://github.com/username/jekyll-showcase.git
cd jekyll-showcase

# Dependencies installieren
bundle install

# Local development server starten
bundle exec jekyll serve
```

### 2. GitHub Pages Deployment

1. **Fork** dieses Repository
2. **Rename** zu `username.github.io` (oder belasse den Namen für Project Pages)
3. **Enable** GitHub Pages in den Repository Settings
4. **Customize** die `_config.yml` mit deinen Daten

### 3. Anpassung

**Wichtige Dateien zum Anpassen:**

- `_config.yml` - Basis-Konfiguration und Site-Daten
- `_data/navigation.yml` - Menü-Navigation
- `assets/images/` - Alle Bilder ersetzen
- `_pages/` - Seiten-Inhalte anpassen

## 📁 Projekt-Struktur

```
├── _config.yml              # Haupt-Konfiguration
├── _data/
│   └── navigation.yml        # Navigation-Menüs
├── _pages/
│   ├── showcase.md          # Alle Komponenten (HAUPTSEITE)
│   ├── gallery.md           # Gallery-Beispiele
│   ├── about.md             # About-Seite
│   ├── posts.md             # Posts-Archiv
│   ├── categories.md        # Kategorien-Archiv
│   └── tags.md              # Tags-Archiv
├── _posts/
│   ├── 2025-06-17-welcome-to-showcase.md
│   ├── 2025-06-16-button-variations.md
│   └── 2025-06-15-layout-options.md
├── assets/
│   └── images/              # Alle Bilder (siehe README dort)
├── index.md                 # Startseite (Splash Layout)
├── Gemfile                  # Ruby Dependencies  
└── README.md               # Diese Datei
```

## 🎨 Verfügbare Komponenten

### Visuelle Elemente
- **Buttons:** Alle Farben und Größen
- **Notice Boxes:** Info, Warning, Success, Danger
- **Typography:** Überschriften, Text-Styling, Alignment  
- **Tables:** Standard und formatierte Tabellen
- **Lists:** Ordered, Unordered, Task Lists
- **Code Blocks:** Mit Syntax Highlighting

### Layout-Optionen
- **Splash:** Landing Pages mit Hero-Bereich
- **Single:** Standard Content-Seiten
- **Archive:** Posts, Categories, Tags
- **Collection:** Custom Collections

### Content-Helpers
- **Feature Rows:** Prominente Content-Bereiche
- **Galleries:** Bild-Sammlungen mit verschiedenen Layouts
- **Figures:** Einzelbilder mit Captions und Popup
- **Video Embeds:** YouTube, Vimeo Integration
- **Archive Singles:** Post-Teasers

### Navigation & UI
- **Masthead:** Haupt-Navigation mit Responsive Toggle
- **Breadcrumbs:** Automatische Seitenpfad-Navigation
- **Table of Contents:** Automatisch generiert, sticky
- **Sidebar:** Author Profile, Custom Navigation
- **Footer:** Social Links, Copyright

## 🖼 Bilder Setup

**Wichtig:** Ersetze alle Platzhalter-Bilder in `assets/images/`

Siehe [assets/images/README.md](assets/images/README.md) für:
- Vollständige Liste aller benötigten Bilder
- Empfohlene Bildgrößen  
- Optimierung-Tipps

## ⚙️ Konfiguration

### _config.yml anpassen

```yaml
# Basis-Informationen
title: "Dein Site-Titel"
description: "Deine Site-Beschreibung"
url: "https://username.github.io"
repository: "username/repository"

# Author-Informationen
author:
  name: "Dein Name"
  avatar: "/assets/images/dein-avatar.jpg"
  bio: "Deine Bio"
  email: "deine@email.com"
  # Social Links...
```

### Theme Skin ändern

```yaml
minimal_mistakes_skin: "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"
```

## 📱 Responsive Design

Alle Komponenten sind **vollständig responsive**:

- **Desktop:** Full-featured Layout mit Sidebar
- **Tablet:** Angepasste Navigation und Sidebar
- **Mobile:** Single-column Layout, Touch-optimiert

## 🔧 Customization

### Custom CSS hinzufügen

Erstelle `/assets/css/main.scss`:

```scss
---
---

@import "minimal-mistakes/skins/{{ site.minimal_mistakes_skin | default: 'default' }}";
@import "minimal-mistakes";

// Deine Custom Styles hier
.custom-class {
  // ...
}
```

### Custom Layouts

Neue Layouts in `_layouts/` erstellen:

```html
---
layout: default
---

<div class="custom-layout">
  {{ content }}
</div>
```

## 📖 Verwendung

### 1. Als Referenz
Nutze die [Showcase-Seite](/showcase/) als **vollständige Referenz** für alle verfügbaren Elemente.

### 2. Als Template  
**Fork** das Repository und passe es für deine eigene Website an.

### 3. Als Lernressource
Studiere den **Source Code** um zu verstehen, wie jedes Element implementiert wird.

## 🤝 Mitwirken

**Verbesserungen sind willkommen!**

1. **Fork** das Repository
2. **Erstelle** einen Feature Branch (`git checkout -b feature/amazing-feature`)
3. **Commit** deine Changes (`git commit -m 'Add amazing feature'`)
4. **Push** zum Branch (`git push origin feature/amazing-feature`)
5. **Öffne** einen Pull Request

## 📝 Lizenz

Dieses Projekt nutzt das Jekyll Minimal Mistakes Theme unter der MIT Lizenz.

## 🔗 Links

- **[Live Demo](https://username.github.io)** - Siehe die Website in Aktion
- **[Minimal Mistakes Docs](https://mmistakes.github.io/minimal-mistakes/)** - Offizielle Dokumentation
- **[Jekyll Docs](https://jekyllrb.com/docs/)** - Jekyll Dokumentation
- **[GitHub Pages](https://pages.github.com/)** - Hosting-Informationen

## 🆘 Support

**Probleme oder Fragen?**

1. Prüfe die [Issues](https://github.com/username/repository/issues)
2. Erstelle ein neues Issue mit detaillierter Beschreibung
3. Oder schreibe eine E-Mail an: support@example.com

---

**⭐ Gefällt dir dieses Projekt? Gib ihm einen Stern!**

**Made with ❤️ and Jekyll Minimal Mistakes**
