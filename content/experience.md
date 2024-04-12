+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "CEO"
  company = "GenCoin"
  company_url = ""
  location = "California"
  date_start = "2017-01-01"
  date_end = ""
  description = """
  Responsibilities include:
  
  * Analysing
  * Modelling
  * Deploying
  """

[[experience]]
  title = "Professor"
  company = "University X"
  company_url = ""
  location = "California"
  date_start = "2016-01-01"
  date_end = "2016-12-31"
  description = """Taught electronic engineering and researched semiconductor physics."""

  - block: experience
    content:
      title: Experience
      text: |-
        Positions are current/final positions at each experience period. Full experience is in my [ CV](https://chaofengqing.github.io/chao_lab/files/cv_CHAOFENGQING.pdf).
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: CUHK (Shenzhen)
          company_url: https://hss.cuhk.edu.cn/en
          company_logo: icon_cuhksz
          location: Shenzhen, China
          date_start: '2024-05-06'
          date_end: ''
          description: Computational Social Science, School of Humanities and Social Science
          # description: |2-
          #     Responsibilities include:
          #
          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Research Scientist
          company: KAUST
          company_url: https://www.kaust.edu.sa/
          company_logo: icon_kaust
          location: Thuwal, Saudi Arabia
          date_start: '2019-07-21'
          date_end: '2024-01-15'
          description: Biostatistics Group, Computer, Electrical and Mathematical Sciences and Engineering
        - title: Research Fellow
          company: NUS
          company_url: https://nus.edu.sg/
          company_logo: icon_nus
          location: Singapore
          date_start: '2012-07-10'
          date_end: '2019-07-19'
          description: ''
    design:
      columns: '2'

+++

