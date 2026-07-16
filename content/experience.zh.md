---
title: '经历'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-experience
    content:
      username: me-zh
    design:
      date_format: '2006年1月'
      is_education_first: false
  - block: resume-skills
    content:
      title: 技能与爱好
      username: me-zh
    design:
      columns: 3
  - block: scientific-software
    id: scientific-software
    content:
      title: 科研软件与工具包
      text: 我在多波段天文研究中使用的软件与数据分析环境。点击工具名称可访问其官方文档或维护中的项目主页。
      categories:
        - id: software-xray
          title: X射线数据分析
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
          title: 脉冲星与暂现源
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
          title: 射电干涉阵数据处理
          items:
            - name: CASA
              url: https://casa.nrao.edu/
        - id: software-optical-nir
          title: 光学 / 近红外数据分析
          items:
            - name: IRAF
              url: https://iraf-community.github.io/
            - name: PyRAF
              url: https://iraf-community.github.io/pyraf.html
            - name: EsoRex
              url: https://www.eso.org/sci/software/cpl/esorex.html
  - block: resume-languages
    content:
      title: 语言
      username: me-zh
---
