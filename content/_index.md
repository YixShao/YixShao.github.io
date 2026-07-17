---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Shaoyixuan.pdf
      headings:
        about: ''
        education: ''
        interests: Research Interests
        skills: Research Skills
      research_interests:
        - title: Pulsars
          url: /interests/pulsars/
        - title: Fast radio bursts
          url: /interests/fast-radio-bursts/
        - title: Supernova remnants
          url: /interests/supernova-remnants/
      research_skills:
        - title: X-ray
          url: /experience/#software-xray
        - title: Radio · Pulsar data
          url: /experience/#software-pulsars-transients
        - title: Radio · Interferometric imaging
          url: /experience/#software-radio-interferometry
        - title: Optical / NIR
          url: /experience/#software-optical-nir
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: balanced # Options: compact (long names), balanced (default), display (short names)

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am interested in some of the most fascinating high-energy phenomena in the Universe, such as fast radio bursts and energetic outbursts from neutron stars, as well as the birth and long-term evolution of neutron stars. In particular, I focus on how their surrounding environments and internal physics shape the observed emission. I believe that multi-wavelength observations provide a uniquely comprehensive view of these extreme systems, allowing us to connect physical processes across different energy bands.
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: News & Recent Activities
      subtitle: ''
      text: |-
        **2026**

        - **June · Manuscript** — Submitted a manuscript on radio pulsars.
        - **May · Conference presentation** — “Polarization-Dependent Distributions of Single Pulse Intensity Revealed by FAST,” APRIM 2026, Hong Kong, China.
        - **February · Publication (co-author)** — “Pulsar Gleaners: Discovery of 19 Pulsars in FAST Archival Data at |b| < 5° and Decl. < −5°,” *The Astrophysical Journal*, 997, 210.
        - **February · Publication (co-author)** — “Search for Radio Pulsations from Neutron Star Candidates in Detached Binaries,” *The Astrophysical Journal*, 997, 222.

        <details class="mt-8 rounded-xl border border-gray-200 bg-white/60 p-5 shadow-sm dark:border-gray-700 dark:bg-gray-800/40">
        <summary class="cursor-pointer font-semibold text-primary-600 dark:text-primary-300">Show 10 earlier activities</summary>

        **2025**

        - **October · Publication (first author)** — “Absence of Radio Emission Reveals an Exceptionally Weak Explosion of the Putative Historical Supernova Pa 30,” *The Astrophysical Journal Letters*, 992, L6.
        - **October · Publication (co-author)** — “RRAT J2325−0530: A Rotating Radio Transient with an Atypical Waiting-time Distribution,” *The Astrophysical Journal*, 991, 201.
        - **September · Publication (co-author)** — “A Target Search for Fast Radio Bursts Associated with Two Fast Blue Optical Transients: AT2018cow and CSS161010,” *The Astrophysical Journal*, 990, 93.
        - **August · Conference presentation** — “The Absence of Radio Emission Reveals an Exceptionally Weak Explosion for the Probable Historical Supernova Pa 30,” 16th Zhang Heng Academic Symposium, Qingdao, China.

        **2024**

        - **December · Conference presentation** — “GTC Optical/Near-infrared Upper Limits and NICER X-Ray Analysis of SGR J1935+2154 for the Outburst in 2022,” PSR 2024, Guizhou, China.
        - **December · Conference presentation** — “A Pipeline to Search for Special Magneto-active Regions near Fast Radio Bursts,” FRB 2024, Khao Lak, Thailand.
        - **November · Publication (first author)** — “GTC Optical/Near-infrared Upper Limits and NICER X-Ray Analysis of SGR J1935+2154 for the Outburst in 2022,” *The Astrophysical Journal*, 976, 99.
        - **November · Publication (co-author)** — “Triggering the Untriggered: The First Einstein Probe-detected Gamma-Ray Burst 240219A and Its Implications,” *The Astrophysical Journal Letters*, 975, L27.
        - **October · Publication (co-author)** — “Discovery of a Millisecond Pulsar Associated with Terzan 6,” *The Astrophysical Journal Letters*, 974, L2.
        - **March · Publication (co-author)** — “Upper Limits on the Radio Pulses from Magnetars and a Central Compact Object with FAST,” *The Astrophysical Journal*, 963, 151.

        </details>
    design:
      columns: 1
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: photo-gallery
    id: gallery
    content:
      title: 'Gallery'
      text: A selection of photographs from nature and everyday life. Click any image to view the original.
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - events
  #  design:
  #    view: card
  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
      # Page type to display. E.g. post, talk, publication...
  #    page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 10
      # Filter on criteria
  #    filters:
  #      author: ''
  #      category: ''
  #      tag: ''
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ''
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: card
      # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
