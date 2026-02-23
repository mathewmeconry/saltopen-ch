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
      title: SaltOpen 2026
      text: in Rohrdorf by TSV Rohrdorf & BKTV
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
        - statistic: "4634"
          description: |
            Sprünge
        - statistic: "331"
          description: |
            Turner*innen
        - statistic: "82"
          description: |
            Mannschaften
    design:
      # Reduce spacing
      spacing:
        padding: ["0.1rem", 0, "0.1rem", 0]
  - block: markdown
    id: anfahrt
    content:
      title: Anfahrt
      text: |
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4657.330575486152!2d8.312827577489701!3d47.421803600718924!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x479012556bb89e4b%3A0x2947dcb590c89f3b!2sSchulhaus%20Hinterb%C3%A4chli!5e1!3m2!1sde!2sch!4v1771852462742!5m2!1sde!2sch" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
        | 07:15 | | Hallenöffnung |
        | 08:00 | KU10 | Wettkampfbeginn |
        | 09:30 | KU10 | Rangverlesen |
        | 09:50 | MU10 1. Abt. | Wettkampfbeginn |
        | 11:05 | MU10 2. Abt. | Wettkampfbeginn |
        | 12:10 | MU10 3. Abt. | Wettkampfbeginn |
        | 13:35 | MU10 | Rangverlesen |
        | 14:00 | MU13 1. Abt. | Wettkampfbeginn |
        | 15:15 | MU13 2. Abt. | Wettkampfbeginn |
        | 16:45 | MU13 3. Abt. & KU13 | Wettkampfbeginn |
        | 18:30 | MU13 & KU13 | Wettkampfbeginn |

        ## Sonntag
        | Zeit | Kategorie | Was |
        | --- | --- | --- |
        | 06:45 | | Hallenöffnung |
        | 07:15 | MU16 Abt. 1 | Einspringen |
        | 07:30 | MU16 Abt. 1 | Wettkampfbeginn |
        | 08:55 | MU16 Abt. 2 | Einspringen |
        | 09:10 | MU16 Abt. 2 | Wettkampfbeginn |
        | 10:35 | KU16 | Einspringen |
        | 10:50 | KU16 | Wettkampfbeginn |
        | 12:15 | KU16 & MU16 | Rangverlesen |
        | 12:45 | D | Einspringen |
        | 13:00 | D | Wettkampfbeginn |
        | 14:20 | A 1. Abt. | Einspringen |
        | 14:35 | A 1. Abt. | Wettkampfbeginn |
        | 15:55 | A 2. Abt. | Einspringen |
        | 16:10 | A 2. Abt. | Wettkampfbeginn |
        | 17:30 | D & A | Rangverlesen |

  - block: markdown
    id: ranglisten
    content:
      title: Ranglisten
      text: |
        <h3><a style="text-decoration: underline" href="/ranglisten-2025">Ranglisten 2025</a></h3>
        <h3><a style="text-decoration: underline" href="/ranglisten-2024">Ranglisten 2024</a></h3>
---


<!--         <h2>MU 10</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU10 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU10 Mannschaft.pdf">Mannschaft</a>
        <h2>KU 10</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU10 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU10 Mannschaft.pdf">Mannschaft</a>
        <h2>MU 13</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU13 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU13 Mannschaft.pdf">Mannschaft</a>
        <h2>KU 13</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU13 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU13 Mannschaft.pdf">Mannschaft</a>
        <h2>MU 16</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU16 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/MU16 Mannschaft.pdf">Mannschaft</a>
        <h2>KU 16</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU16 Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/KU16 Mannschaft.pdf">Mannschaft</a>
        <h2>Damen</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/D Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/D Mannschaft.pdf">Mannschaft</a>
        <h2>Aktive</h2>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/A Einzel.pdf">Einzel</a>
        <a target="_blank" style="text-decoration: underline" href="/ranglisten/2025/A Mannschaft.pdf">Mannschaft</a>
        <br /> -->