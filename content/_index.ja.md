---
# Leave the homepage title empty to use the site title
title: "Atsutomo Yara (屋良 淳朝)"
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    content:
      title: 最新の論文
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: resume-experience
    content:
      title: 職歴
      username: admin
    design:
      date_format: '2006年1月'
      is_education_first: false
  - block: resume-awards
    content:
      title: 受賞
      username: admin
---
