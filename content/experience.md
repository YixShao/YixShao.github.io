---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me
    design:
      columns: 3
  - block: scientific-software
    id: scientific-software
    content:
      title: Scientific Software & Toolkits
      text: Software and analysis environments I use across multi-wavelength astronomy. Select a tool to open its official documentation or maintained project page.
      categories:
        - id: software-xray
          title: X-ray Analysis
          items:
            - name: HEASoft
              url: https://heasarc.gsfc.nasa.gov/docs/software/lheasoft/
            - name: CIAO
              url: https://cxc.cfa.harvard.edu/ciao/
            - name: XMM-Newton SAS
              url: https://xmm-tools.cosmos.esa.int/external/sas/current/doc/sas/index.html
            - name: Einstein Probe FXTDAS
              url: https://epfxt.ihep.ac.cn/analysis
        - id: software-pulsars-transients
          title: Pulsars & Transients
          items:
            - name: PSRCHIVE
              url: https://psrchive.sourceforge.net/
            - name: DSPSR
              url: https://dspsr.sourceforge.net/
            - name: PRESTO
              url: https://github.com/scottransom/presto
            - name: RIPTIDE
              url: https://riptide-ffa.readthedocs.io/en/latest/
            - name: TransientX
              url: https://github.com/ypmen/TransientX
            - name: PSRFITS_UTILS
              url: https://github.com/demorest/psrfits_utils
        - id: software-radio-interferometry
          title: Radio Interferometry
          items:
            - name: CASA
              url: https://casa.nrao.edu/
        - id: software-optical-nir
          title: Optical / NIR
          items:
            - name: IRAF
              url: https://iraf-community.github.io/
            - name: PyRAF
              url: https://iraf-community.github.io/pyraf.html
            - name: EsoRex
              url: https://www.eso.org/sci/software/cpl/esorex.html
  #- block: resume-awards
  #  content:
  #    title: Awards
  #    username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
---
