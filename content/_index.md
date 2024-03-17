---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: SaltOpen 2024
      text: in Mägenwil by Art of GETU Stetten & BKTV
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: homepage-image.jpg
          filters:
            brightness: 0.5
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: false
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  - block: stats
    content:
      items:
        - statistic: "270"
          description: |
            Turner*innen
        - statistic: "2"
          description: |
            Tage
        - statistic: "3780"
          description: |
            Sprünge
    design:
      # Reduce spacing
      spacing:
        padding: ["0.1rem", 0, "0.1rem", 0]
  - block: markdown
    id: anfahrt
    content:
      title: Anfahrt
      text: |
        <iframe style="border:0; width: 80vw; max-width: 65ch; min-width: 20vw; height: 50vh" loading="lazy" frameborder="0" allowfullscreen src="https://www.google.com/maps/embed/v1/place?q=Doppelturnhalle+Oberfeld&key=AIzaSyC4vUMEDH0hY2gPC5FFIzmHb0p6F7_ZVh4"></iframe>
    design:
      spacing:
        padding: ["2vh", "2vw"]
  - block: markdown
    id: zeitplan
    content:
      title: Zeitplan
      text: |
        ## Samstag
        | Zeit | Kategorie | Was |
        | --- | --- | --- |
        | 08:30 | | Hallenöffnung |
        | 09:00 | KU10 | Einspringen |
        | 09:20 | KU10 | Wettkampfbeginn |
        | 10:15 | MU10 Abt. 1 | Einspringen |
        | 10:25 | MU10 Abt. 1 | Wettkampfbeginn |
        | 11:45 | MU10 Abt. 2 | Einspringen |
        | 12:05 | MU10 Abt. 2 | Wettkampfbeginn |
        | 13:30 | KU10 / MU10 | Rangverlesen |
        | 14:15 | KU13 | Einspringen |
        | 14:35 | KU13 | Wettkampfbeginn |
        | 15:20 | MU13 Abt. 1 | Einspringen |
        | 15:35 | MU13 Abt. 1 | Wettkampfbeginn |
        | 16:40 | MU13 Abt. 2 | Einspringen |
        | 17:00 | MU13 Abt. 2 | Wettkampfbeginn |
        | 18:30 | KU13 / MU13 | Rangverlesen |

        ## Sonntag
        | Zeit | Kategorie | Was |
        | --- | --- | --- |
        | 08:30 | | Hallenöffnung |
        | 09:15 | MU10 | Einspringen |
        | 09:35 | MU10 | Wettkampfbeginn |
        | 10:25 | KU16 / MU16 | Einspringen |
        | 10:45 | KU16 / MU16 | Wettkampfbeginn |
        | 12:30 | KU16 / MU16 | Rangverlesen |
        | 13:15 | D / A | Einspringen |
        | 13:45 | D / A | Wettkampfbeginn |
        | 16:00 | D / A | Rangverlesen |
  - block: markdown
    id: ranglisten
    content:
      title: Ranglisten
      text: |
        <h2>KU 10</h2>
        <a target="_blank" href="/ranglisten/KU10 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/KU10 Mannschaft.pdf">Mannschaft</a>
        <h2>A0</h2>
        <a target="_blank" href="/ranglisten/MU10 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/MU10 Mannschaft.pdf">Mannschaft</a>
        <h2>KU 13</h2>
        <a target="_blank" href="/ranglisten/KU13 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/KU13 Mannschaft.pdf">Mannschaft</a>
        <h2>MU 13</h2>
        <a target="_blank" href="/ranglisten/MU13 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/MU13 Mannschaft.pdf">Mannschaft</a>
        <h2>KU 16</h2>
        <a target="_blank" href="/ranglisten/KU16 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/KU16 Mannschaft.pdf">Mannschaft</a>
        <h2>MU 16</h2>
        <a target="_blank" href="/ranglisten/MU16 Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/MU16 Mannschaft.pdf">Mannschaft</a>
        <h2>A</h2>
        <a target="_blank" href="/ranglisten/A Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/A Mannschaft.pdf">Mannschaft</a>
        <h2>D</h2>
        <a target="_blank" href="/ranglisten/D Einzel.pdf">Einzel</a>
        <a target="_blank" href="/ranglisten/D Mannschaft.pdf">Mannschaft</a>
        <h2>Mixed</h2>
        <a target="_blank" href="/ranglisten/Mixed Mannschaft.pdf">Mannschaft</a>
---
